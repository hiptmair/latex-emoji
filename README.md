# The `emoji` package

Emoji support in (Lua)LaTeX.

## Introduction

The `emoji` package allows user to typeset emoji in a LaTeX document. It requires LuaHBTeX, or `lualatex-dev` at present.

## Usage

```tex
\documentclass{article}
\usepackage{emoji}
\setemojifont{Apple Color Emoji}  % Optional

\begin{document}
\emoji{joy}
\emoji{+1}
\emoji{family-man-woman-girl-boy}
\end{document}
```

Result:

> :joy:
> :+1:
> :family_man_woman_girl_boy:

## License

This work may be distributed and/or modified under the conditions of the [LaTeX Project Public License](http://www.latex-project.org/lppl.txt), either version 1.3c of this license or (at your option) any later version.

-----

Copyright (C) 2020 by Xiangdong Zeng.
