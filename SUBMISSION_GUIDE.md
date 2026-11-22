# Submission guide — COSC 4272

## Before uploading
1. Your supplied professional photograph is already included at `assets/profile.jpg`. No replacement is needed.
2. The resume has been confirmed by the student. Review the portfolio and update certifications if you have any. Do not claim unearned certificates. Review the About Me text for accuracy.
3. Add a genuine Community Garden course project screenshot and an authorized GitHub project link if you have them. Replace the existing conceptual screenshot and its caption in `index.html` as appropriate; it currently shows a reconstructed case study only. If you use another course project instead, update the title, description, stack, screenshot and link. Verify the Snake Arcade and Mount Sahara links.
4. Open the AI demo and Focus Board. Run `node ai-assistant/test.js` if Node is installed. Review the implementation and be ready to explain the classifier. Add your own actual development/testing notes to the AI prompt log (do not invent a prompt history).

## Publish using GitHub in your browser
1. Extract the ZIP. Sign in to GitHub as Nigelpat. Go to https://github.com/new. Name the repository `github-portfolio`, choose Public, and create it (do not initialize it with a README if uploading these files).
2. On the new repository page choose uploading an existing file (or Add file > Upload files). Drag all contents **inside** the extracted github-portfolio folder, not the outer folder itself, so `index.html` and `README.md` are in the repository root. Keep subfolders intact. Use a meaningful commit message such as `Add portfolio, AI assistant and career documents`. If the browser omits the hidden `.nojekyll` file, the site can still work without it; create the file manually if needed.
3. Go to repository Settings > Pages. Choose Deploy from a branch, branch `main`, folder `/ (root)`, and Save. Check the Actions tab if deployment fails. Once GitHub reports the site published, open https://nigelpat.github.io/github-portfolio/ in a private browsing window.
4. Verify every project, resume download, embedded resume, navigation and contact link. Confirm source links open the correct GitHub folders. If the instructor requires the AI project in a separate repository, publish its source plus the shared stylesheet in a separate public repository and update the source link; the provided public portfolio repository already contains the complete AI project.

## Seven submission items (page 9 of assignment)
- GitHub repository URL: https://github.com/Nigelpat/github-portfolio (verify after publication)
- GitHub Pages URL: https://nigelpat.github.io/github-portfolio/ (verify after publication)
- `resume.pdf`
- `docs/AI_Project_Documentation.pdf`
- `docs/Job_Search_Analysis.pdf`
- `docs/Skills_Gap_Analysis.pdf`
- `docs/AI_Prompt_Log.pdf`

Do not submit the expected URLs until they actually work. No repository or live deployment has been created by ChatGPT. Upload the five PDFs directly if Blackboard requests files; provide both URLs separately.
