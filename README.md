# ICGS137 — Witchcraft and Gender Representation

An unofficial student archive for **ICGS137: Witchcraft and Gender Representation**, a four-credit general education course I took at Mahidol University International College (MUIC) during Trimester 3 of the 2025–2026 academic year.

> [!IMPORTANT]
> These are student notes, not official course materials. They may contain omissions, transcription errors, or my own interpretation of a lecture. When something here conflicts with the lecturer's slides, study guides, instructions, or announcements, trust the official source.

## Browse the notes

The easiest way to read the archive is through the MkDocs site:

**[jiraroj-wir.github.io/MUIC-ICGS137-Witchcraft-and-Gender-Representation](https://jiraroj-wir.github.io/MUIC-ICGS137-Witchcraft-and-Gender-Representation/)**

The site contains consolidated midterm and final notes, notes organized by lecture date, and collections of questions mentioned or strongly signaled during class. I missed approximately two classes, so the archive is fairly complete but should not be treated as a complete record of the course.

## About the course

The course was taught by **Prof. Pattaka Sa-ngimnet**, who also taught [ICGS112: Geography of Human Activities](https://github.com/jiraroj-wir/MUIC-ICGS112-Geography-of-Human-Activities). I therefore began ICGS137 with some idea of what to expect. The two courses were similar in their lecture and examination styles: each class was primarily lecture-based, the explanations generally followed the slides, and the assessments emphasized written answers.

Across the trimester, the course introduced topics including:

- distinctions and relationships among sex, gender, gender identity, expression, and sexuality;
- theories such as biological essentialism, social constructionism, queer theory, and intersectionality;
- feminist perspectives, movements, achievements, disagreements, and limitations;
- the historical and continuing marginalization of women and gender-diverse people;
- gender in Thai history, institutions, law, culture, and social life;
- cultural norms and the ways they are formed, maintained, and challenged; and
- witchcraft, witch hunts, gendered accusations, representations of witches, and selected historical case studies.

This was a broad undergraduate general education course rather than an intensive theory course. Its main value for me was learning the historical background, terminology, theories, and categories used to discuss these subjects. I approached the material mainly to understand what the course presented and pass it, not to use this repository to advocate a political position. The notes may preserve claims, terminology, or generalizations made during lectures; their inclusion records the course content and does not necessarily mean that I endorse them.

## Class and assessment format

The class environment was relaxed, although the course was not entirely effortless. For someone looking for a four-credit, lecture-based general education course with four assignments, a midterm, and a final examination, I would describe it as manageable—but probably not among the lightest options.

- **Classes:** Primarily lectures, with some discussion and an end-of-term witchcraft demonstration.
- **Attendance:** Taken in most classes, but handled fairly casually in my experience. Students arriving late could normally speak with the lecturer after class to correct the attendance record.
- **Midterm:** A paper-based written exam with more than ten short-answer questions.
- **Final:** Two long essays chosen from ten announced essay topics.
- **Environment:** Generally calm and flexible; eating, resting, or quietly doing something else was tolerated as long as it did not disturb other people.

Some discussions used Thai, more often than in ICGS112. From my experience, this was usually for detailed discussion of Thai social issues or for light conversation—not an attempt to exclude international students. Material important to the course or examination was generally also explained in English. A student who does not speak Thai could usually continue following the main lecture.

The lectures were straightforward and closely paralleled the slides. At times, some explanations or lines of reasoning felt simplified or broad to me. That may be appropriate for an accessible undergraduate general education course, and it made the material easy to follow, but it is another reason not to treat these notes as a definitive source on gender studies, history, or witchcraft.

The witchcraft portion was the part I found most interesting. The final demonstration underdelivered a little compared with what I had imagined, but it was still fun—and I will leave its details as a surprise for future students.

## Repository scope

This repository is centered on lecture notes. It does not include my assignments: they were highly opinion-based, and I prefer not to publish my personal views on gender or politics online.

The main source files are under [`docs/`](docs/):

```text
docs/
├── index.md              # Site home page
├── midterm/              # Midterm-period notes and questions
└── final/                # Final-period notes and questions
```

## Build the site locally

The site uses [MkDocs](https://www.mkdocs.org/) with the [Material for MkDocs](https://squidfunk.github.io/mkdocs-material/) theme. Python 3.11 is used by the deployment workflow.

```bash
python3 -m venv .venv
source .venv/bin/activate
python -m pip install -r requirements.txt
mkdocs serve
```

Open <http://127.0.0.1:8000> to preview the site. To create a static build instead, run:

```bash
mkdocs build --strict
```

The generated site is written to `site/`. Pushes to `main` also trigger the GitHub Actions workflow that builds and deploys the notes to GitHub Pages.

## Archival status

This repository documents my experience of one offering of ICGS137 in Trimester 3, academic year 2025–2026. Course content, assessment formats, policies, and teaching practices may change in later trimesters. Future students should rely on their current syllabus, study guides, official course materials, and lecturer's instructions.
