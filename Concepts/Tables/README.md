# Tables in LaTeX

Inserting tables in LaTeX documents

## Table of contents

- [Tables in LaTeX](#tables-in-latex)
    - [Table of contents](#table-of-contents)
    - [Contents](#contents)
    - [Notes](#notes)
    - [References](#references)

## Contents

The contents of this folder are described below

| S. No. | Item(s) | Description |
| :--- | :----- | :---- |
| 1 | [main.tex](./main.tex) and [preamble.tex](./preamble.tex) | Core files |
| 2 | [main.pdf](./main.pdf) | Resulting file |
| 3 | [captioned_tables.tex](./captioned_tables.tex) | Captioning and slash-box |

## Notes

Caption a table using (refer [this](https://www.overleaf.com/learn/latex/Questions/How_do_I_add_a_caption_to_a_table%3F) or [this](https://en.wikibooks.org/wiki/LaTeX/Floats,_Figures_and_Captions#Figures))

```tex
\begin{table}
\begin{tabular}
...
\end{tabular}
\caption{\label{tab:table-name}Your caption.}
\end{table}
```

## References

- Slashbox on [StackExchange](https://tex.stackexchange.com/a/27195/253896)
