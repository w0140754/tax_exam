# TaxLab — TAX 201 final-exam study website

A static, mobile-friendly study companion for Saskatchewan Polytechnic TAX 201, based on the provided 2024 instructor questions and recovered study archive. It contains **106 free-response questions across all seven learning outcomes**, plus 38 flashcards and 31 independently keyed quick multiple-choice drills.

## Open the site

Open `index.html` in Chrome, Firefox, Edge, or Safari. The study site runs offline with no dependencies, account, analytics or server. Open a question, write an attempt, reveal the reference solution, then mark it **Confident** or **Needs review**. Browser progress is saved only on that device in `localStorage`; classmates cannot see each other's scores. For official PDF solutions, keep the included `solutions/` folder beside `index.html`.

## Share it as a class website

1. Unzip `TAX201_StudyLab_Shareable.zip`.
2. For GitHub Pages: create a repository, upload `index.html` and the `solutions/` folder to its root, and enable **Settings → Pages → Deploy from branch → main / (root)**.
3. After the site builds, give classmates the generated GitHub Pages URL. Alternatively, drag the unzipped folder onto a static-site hosting provider such as Netlify Drop.
4. The linked official solution PDFs only work when that folder is uploaded too. `index.html` by itself works offline with the summarized answers embedded on each card.

**Source permissions:** The course handout explicitly bears a no-reproduction notice. Check with the instructor before publishing those source questions or instructor answer PDFs publicly. For private sharing within your class, follow your program's guidance.

## Site features

- Syllabus overview of **20 learning steps** under **LO1–LO7**.
- 106 source-labelled free-response questions from original graded Quiz 2, original Quiz 4, Appendix B demos, Appendix C handouts, Chapter 3 extra package, reconstructions and clearly labelled supplemental questions.
- Written practice in syllabus order, shuffled, unseen, saved, and missed-only modes. Students see no solution until clicking “Reveal.” Written work is **self-graded**, not auto-marked.
- A mixed 21-question mock exam sampling three questions from each learning outcome.
- 31 auto-marked concept drills with explanations.
- 38 definition flashcards; a local mark-known/needs-review tracker.
- Searchable question bank, starred questions, confidence dashboard, light/dark theme, mobile layout, and exportable personal progress JSON.

## Accuracy notes

The originals were for the **2024 taxation year**. Do **not** use this site to prepare an actual 2026 income tax return. Source figures for automobile operating benefits, tax credits and gains may change between tax years.

Several provided answer materials appear internally inconsistent, and the website flags them: (i) Anne Bell extra practice lists $75,000 salary in the prompt but $73,000 in the solution; (ii) Jay Walker's 2024 solution shows taxable benefits exceeding gross disability payments; (iii) some fully computed T1 instructor solutions are scanned PDFs; and (iv) certain older demonstration figures conflict. For those items the reference answer is labelled provisional or points to the relevant original PDF rather than silently asserting unverified arithmetic.

Fictitious SINs and street addresses shown in instructor sample tax forms were excluded from the study-site question text. The site is independently produced and is **not an official Saskatchewan Polytechnic website**.
