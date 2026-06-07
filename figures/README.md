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

Figures are written for XeLaTeX, which is required to load the [New Computer Modern](https://ctan.org/pkg/newcomputermodern?lang=en) font via `fontspec` and `fontsetup`:

```bash
xelatex figure.tex
```

They can also be compiled with pdfLaTeX without any other changes — just comment out the two font packages at the top of the file:

```tex
% \usepackage{fontspec}
% \usepackage[default]{fontsetup}
```

Common dependencies: `tikz`, `pgfplots`, `siunitx`, `physics`.
