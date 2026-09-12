# A-Level Revision System

Personal revision management project for Year 13, covering four A-level qualifications. Structure established 6 September 2026.

## Qualifications (verified)

| # | Subject | Exam board | Qualification | Spec code | Notes |
|---|---|---|---|---|---|
| 1 | Biology | AQA | A-level | **7402** | |
| 2 | Chemistry | AQA | A-level | **7405** | |
| 3 | Physics | AQA | A-level | **7408** | Optional topic: **Astrophysics** only |
| 4 | Mathematics | Pearson Edexcel | A-level (UK, domestic) | **9MA0** | Not International Advanced Level; not Further Mathematics |

Verified directly against the live AQA specification pages and the official Pearson Edexcel specification PDF on 6 September 2026 (sources listed at the bottom of this file). One correction surfaced during verification: AQA Physics 7408 has **five** optional topics, not four — Astrophysics, Medical physics, Engineering physics, Turning points in physics, and Electronics (specification sections 3.9–3.13). Only Astrophysics is in scope for this project.

## Project structure

```
ALevelRevision/
├── Biology_AQA_7402/
├── Chemistry_AQA_7405/
├── Physics_AQA_7408_Astrophysics/
├── Mathematics_Edexcel_9MA0/
├── STUDENT_INFORMATION_FORM.md
├── DOCUMENTS_TO_UPLOAD.md
├── QUALITY_CONTROL_AND_BOUNDARIES.md
└── PROGRESS_DASHBOARD.md
```

Each subject folder contains an identical set of 12 empty sections (defined in that subject's `_SECTION_GUIDE.md`):

1. `01_Specification_Audit`
2. `02_Diagnostic_Assessments`
3. `03_Detailed_Topic_Packs`
4. `04_Concise_Revision_Sheets`
5. `05_Flashcards`
6. `06_Original_Exam_Questions`
7. `07_Worked_Solutions`
8. `08_Mistake_Log`
9. `09_Mastery_Tracker`
10. `10_Spaced_Retrieval_Queue`
11. `11_Timed_Assessments`
12. `12_Full_Mock_Examinations`

Nothing inside any section folder has been populated yet — this is a scaffolding-only stage.

## Guardrails against wrong-board / wrong-topic content

Full policy in `QUALITY_CONTROL_AND_BOUNDARIES.md`. In short: subject identity is fixed at folder level, every content file from Stage 1 onward will carry a header stating board + code + (for Physics) option, and no specification statement, equation, or practical is written into any pack until it has been checked against an uploaded official source or explicitly flagged as unconfirmed.

## Current stage

**Stage 0 — scaffolding.** Structure created; no diagnostic, topic-pack, flashcard, or question content exists yet.

Stage 1 (specification audit) begins once:
- the student information form is completed, and
- the official specification / data-booklet documents are uploaded (or their absence is confirmed — in which case verified web sources will be used and clearly flagged as such until cross-checked against your own paperwork).

## Sources consulted for verification (6 September 2026)

- https://www.aqa.org.uk/subjects/biology/a-level/biology-7402/specification
- https://www.aqa.org.uk/subjects/chemistry/a-level/chemistry-7405/specification
- https://www.aqa.org.uk/subjects/physics/a-level/physics-7408/specification/subject-content
- https://www.aqa.org.uk/subjects/physics/a-level/physics-7408/specification/specification-at-a-glance
- https://qualifications.pearson.com/content/dam/pdf/A%20Level/Mathematics/2017/specification-and-sample-assesment/a-level-l3-mathematics-specification-issue4.pdf
