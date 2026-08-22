<div align="center">

# ELL305 — Term Paper / Project

### Consolidated Instructions, Schedule & Submission Guide

![Course](https://img.shields.io/badge/Course-ELL305-blue)
![Status](https://img.shields.io/badge/Draft%201-Due%2024%20Aug%202026%2C%2008:00-red)
![Platform](https://img.shields.io/badge/Submission-Gradescope-brightgreen)
![Format](https://img.shields.io/badge/Files-1%20.tex%20%2B%201%20.pdf-orange)

*general rules and shit. project/termpaper specific is below*

*ALSO NOTE I MADE TS FOR MYSELF AND SOME OF MY PEERS SO IF YOU ARE USING IT CROSS CHECK EVERY INFORMATION WITH SOMEONE IDK*

**[Term Paper Guide →](./TERM_PAPER.md)** &nbsp;·&nbsp; **[Project Guide →](./PROJECT.md)** &nbsp;·&nbsp; **[Sources →](./sources)**

</div>

---
# UPCOMING DEADLINE - 24th AUG 8AM MORNING GET TO WORK AHHHHHHHHHHHH

## contents

- [overview](#overview)
- [submission rules for ALL drafts](#submission-rules)
- [doubts](#doubts)
- [DRAFT 1](#draft-1)
- [sources](#sources)

---

## Overview

| Item | Detail |
|---|---|
| Submission Platform | [Gradescope](https://gradescope.com) |
| Textbook | [Sarangi — Computer Architecture (archbook.pdf)](https://srsarangi.github.io/archbook/archbook.pdf) |
| Authorship | Term Paper: teams of 1–360 · Project Report: single author only |
| Files per submission | Exactly **2** — one `.tex` source + one compiled `.pdf` |

> Each submission is **cumulative**: everything corrected in Draft *n* (based on feedback) carries forward into Draft *n+1*, plus new content is added.

---

## Submission Rules

Every submission (including Draft 1) requires **two, and only two, files** — this applies identically to Term Paper and Project:

1. **A single LaTeX file** containing *all* diagrams, graphs/plots, flowcharts, and circuit diagrams inline — no second `.tex` file, no auxiliary asset files, **no `.zip`**
2. **A single PDF file** — must be reproducible by compiling file (1) above

---

## Doubts

```mermaid
flowchart TD
    Q["I have a doubt"] --> T["Ask TA(s) / Utkarsh Roy\nat Embedded Lab FIRST"]
    T --> R{Still stuck?\nWhich chapter is it from?}
    R -->|"Chapters 1–12"| P1["Prof. Sumantra DuttaRoy"]
    R -->|"Chapter 13"| P2["Prof. Subrat Kar"]
```
(no idea why it created a fucking chart for this but ill take it)
> Heads up: the first question either professor will ask is *"What did the TAs / Utkarsh say?"* — so always route through the TAs first.
 
**TA Contacts:**
 
| TA | Email |
|---|---|
| Utkarsh Roy (Head TA) | [eez238339@iitd.ac.in](mailto:eez238339@iitd.ac.in) |
| Garima Singhal | [eez238573@ee.iitd.ac.in](mailto:eez238573@ee.iitd.ac.in) |
---

## DRAFT 1

Per Prof. Subrat Kar: Draft 1 is explicitly a **progress report**, not a preliminary version of the final paper. Per Head TA Utkarsh Roy, it must include a section titled **"Background Preparations"** describing the work completed so far, appropriately illustrated (circuit diagrams, flowcharts, figures, code snippets as needed).

```mermaid
flowchart TD
    subgraph Prep["Background Preparation"]
        A1[Pick topic / experiments] --> A2[Do the groundwork]
        A2 --> A3[Log references / results]
    end

    subgraph D1["Draft 1 — 24 Aug 2026, 08:00"]
        B1["Write 'Background Preparations' section\n(see TERM_PAPER.md / PROJECT.md for exact content)"]
        B2["Illustrate appropriately"]
        B3["Move code to Appendix, syntax-highlighted"]
        B1 --> B2 --> B3
    end

    subgraph Compile["Compile & Submit"]
        C1["Single .tex (all diagrams inline)"] --> C2["Compile to single .pdf"]
        C2 --> C3["Upload both to Gradescope"]
    end

    subgraph Iterate["Draft 2 / 3 / Final"]
        E1["Incorporate feedback"] --> E2["Correct + append new content"]
    end

    Prep --> D1 --> Compile --> Iterate
    Iterate -.->|repeats each cycle| D1
```

The exact content of the "Background Preparations" section **differs** for Term Paper vs. Project — see the respective guide.

---

## Sources

Every instruction in this README and in `TERM_PAPER.md` / `PROJECT.md` is paraphrased/organized from the original communications below, kept verbatim so you can cross-check:

| # | Source | Sender | Applies to |
|---|---|---|---|
| 1 | [Submission logistics email](./sources/subrat_mail_17thAug.md) | Course communication | Both |
| 2 | [Draft 1 instructions](./sources/utkarsh_teams_20thAug.md) | Utkarsh Roy (Head TA) | Both |
| 3 | [Draft 1 tips](./sources/subrat_teams_21stAug.md) | Prof. Subrat Kar | Project |
| 4 | [Mandatory tooling email](./sources/garima_mail_21stAug.md) | Garima Singhal (TA) | Term Paper |

---

<div align="center">

*This README consolidates official course communications for ELL305. Always cross-check against the original email/Gradescope announcements for any updates.*

</div>
