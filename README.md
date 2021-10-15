# COM 457 Fall 2021

This repository contains the source files for my assignments in [COM 457 Ways of Knowing: Philosophy and Literature](https://registrar.princeton.edu/course-offerings/course-details?term=1222&courseid=016122). Each assignment is a LaTeX document that uses a shared preamble and is ultimately compiled with XeTeX. BibLaTeX (Biber backend) is used to handle bibliographic sources, with additional configuration to handle MLA citations.

## Usage

Each assignment is located in a child folder of `assignments/`. I use [LaTeX Workshop](https://github.com/James-Yu/LaTeX-Workshop) along with a custom recipe for compiliation, but any tool that can handle XeTeX and Biber should work (e.g. `latexmk`).

When a document needs to adhere more closely to MLA formatting (1 inch margins on all sides, double spacing), set the toggle `draft` in `preamble.tex` to true:

```tex
\toggletrue{draft}
```

## License

The LaTeX code used is MIT licensed. Please see the file [`LICENSE.txt`](LICENSE.txt) in the main directory of the repository for more details.

The actual text for each document is licensed under a [Creative Commons Attribution 4.0 International License](https://creativecommons.org/licenses/by/4.0/).
