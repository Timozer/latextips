# Lengths in LaTeX

## Units

Abbreviation | Value
:-------------:|------------------
pt | a point is approximately 1/72.27 inch, that means about 0.0138 inch or 0.3515 mm (exactly point is defined as 1/864 of American printer’s foot that is 249/250 of English foot)
mm | a millimeter
cm | a centimeter
in | inch
ex | roughly the height of an 'x' (lowercase) in the current font (it depends on the font used)
em | roughly the width of an 'M' (uppercase) in the current font (it depends on the font used)
mu | math unit equal to 1/18 em, where em is taken from the math symbols family

## Lengths

Length | Description
:------|--------------------
\baselineskip | Vertical distance between lines in a paragraph
\columnsep | Distance between columns
\columnwidth | The width of a column
\evensidemargin | Margin of even pages, commonly used in two-sided documents such as books
\linewidth | Width of the line in the current environment.
\oddsidemargin | Margin of odd pages, commonly used in two-sided documents such as books
\paperwidth | Width of the page
\paperheight | Height of the page
\parindent | Paragraph indentation
\parskip | Vertical space between paragraphs
\tabcolsep | Separation between columns in a table (tabular environment)
\textheight | Height of the text area in the page
\textwidth | Width of the text area in the page
\topmargin | Length of the top margin

# Spacing in math mode

LATEX code | Description
-----------|------------------
\quad | space equal to the current font size (= 18 mu)
\, | 3/18 of \quad (= 3 mu)
\: | 4/18 of \quad (= 4 mu)
\; | 5/18 of \quad (= 5 mu)
\! | -3/18 of \quad (= -3 mu)
\ (space after backslash!) | equivalent of space in normal text
\qquad | twice of \quad (= 36 mu)

# math formular

```tex
\begin{equation}
    \label{eq:lab}
    f(x) = \left\{ 
        \begin{array}{ccl}
        x + 1 & & \text{if}\ x > 0 \\
        x - 1 & & \text{otherwise}
        \end{array}
    \right.
\end{equation}
```

![](http://latex.codecogs.com/gif.latex?f_x%20=%20\left\{%20\begin{array}{ccl}%20x%20+%201%20&%20&%20\text{if}\%20x%20%3E%200%20\\%20x%20-%201%20&%20&%20\text{otherwise}%20\end{array}%20\right.)
<!--![](http://latex.codecogs.com/gif.latex?f_x=\left\{\begin{array}{ccl}x+1& &\text{if}\ x>0\\x-1& &\text{otherwise}\end{array} \right.)-->
