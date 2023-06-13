# Latex-Codes
Latex(Beginner)

# Font #

`mathptmx` times new roman \\
`mathpazo` The Pazo Math fonts are a family of PostScript fonts suitable for typesetting mathematics in combination with the Palatino family of text fonts.([CTAN](https://ctan.org/pkg/mathpazo?lang=en))

# Bibliography Style #

## APA Style
```Latex
\usepackage[style=apa, backend=biber, natbib=true]{biblatex}
\addbibresource{bib file name}

[contents]

\printbibliography
```

# Tables #

## 3 by 4 simultaneous game

Code: [Link](./Simultaneous_Game_Tables.tex)

Figure: [Link](./3by4gametable.png)


# Hyperlink #

Using the `hyperref` package and its setup `hypersetup`, we can build hyper links.

```Latex
\usepackage{hyperref}
\hypersetup{
	colorlinks=true,
	linkcolor=black,
	filecolor=blue,      
	urlcolor=blue,
	citecolor=blue
}
```
