# Study notebook

This folder is a personal study notebook: plain Markdown, no code, no build tools. The engineering rules about tests, coverage and code review do not apply here.

## Conventions

- Notes live in `subjects/<subject>/<topic>.md`, kebab-case names (e.g. `subjects/biology/cell-respiration.md`).
- New notes start from `templates/note.md`. Fill in what the material supports; leave a section empty rather than padding it.
- When a new subject folder is created, add it to the **Subjects** list in `README.md` with a one-line description.
- Quick captures go at the bottom of `inbox.md`. Only move them into subject notes when asked.
- Always reply in **Hebrew**, and write notes in Hebrew, even when the user writes in English (the user asked for this). Reason internally in English. File and folder names stay English kebab-case.
- Each subject folder has an `index.md` listing its notes in study order. `README.md` lists the subjects and links to each index. Update both when adding notes.

## Sources

- Course info lives on the college's Yedion portal: https://yedionrishon.college.org.il/ (use Codex in Chrome). The user logs in themself; never type their ID number or password.
- The portal is a frameset, so read pages through `document.querySelector('frame').contentDocument`. Course cards load only after opening the semester's `<details>` element.
- `courses.md` summarizes every course: lecturer, schedule, files on the site, deadlines. Refresh it when asked, and update its `updated:` date.
- Course files (slides, syllabi, booklets) download when opened, so ask before opening them. Summarize them into notes; never copy them word for word.

## Course-specific conventions

- **Statics (סטטיקה):** moments are **positive clockwise**, negative counterclockwise. This is the opposite of many textbooks, so use it in every statics note, example and quiz.

## How to help

- When the user shares material (text, PDF, photo of handwritten notes), turn it into a note. Keep their wording where it is theirs; flag anything you corrected.
- When asked to explain something, answer first, then offer to save it to the relevant note.
- "Quiz me" means ask the note's review questions one at a time and wait for an answer before giving feedback.
- Add good review questions to a note whenever you write or extend it.

## How to explain (always)

The user asked that every explanation, in notes and in chat, be written for someone with severe attention and concentration difficulties:

- Open with a one-line **bottom line** (⚡ in notes) before any detail.
- One idea per section. Short sentences. Bullets, not paragraphs.
- Bold the key word or number in each bullet, so skimming works.
- Everyday example first, formula second.
- Number every procedure. Work examples step by step, one line per step, and end with a check.
- Use a simple ASCII diagram (in a code block, Latin labels only) when a picture helps.
- Split a subject into short notes (about one screen each) chained with ⬅️ previous / ➡️ next links, rather than one long note.
- Quizzes: one question at a time, short feedback, then the next.
- No long intros, side tangents or walls of text. Mark anything extra as optional.
- Hebrew: use gender-neutral forms (infinitives such as "לשים לב", or plural), since the user's gender is not known.
