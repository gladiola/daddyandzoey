# daddyandzoey

This repository contains an AAC recording and a LaTeX transcription.

## Build

Compile `transcription.tex` with pdfLaTeX:

```bash
pdflatex transcription.tex
```

If you use `latexmk`, run it in PDF mode:

```bash
latexmk -pdf transcription.tex
```

The repository also includes a `.latexmkrc` with `$pdf_mode = 1`.
