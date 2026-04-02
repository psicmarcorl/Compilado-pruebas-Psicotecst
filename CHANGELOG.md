# Changelog

## 2026-04-01
1. Added the Ellis Irrational Beliefs Test with agree/disagree responses, per-belief scoring, and XLSX export (including belief-level interpretation).
2. Extended the main menu and navigation to include the Ellis test.
3. Redesigned the main menu with a more visual layout and an embedded psyche-themed background illustration.

## 2026-03-31
1. Created `bai_form.html` with the Beck Anxiety Inventory (BAI), automatic scoring, interpretation, and XLSX download with no external dependencies.
2. Extracted and incorporated BAI items and response options from the provided PDF.
3. Built `index.html` with a main menu to select tests (BAI and BDI-II) and internal navigation.
4. Integrated the Beck Depression Inventory (BDI-II) with 21 groups, automatic scoring, and cutoffs: 0–13 minimal, 14–19 mild, 20–28 moderate, 29–63 severe.
5. Implemented automatic XLSX generation for each test including test name, date, respondent, total score, interpretation, and item responses.
6. Fixed independent validation so each test can be completed without requiring responses from the other (radio `name` alignment).
