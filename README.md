# Resume (XeLaTeX)

## Directory Structure

```text
  main.tex     content only (uses the building blocks listed at its top)
  resume.sty   resume layout: header band, timeline, entry/skill rows, references
  design.sty   core design tokens (colors, fonts, type scale, icons, page defaults);
               reusable by any branded document via \usepackage{design}
  fonts/       Sofia Sans, Sofia Sans Condensed, Martian Mono, Font Awesome 7 Free (all OFL)
```

## Build

```sh
xelatex main.tex && xelatex main.tex   # (second run draws the timeline)
```

