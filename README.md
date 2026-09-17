# My One-Page CV

<p align="center">
  <a href="main.pdf">
    <img src="main-1.png" alt="CV preview" width="800">
  </a>
</p>

This repository contains my own take of a one-page CV based on the [hipster-cv](https://github.com/latex-ninja/hipster-cv/).

## Files
```text
├── LICENSE.md 
├── README.md
├── images/           - logos and pictures
├── main-1.png        - preview image
├── main.pdf          - compiled pdf file
├── main.synctex.gz
├── main.tex          - tex source file
├── myBIB.bib         - bib file for highlights papers
└── simplehipstercv/  - class and style files
```

## Build
To compile the PDF:

```bash
pdflatex main.tex
```


pdftoppm -png -r 300 main.pdf main