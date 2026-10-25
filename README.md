# BBMB 1200 — Chemistry of Beer (course demos)

- **`brew-mud/`** — source for the Brew MUD, a text-adventure study guide for the class
  (Python). Copy of `swnisu-mud/brew-mud`; the live site deploys from that original repo.

- **`index.html`**: landing page for the Exam 1 review games (open it in a browser; no build step needed).
  - **`millionaire.html`**: *Who Wants to Be a Brewmaster?*, a single-player "Who Wants to Be a Millionaire" game: 15 questions of increasing difficulty, safe havens at $1,000 and $32,000, and three lifelines (50:50, Ask the Class, Swap Question).
  - **`quiz.html`**: a standard review quiz (default 50 questions) filtered by subject and difficulty, with explanations, a per-subject score breakdown, and a retry of missed questions.
  - **`questions.js`**: shared bank of ~250 questions tagged by subject and difficulty (1–5), drawn from Lectures 1–3 and the Exam 1 review. Answer choices are shuffled every time they are shown. To add a question, append a row to `RAW_QUESTIONS`.

## Exam 2 review

- **`millionaire-exam2.html`**: Exam 2 edition of Who Wants to Be a Brewmaster? Uses the original game's 15-question prize ladder, three lifelines, safe havens, and answer confirmation.
- **`questions-exam2.js`**: 80 practice questions, with 16 at each difficulty (1–5), covering yeast and brewing microbes, sugar transport and fermentation, oxygen and flavor, sulfur chemistry, yeast domestication, and browning. Each explanation includes deck and slide references.
- Sources: the Exam 2 decks in `Lectures/Exam 2 material`, including the 2026 sulfur update. The GMO yeast lecture (Lecture 12) was not covered in class, so its questions were removed. Browning is included because it appears in slide 18 of the Exam 2 review. Older review statements about domestication are superseded by the updated lectures.
- Exam 2 scores and seen-question history use separate localStorage keys. The class poll is simulated and may be wrong. Questions are study aids, not predictions of exam content.
- **Study guide:** `brew-mud/docs/BBMB_1200_Second_Test_Study_Guide.docx`, the Exam 2 counterpart of the first-test guide, with summaries, 25 review questions, an answer key, and links to the Exam 2 game.
- Open `index.html` in a browser, or serve the folder as static files. No install or build step is needed.

