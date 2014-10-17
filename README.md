texsnip
=======

TeX-related snippets.

Usage:

```latex
\documentclass{article}
\usepackage{cmvec}
\CMIndexedSymbol{MS}{X}
\begin{document}
$\MS \: \MS[0] \: \MS[0][3] \: \MS[][3] \: \MS[0][] \: \MS(<) \: \MS(>)[0] \: \MS(<>)[0][3]$
\end{document}
```

Make sure your LaTeX installation is up-to-date. You will need `mathtools` and `etoolbox`.
