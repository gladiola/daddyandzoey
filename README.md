# daddyandzoey

This repository contains an AAC recording and a LaTeX transcription.

## Build

Compile `transcription.tex` with pdfLaTeX:

```bash
pdflatex transcription.tex
```

If you use `latexmk`, this repository includes a `.latexmkrc` that selects pdfLaTeX automatically:

```bash
latexmk transcription.tex
```

The transcription presents the approximate melody as note names with aligned lyric syllables.
