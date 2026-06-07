# Ars Mathematica — Content

> *Non docentibus, sed discentibus.*  
> *Non eruditis, sed erudiendis.*

This repository is the content library behind the [Ars Mathematica](https://ro-smtz.github.io/ars-mathematica/) project — a collection of TikZ and PGFPlots source files, LaTeX templates, figure code, and reading resources produced since 2019.

Everything here is meant to be downloaded, compiled, studied, and modified. We all learn by imitation.

---

## Structure

```text
figures/          # Standalone TikZ and PGFPlots figures (with compiled PDF)
tutorials/        # Source files accompanying website tutorials
templates/        # Complete LaTeX templates (article, beamer, poster)
reading/          # Book recommendations and curated reading lists
```

Each subfolder contains a `README.md` describing its contents and compilation instructions where relevant.

---

## Compilation

Figures are written for XeLaTeX. To compile a standalone figure:

```bash
xelatex figure.tex
```

Dependencies vary by file but commonly include: `tikz`, `pgfplots`, `siunitx`, `physics`, `fontspec`.

---

## Related

- **Website** → [ro-smtz.github.io/ars-mathematica](https://ro-smtz.github.io/ars-mathematica/) — courses, tutorials, and figure gallery
- **Instagram** → [@ars_mathematica](https://www.instagram.com/ars_mathematica/) — 70K+ followers
- **Author** → [Rodrigo Sánchez-Martínez](https://orcid.org/0000-0002-5713-3053)
- **Contact** → rodrigo.smtz@icloud.com
