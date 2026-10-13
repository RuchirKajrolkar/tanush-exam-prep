# VCE Mathematical Methods Units 3 & 4: exam content sheet

**[Methods_Units_3_4_Content_Sheet.pdf](Methods_Units_3_4_Content_Sheet.pdf)** is a content sheet for the end-of-year Methods exams. It is written against the VCAA *VCE Mathematics Study Design 2023–2027* (Units 3 and 4: Mathematical Methods, version 1.1) and covers every dot point.

## What's in it

1. The exams: Exam 1 vs Exam 2 format, the formula sheet (what's on it, what to memorise), notation, command terms
2. Assumed knowledge from Units 1 & 2: algebra, exact values and the unit circle, probability rules
3. Functions, relations and graphs (AOS 1): polynomials, power, exponential, log and circular functions, transformations, families, combinations, hybrid functions, modelling
4. Algebra, number and structure (AOS 2): polynomial equations, inverse and composite functions, equation solving (including circular equations by hand), literal and parametric equations, simultaneous equations
5. Calculus I (AOS 3): continuity and differentiability, derivative rules, tangents, graphs of f′, stationary points, optimisation, Newton's method
6. Calculus II (AOS 3): anti-derivatives, recognition, the FTC, the trapezium rule, areas, average value
7. Random variables (AOS 4): discrete distributions, binomial, pdfs, the normal distribution
8. Statistical inference (AOS 4): sample proportions, simulation, confidence intervals
9. Outcomes 2 & 3: computational thinking, pseudocode, standard algorithms, CAS syntax
10. Exam technique and common errors
11. A tick-box checklist mapping every study design dot point to its page

Each section starts with the study design dot points it covers. Every worked example was checked with a computer algebra system.

## Rebuilding the PDF

The LaTeX source is in [`methods-content-sheet/`](methods-content-sheet/). With TeX Live installed (needs `pgfplots`, `tcolorbox`, `newpx`, `sourcesanspro`, `fontawesome5`):

```sh
cd methods-content-sheet
latexmk -pdf -outdir=build main.tex
cp build/main.pdf ../Methods_Units_3_4_Content_Sheet.pdf
```
