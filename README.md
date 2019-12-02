# Image Glob Print

Glob all images on directories and print them to `.tex` document for printing

## Background

I have been tasked with inserting 1000+ images to word document for printing. 
Because it was a redundant and a chore I decided to install pdflatex on my PC, glob
images and print it into `.tex` document so TeX/LaTeX could print it for me.

## Installation

### Dependency

#### For producing TeX file

- Node > 8

#### For printing and processing to pdf file

- Node > 8
- TeX 3.14159265 (TeX Live 2019/Debian)
- pdfTeX 3.14159265-2.6-1.40.20 (TeX Live 2019/Debian)

### Instruction

1. [Download](https://nodejs.org/en/download/) node.js to your PC

2. Clone this repository

```bash
git clone https://github.com/rayGobel/image-glob-print
```

3. Run npm install

```bash
npm install
```

4. Run program with

```bash
npm start -- --image-dir=directory/of/your/image --output-file=output.tex
```

## Caveats

* How the image structured in a directory affect how image will be printed
