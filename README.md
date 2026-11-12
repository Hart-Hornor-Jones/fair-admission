# Fair to whom? — six ways to judge an admissions test

An interactive explainer of the standard definitions of a "fair" admissions test, shown on a
simulated pool of 30,000 applicants to a university like the University of California.

- **The page:** `index.html` — the narrative with all six charts embedded.
- **The charts on their own:** `charts/chart1.html` … `charts/chart6.html`, each with its own
  introduction and note.

## What the charts do

1. **An imperfect predictor** — the indicator (high school GPA and SAT combined) against the
   first-year college GPA each applicant would earn.
2. **A selection rule** — a cut score on the indicator; admitted applicants move from the pool to
   the class.
3. **Costs and benefits** — a success bar on first-year grades, and the two errors a rule makes:
   turning away students who would have succeeded, and admitting students who do not.
4. **Make it fair: equal opportunity** — adjust the rule until the same share of would-be
   successes is admitted in every group (Cole 1973; "equal opportunity").
5. **Make it fair: same promise** — adjust it until the same share of admitted students succeeds
   in every group (the standard behind Cleary 1968; "predictive parity"). The two standards
   cannot both be met by the same rule when groups differ on the indicator.
6. **Make it rational: optimal utility** — put a value on each outcome, optionally by group, and
   find the cut that makes the total highest (Gross & Su 1975; Petersen & Novick 1976).

## The simulation

The pool is simulated, not real student data. Group shares and the within-group means and
standard deviations of high school GPA and SAT come from the University of California's
Standardized Testing Task Force report (2020, fall 2018 applicants); the link from grades and
scores to first-year college GPA comes from the regression in UC's 2020 SAT/ACT study
(2015 entering cohort), with group offsets from Geiser & Studley (2001). The resulting validity
figures match UC's published ones without being fit to them. Full details are in the note at
the end of the page.

The page is a single self-contained HTML file: no build step, no data files, no dependencies
beyond three fonts from Google Fonts (with system fallbacks).

## Sources

- University of California Academic Senate, *Report of the UC Academic Council Standardized
  Testing Task Force* (2020).
- UC Institutional Research and Academic Planning, *SAT/ACT study* (2020).
- UC Office of the President, freshman-GPA regression tables, 2003–06.
- Geiser, S., & Studley, R., *UC and the SAT: Predictive validity and differential impact of
  the SAT I and SAT II at the University of California* (2001).
- Cleary, T. A. (1968); Thorndike, R. L. (1971); Cole, N. S. (1973); Darlington, R. B. (1971);
  Gross, A. L., & Su, W. (1975); Petersen, N. S., & Novick, M. R. (1976) — the fairness models.
