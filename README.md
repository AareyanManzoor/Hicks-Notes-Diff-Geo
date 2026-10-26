# Hicks-Notes-Diff-Geo
This is the TeX for Hicks ``notes on differential geometry'', TeX'd by the TeXromancers.

The sources originated in our Overleaf project. Corrections checked against the original scan in October 2026 restore transcription omissions, mathematical formulas, references, bibliography entries, and diagram constructions. Corrections of errors inherited from the original are identified by editor's notes in the text.

Feel free to download and change for example font to better fit your preferences. Your can report errors to my email at amanzoo1 at asu dot edu, or at my discord JohnDS#1149, or as changes to this github with documentation of what was changed.

Link to the book: https://aareyanmanzoor.github.io/assets/hicks.pdf

Link to dyslexic friendly version: https://aareyanmanzoor.github.io/assets/hicks-dyslexic.pdf

## Building

Use a TeX distribution with pdfLaTeX, MakeIndex, `latexmk`, and a working Biber compatible with its installed `biblatex`. From this directory run:

```sh
latexmk -pdf -outdir=build main.tex
```

`latexmk` must be able to invoke Biber and MakeIndex and rerun pdfLaTeX to resolve the bibliography, index, and cross-references. The finished file is `build/main.pdf`; generated files in `build/` are not source files.
