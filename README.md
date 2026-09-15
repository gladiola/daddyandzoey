# daddyandzoey

This repository contains an AAC recording and a LilyPond-based LaTeX transcription.

## Build

Compile `transcription.tex` with **LuaLaTeX**, not XeLaTeX or pdfLaTeX:

```bash
lualatex transcription.tex
```

If you use `latexmk`, this repository includes a `.latexmkrc` that selects LuaLaTeX automatically:

```bash
latexmk transcription.tex
```
