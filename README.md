# daddyandzoey

This repository contains an AAC recording and a LilyPond-based LaTeX transcription.

## Build

Compile `transcription.tex` with LuaLaTeX and `--shell-escape`:

```bash
lualatex --shell-escape transcription.tex
```

If you use `latexmk`, this repository includes a `.latexmkrc` that selects LuaLaTeX and enables `--shell-escape` automatically:

```bash
latexmk transcription.tex
```

The score is engraved with LilyPond and includes lyrics under the staff.
