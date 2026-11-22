# Career Coach AI
A static, browser-based career and programming study assistant. Built with ChatGPT assistance for COSC 4272. It uses supervised multinomial naive Bayes classification over 45 labeled examples across nine categories, followed by a curated response. It is not a generative LLM.

## Run
Open `index.html` from the portfolio folder, or serve the repository root using `python -m http.server 8000` and visit `/ai-assistant/`. No API key, installation, or network inference required.

## Architecture
`model.js` contains training examples, tokenization, a vocabulary, Laplace-smoothed log likelihoods, and confidence-based rejection. `ui.js` handles form submission, suggested questions and reset. All messages are inserted as text, not active HTML. No conversation is stored or sent externally.

## Test
Run `node ai-assistant/test.js` from the repository root. Tests cover all nine intents, an unrelated query, an empty query and markup-like input. Classifier confidence is a normalized model score, not a calibrated probability of correctness. The example corpus is small, and ambiguous, misspelled or unusual wording can lead to low-confidence or incorrect classifications. It cannot provide current job openings or individualized professional advice.

## Improvement opportunities
Expand labeled paraphrases, build a held-out validation set, measure confusion by class, and add accessibility testing. A server-side LLM integration could be considered later without exposing API keys in GitHub Pages. Review every response for accuracy.
