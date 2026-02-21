# CISC-727: Advanced Research Explorations (ARE) - I

## Assignment A02 - Literature Review

**Course:** CISC-727 - Advanced Research Explorations (ARE) - I
**Author:** Kenneth Peter Fernandes
**Institution:** Harrisburg University of Science and Technology
**Semester:** Spring 2026
**Instructor:** Professor Majid Shaalan, PhD

## Repository Structure

```
are-1/
├── a02/
│   └── cisc_727_are_I_a02_kenneth_peter_fernandes_literature_review_v1.tex
└── references/
    └── references.bib
```

## Build Instructions

From the `are-1/a02/` directory, run:

```bash
pdflatex cisc_727_are_I_a02_kenneth_peter_fernandes_literature_review_v1.tex && biber cisc_727_are_I_a02_kenneth_peter_fernandes_literature_review_v1 && pdflatex cisc_727_are_I_a02_kenneth_peter_fernandes_literature_review_v1.tex && pdflatex cisc_727_are_I_a02_kenneth_peter_fernandes_literature_review_v1.tex
```

## Requirements

- TeX Live (or equivalent LaTeX distribution)
- `biber` (for APA-style bibliography processing)
- Required LaTeX packages: `biblatex`, `longtable`, `booktabs`, `hyperref`, `geometry`, `setspace`
