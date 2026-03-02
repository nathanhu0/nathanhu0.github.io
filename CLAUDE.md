# Build Commands

## Compile CV to PDF

```bash
cd cv_tex && pdflatex main.tex && biber main && pdflatex main.tex && pdflatex main.tex && mv main.pdf ../files/cv.pdf
```
