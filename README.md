# BBMB 1200 — Chemistry of Beer (course demos)

- **`brew-mud/`** — source for the Brew MUD, a text-adventure study guide for the class
  (Python). Copy of `swnisu-mud/brew-mud`; the live site deploys from that original repo.

- **`index.html`**: landing page for the Exam 1 review games (open it in a browser; no build step needed).
  - **`millionaire.html`**: *Who Wants to Be a Brewmaster?*, a single-player "Who Wants to Be a Millionaire" game: 15 questions of increasing difficulty, safe havens at $1,000 and $32,000, and three lifelines (50:50, Ask the Class, Swap Question).
  - **`quiz.html`**: a standard review quiz (default 50 questions) filtered by subject and difficulty, with explanations, a per-subject score breakdown, and a retry of missed questions.
  - **`questions.js`**: shared bank of ~250 questions tagged by subject and difficulty (1–5), drawn from Lectures 1–3 and the Exam 1 review. Answer choices are shuffled every time they are shown. To add a question, append a row to `RAW_QUESTIONS`.
