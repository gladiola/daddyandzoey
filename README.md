# daddyandzoey

This repository contains an AAC recording and a LilyPond-based LaTeX transcription.

## Build

Compile `transcription.tex` with **LuaLaTeX** and `--shell-escape`, not XeLaTeX or pdfLaTeX:

```bash
lualatex --shell-escape transcription.tex
```

If you use `latexmk`, this repository includes a `.latexmkrc` that selects LuaLaTeX and enables `--shell-escape` automatically:

```bash
latexmk transcription.tex
```
