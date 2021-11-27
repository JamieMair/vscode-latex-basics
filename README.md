# VSCode LaTeX grammars

The files contained in this repository were originally part of https://github.com/James-Yu/LaTeX-Workshop. They have been extracted in the hope that they can useful out of the LaTeX-Workshop extension.

This repository contains `tmLangugage` grammar files for LaTeX and some related programming languages (`TeX`, `DocTeX`, `BibTeX`, `BibTeX Style`, `LaTeX3`). These grammar files specifically target [Visual Studio Code](https://github.com/Microsoft/vscode) as they are accompanied by the corresponding language configuration files. However the grammar files could in principle be consumed by any editor or extension using the TextMate language.

The grammar files support various embedded languages

- `asymptote`
- `c/c++`
- `css`
- `dot`
- `gnuplot`
- `html`
- `java`
- `javascript`
- `julia`
- `lua`
- `python`
- `ruby`
- `scala`
- `typescript`
- `xml`
- `yaml`
- Combined LaTeX and markdown to be used with the `markdown` package

## License

If not otherwise specified (see below), files in this repository fall under the license stated in [LICENSE.txt](LICENSE.txt)


### LaTeX grammar

The LaTeX grammar [syntaxes/LaTeX.tmLanguage.json](syntaxes/LaTeX.tmLanguage.json) is based on https://github.com/textmate/latex.tmbundle/blob/master/Syntaxes/LaTeX.plist but has been largely modified. The original file falls under the following license

    Permission to copy, use, modify, sell and distribute this
    software is granted. This software is provided "as is" without
    express or implied warranty, and with no claim as to its
    suitability for any purpose.

### Combined LaTeX/Markdown grammar

The combined Markdown/LaTeX grammar [syntaxes/markdown-latex-combined.tmLanguage.json](syntaxes/markdown-latex-combined.tmLanguage.json) is generated from the Markdown grammar included in VSCode and falls under the following license described in [markdown-latex-combined-license.txt](markdown-latex-combined-license.txt).

### C++ bailed out grammar

The file [syntaxes/cpp-grammar-bailout.tmLanguage.json](syntaxes/cpp-grammar-bailout.tmLanguage.json) is generated from https://github.com/jeff-hykin/better-cpp-syntax and falls under the following license described in [cpp-bailout-license.txt](cpp-bailout-license.txt).
