# LaTex Template

LaTeX Template for MSc and PhD thesis. Based on the 2017-18 guidelines for MSc thesis at the University of Southampton.
Requires BibLaTex to compile the bibliography.


## Getting Started 

Once the repository has been clone or downloaded from github
```
git clone https://github.com/marinlauber/LaTex_Template.git
```
You can build the project, and the `main.pdf` file using
```
make
```

This calls `pdflatex`, `biber` and `pdflatex` in this order and uses the chapter/files stored in `src/`. 

All library/module import are kept in `module.tex` to keep the `main.tex` file cleaner. The role of this main file is to gather all the different parts of the report together.

Once the project has been made, you can clean all the files that are generated by `pdflatex` using

```
make clean
```

or 

```
make cleaner
```

to completely clean the project.

Author: Marin Lauber
