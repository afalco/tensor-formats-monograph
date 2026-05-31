# Tensor Formats in Banach Spaces
## Minimal Subspaces, Geometry, and Variational Principles

**Author:** Antonio Falcó  
**Institution:** ESI International Chair@CEU-UCH, Universidad Cardenal Herrera-CEU, CEU Universities  
**Series:** Ergebnisse der Mathematik und ihrer Grenzgebiete (3. Folge), Springer  

---

## Description

This monograph presents a unified and self-contained treatment of the mathematical
foundations of low-rank tensor formats in Banach spaces. It synthesises and extends
the results of the following four research papers:

| Paper | Reference |
|-------|-----------|
| On Minimal Subspaces in Tensor Representations | Falcó & Hackbusch, *Found. Comput. Math.* **12** (2012) 765–803 |
| Tree-based Tensor Formats | Falcó, Hackbusch & Nouy, *SeMA J.* **78** (2021) 159–173 |
| On the Dirac–Frenkel Variational Principle on Tensor Banach Spaces | Falcó, Hackbusch & Nouy, *Found. Comput. Math.* **19** (2019) 159–204 |
| Geometry of Tree-based Tensor Formats in Tensor Banach Spaces | Falcó, Hackbusch & Nouy, *Ann. Mat. Pura Appl.* (2023) |

---

## Structure

```
monograph/
├── main.tex                  % Master file (compiles the whole book)
├── notation.tex              % Unified notation and macros (input into main.tex)
├── chapters/
│   ├── ch00_preface.tex
│   ├── ch01_introduction.tex
│   ├── ch02_banach.tex
│   ├── ch03_algtensor.tex
│   ├── ch04_minsubspaces.tex
│   ├── ch05_trees.tex
│   ├── ch06_algTBT.tex
│   ├── ch07_topTBT.tex
│   ├── ch08_tucker_manifold.tex
│   ├── ch09_TB_manifold.tex
│   ├── ch10_DF.tex
│   ├── ch11_open.tex
│   ├── app_manifolds.tex
│   ├── app_functional.tex
│   └── app_notation_index.tex
├── bibliography/
│   └── monograph.bib         % BibTeX database
├── figures/                  % PDF/TikZ figures
└── styles/                   % Any custom style files
```

---

## Compilation

```bash
pdflatex main.tex
bibtex main
pdflatex main.tex
pdflatex main.tex
```

Or with `latexmk`:

```bash
latexmk -pdf main.tex
```

---

## MSC Classification

15A69 · 46B28 · 46A32

## Keywords

Tensor spaces · Banach manifolds · Tensor formats · Tree-based tensors ·
Minimal subspaces · Dirac–Frenkel variational principle · Tucker format ·
Tensor train · Hierarchical Tucker
