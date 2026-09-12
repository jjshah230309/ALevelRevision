# Quality Control & Subject-Boundary Policy

This file is the standing check applied before any content (topic pack, flashcard, question, worked solution, mock paper) is written into this project. It exists because four qualifications share subject names that every exam board also teaches (Biology, Chemistry, Physics, Maths), and because AQA Physics alone has five optional topics that are easy to mix up with the wrong one.

## 1. Fixed identity table

Only these four qualifications are in scope. Nothing else is ever a valid source.

| Subject | Board | Qualification | Code | Scope restriction |
|---|---|---|---|---|
| Biology | AQA | A-level | 7402 | — |
| Chemistry | AQA | A-level | 7405 | — |
| Physics | AQA | A-level | 7408 | **Astrophysics option only** |
| Mathematics | Pearson Edexcel | A-level (UK, domestic) | 9MA0 | Not International Advanced Level; not Further Mathematics |

## 2. Explicit exclusions

Named here because they are the most likely accidental substitutions when pulling revision material from general sources:

- Any Biology, Chemistry, or Physics specification from OCR, Edexcel, WJEC/Eduqas, CIE, or SQA.
- AQA Physics 7408's other four optional topics: **Medical physics, Engineering physics, Turning points in physics, Electronics** (specification sections 3.10–3.13) — verified 6 September 2026 against the live AQA specification. Only Astrophysics (section 3.9) is in scope; the compulsory core (sections 3.1–3.8) is correctly in scope for all students regardless of option.
- Pearson Edexcel **International Advanced Level** Mathematics — a related but separate Pearson qualification with its own papers and codes.
- Pearson Edexcel **Further Mathematics** — a separate qualification from Mathematics 9MA0.
- Any pre-reform "legacy" specification content (pre-2015 for the sciences, pre-2017 for maths) — these are modular predecessors and are no longer current.

## 3. Structural safeguard

Physically separating content by folder makes cross-board or cross-option material structurally harder to introduce: a Chemistry file cannot silently sit inside `Physics_AQA_7408_Astrophysics/`, and every folder name carries the spec code so the qualification is never ambiguous from the path alone.

## 4. Content header rule

From Stage 1 onward, every substantive file created in any numbered section (topic packs, flashcards, questions, worked solutions, mock papers) will open with a short header stating subject, board, spec code, and — for Physics only — the option name. This makes any individual file self-auditing without needing to check its folder location.

## 5. Source-primacy rule

- No specification statement, required practical, equation, formula-booklet entry, paper structure detail, or assessment-objective weighting is invented.
- Where you have uploaded an official document, it is the primary source and is cited by section/page reference.
- Where no upload exists yet, only information directly verified against the live official specification (aqa.org.uk or qualifications.pearson.com) is used, and it is labelled "verified online on [date], not yet cross-checked against your own copy" until you supply the document.
- Anything that cannot be verified either way is labelled **UNCONFIRMED** rather than guessed.

## 6. Pre-generation checklist

Applied before writing any new topic content in later stages:

1. Does the folder path match one of the four qualifications above?
2. For Physics: is the topic within the compulsory core (3.1–3.8) or the Astrophysics option (3.9)? If it belongs to sections 3.10–3.13, it is out of scope and is not generated.
3. For Maths: is the topic within Pure Mathematics (Papers 1–2) or Statistics and Mechanics (Paper 3) as defined in 9MA0, not Further Mathematics or an International-only topic?
4. Is the statement traceable to an uploaded specification/data-booklet, or clearly flagged as web-verified/unconfirmed?
5. Does the file carry the header required in Section 4?
