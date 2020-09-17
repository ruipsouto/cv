# A CV Template

A simple single-page, one-column CV template written in LaTeX. Feel free to modify the .tex file and create your own CV.

## How to Use

At a command prompt, run

```sh
docker build -t latex .
docker run --rm -i -v "$PWD":/source latex pdflatex template.tex
```

A template.pdf file should be created.

## Preview

In [pdf](template.pdf) format.

![CV Preview](/preview.png)
