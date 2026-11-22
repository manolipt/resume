Resume (XeLaTeX)
  resume.tex   content only (uses the building blocks listed at its top)
  resume.sty   resume layout: header band, timeline, entry/skill rows, references
  design.sty   core design tokens (colors, fonts, type scale, icons, page defaults);
               reusable by any branded document via \usepackage{design}
  fonts/       Sofia Sans, Sofia Sans Condensed, Martian Mono, Font Awesome 7 Free (all OFL)
Build:  xelatex resume.tex && xelatex resume.tex   (second run draws the timeline)
