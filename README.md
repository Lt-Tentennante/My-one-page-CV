# My One-Page CV

<p align="center">
  <a href="main.pdf">
    <img src="main-1.png" alt="CV preview" width="800">
  </a>
</p>

This repository contains my own take of a one-page CV based on the [hipster-cv](https://github.com/latex-ninja/hipster-cv/).

## Files
- `main.tex` — source file
- `main.pdf` — compiled PDF
- `main-1.png` — preview image for GitHub

## Build
To compile the PDF:

```bash
pdflatex main.tex



pdftoppm -png -r 300 main.pdf main