# Mirror or Self-Portrait

**A Systematic Review of AI Ethics Literature Using an Emergent Double-Axis Framework**

Jo Cichon · M.S. Computer Science, Northeastern University
Faculty Advisor: Dr. Brianna Dym

---

## Overview

AI ethics literature is broad, interdisciplinary, and often framed inconsistently. Many papers rest on philosophical assumptions they never state. This project looks at *how* ethical meaning is constructed in AI discourse, not only *what* each paper considers ethical.

A systematic literature review produced a two-axis framework. That framework is then applied back to the literature to show how individual papers position responsibility, agency, and accountability.

This repository contains the companion web page for the research poster, along with the poster and working drafts.

## The framework

Papers are read along two intersecting dimensions:

- **AI lens — Mirror vs. Self-Portrait.** Is AI treated as a *reflection* of human data, behavior, and institutions, or as an *artifact* of deliberate human design choices and values?
- **Ethics lens — Checklist vs. Situated.** Is ethics framed as rules, compliance, and mitigation, or as contextual, relational, and constructed in practice?

|                | **Mirror**                  | **Self-Portrait**       |
|----------------|-----------------------------|-------------------------|
| **Checklist**  | Mitigation Framing          | Responsible Design      |
| **Situated**   | Sociotechnical Reflection   | Ethics as Construction  |

## Method

1. **Search.** ACM Digital Library, full research articles, using combinations of "artificial intelligence," "philosophy," and "existential."
2. **Screening.** Papers were kept if they engaged, explicitly or implicitly, with human agency, meaning-making, responsibility, identity, or the human–AI relationship.
3. **Framework development.** Recurring patterns across the corpus were refined, through iterative comparison, into the two axes.
4. **Coding.** Each accepted paper is read in full. Representative quotes are assigned to a quadrant with a 1–5 strength-of-fit score, and each paper receives a weight for every quadrant.

## Project phases

| Phase | Focus                                              |
|-------|----------------------------------------------------|
| 1     | Human agency and meaning-making with technology; the framework emerges |
| 2     | AI-specific ethics literature; the framework is applied |
| 3     | Labeled dataset development                        |
| 4     | ML classifier and lifecycle mapping                |

## Repository contents

```
.
├── index.html          Companion page: framework, method, coding walkthrough
├── css/
│   └── styles.css      Stylesheet for index.html
└── docs/
    ├── Cichon_Jo_MirrorOrSelfPortrait.pdf   Research poster
    ├── Abstract_draft.docx                  Abstract (draft)
    ├── Background Draft.docx                Background section (draft)
    ├── Methods Draft.docx                   Methods section (draft)
    └── SLR Notes.docx                       Systematic literature review notes
```

## Viewing the page

The site is plain HTML and CSS with no build step. Open `index.html` in a browser, or serve the folder locally:

```bash
python3 -m http.server
# then visit http://localhost:8000
```
