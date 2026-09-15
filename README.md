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

The transcription presents the approximate melody in a simple sheet-music layout with a bass clef, aligned lyric syllables, and reusable TikZ notation macros for notes, rests, staff rendering, and automatic line breaks.

The build is fully local and deterministic: it does not require LilyPond, external notation fonts, PDF-to-image conversion, or any download step.
