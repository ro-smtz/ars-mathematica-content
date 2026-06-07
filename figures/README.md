# figures

Standalone TikZ and PGFPlots figures published on [@ars_mathematica](https://www.instagram.com/ars_mathematica/). Each subfolder contains the `.tex` source and compiled `.pdf`.

## Structure

```text
figures/
├── YYYY-short-description/
│   ├── figure.tex
│   └── figure.pdf
└── ...
```

## Compilation

```bash
xelatex figure.tex
```

Common dependencies: `tikz`, `pgfplots`, `siunitx`, `physics`, `fontspec`.
