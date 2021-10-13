This is a modified [beamerposter](https://ctan.org/pkg/beamerposter?lang=en) template with the University of Queensland logo and colors. It is forked from https://rev.cs.uchicago.edu/k4rtik/gemini-uccs (which is forked from https://github.com/anishathalye/gemini). 

## Screenshot

![Screen](screenshot.png)

## UQ RGB

UQ RGB is in file `beamercolorthemeuchicago.sty` can be re-adjusted. The current RGB code is:

```
\definecolor{UQmain}{rgb}{0.3178,0.141,0.478}
```

## Compiling

### Using it From Overleaf

You can easly use the template via [Overleaf Gallery](https://www.overleaf.com/latex/templates/uq-beamerposter-template/svbpbndqdpqv). Click "Open as Template" after going to the gallery page. 

### Offline Use

It is a gemini template. More information about dependencies are available here: [Gemini Readme File](https://github.com/alfurka/gemini-uq/blob/master/gemini-readme.md).

1. Copy the files in this repository (or clone the repository)
2. In `main.tex`, set up your paper size, column layout, and scale the content if required.
3. Run `makefile` to build your poster
