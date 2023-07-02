# Latex-Codes
Latex(Beginner)

# Font #

`mathptmx` This package defines Adobe Times Roman (or equivalent) as default text font, and provides maths support using glyphs from the Symbol, Chancery and Computer Modern fonts together with letters, etc., from Times Roman([CTAN](https://ctan.org/pkg/mathptmx?lang=en)).

`mathpazo` The Pazo Math fonts are a family of PostScript fonts suitable for typesetting mathematics in combination with the Palatino family of text fonts.([CTAN](https://ctan.org/pkg/mathpazo?lang=en)).

# Bibliography Style #

## APA Style
```Latex
\usepackage[style=apa, backend=biber, natbib=true]{biblatex}
\addbibresource{bib file name}

[contents]

\printbibliography
```

# Tables #

## Game Tables

<div id="Game_Tables">
  <a href="./Codes/2by2_Game_Table.tex">
    <img src="./Figures_(Models)/Ramsey_Model.png" title="Ramsey Model" alt="Ramsey Model" width="327.19" height="267.5"/>&nbsp;&nbsp;&nbsp;&nbsp;
  </a>
  <a href="./Codes/3by4_Game_Table.tex">
    <img src="./Figures_(Models)/Ramsey_Model_with_Government.png" title="Ramsey Model with Government" alt="Ramsey Model with Government" width="308.61" height="269.17"/>
  </a>
</div>


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
