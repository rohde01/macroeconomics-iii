# Macroeconomics III

University of Copenhagen · MSc Economics · Spring 2026 · 7.5 ECTS  
<!-- TODO: Course code and link to kurser.ku.dk -->

Graduate macroeconomics, covering consumption and savings decisions, business cycles and growth. The two assignments solve an optimal consumption problem and document business cycle facts for the US and Portugal.

## Contents

| Folder | Contents |
| --- | --- |
| `assignments/assignment-<n>/` | Assignments 1 and 2 with `AssignmentN.tex` and PDF, the notebook, its data and figures |
| `notes/` | `weekly-notes.tex` and PDF, my weekly notes |
| `materials/` | Course-provided material. Slides, problem sets, assignment briefs, syllabus and exam solutions. |

## Tools

Python, uv, LaTeX

## Build

Each LaTeX source sits next to its PDF. Rebuild a PDF from its folder with:

```bash
tectonic -Z continue-on-errors Assignment1.tex
```

The notebooks read their data from and save their figures to their own folder. The `.csv` files are downloads from EU KLEMS, FRED and Eurostat.
