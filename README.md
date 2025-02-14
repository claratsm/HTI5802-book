# Welcome! 

Welcome to the book for practical sections of [HTI5802: Algorithms in Bioinformatics and Genomics](). Most contents are demonstrated with PLINK and R programming language.

This book is designed as a collection of R Markdown notebooks, as supplementary to the lecture notes for GWAS and sequence interpretation of HTI5802 at PolyU.

1. [Genomewide association analysis (GWAS)](https://github.com/claratsm/HTI5802-book/blob/main/GWAS.md) (2025-02-17)
2. [Variant interpretation for clinical sequencing]() (2025-03-10)

Note: Most contents may be updated before or right after the lectures, so please refer to the updated version.

## Source files and re-build:

you can find the source files on GitHub
[claratsm/HTI5802-book](https://github.com/claratsm/HTI5802-book).

To build this book from the source files, use the following script in R:
```
bookdown::render_book("index.Rmd", "bookdown::gitbook")
```

To release the build, you can simply push the `docs` folder to this github 
repository. Note, the website only shows the `docs` folder while other files are
source codes for generating the `docs` folder.