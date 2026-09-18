# My One-Page CV

<p align="center">
  <a href="main.pdf">
    <img src="main-1.png" alt="CV preview" width="800">
  </a>
</p>

This repository contains my own take of a one-page CV based on the [**hipster-cv**](https://github.com/latex-ninja/hipster-cv/).

## Usage
To create your own one-page CV simply clone the repository and run the `main.tex` file with a LaTeX engine. The simplest way to get to this result is to use [**Overleaf**](https://overleaf.com).

In overleaf create a new project and upload the `main.tex` file, and the two folders `images` and `simplehipstercv`. Personalize the `main.tex` and add your own logos and pictures needed. Compile it and the job is done.

### For the expert
Other files, and especially the `.latexmkrc` are needed when compiling the project via other methods, for example using VS Code and the [**latex-workshop**](https://github.com/James-Yu/LaTeX-Workshop) extension. To work in this setting simply clone the repository and open the folder with VS Code. Follow the instructions of latex-workshop for details on how to run the project. This method is recommended only for expert users, using Overleaf should be the first choice. 

### Preview for this `README.md`
The preview image for this `README.md` file is generated with:
```bash
pdftoppm -png -r 300 main.pdf main
```

## Files
Here is a file-tree of the files in this project. The essential files and folders that need to be used in Overleaf are in <u><strong>highlighted</strong></u>.
<pre>
├── LICENSE.md
├── README.md
├── <u><strong>images/</strong></u>           - logos and pictures
├── main-1.png        - preview image
├── <u><strong>main.tex</strong></u>          - tex source file
├── myBIB.bib         - bib file for highlights papers
└── <u><strong>simplehipstercv/</strong></u>  - class and style files
</pre>