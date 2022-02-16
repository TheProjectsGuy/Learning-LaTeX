# Simple Math Equations in LaTeX

Basic LaTeX equations

## Table of contents

- [Simple Math Equations in LaTeX](#simple-math-equations-in-latex)
    - [Table of contents](#table-of-contents)
    - [Contents](#contents)
    - [Snippets](#snippets)
    - [References](#references)

## Contents

The contents of this folder are described below

| S. No. | Item Name | Description |
| :--- | :---- | :------ |
| 1 | [main.pdf](./main.pdf) | Resulting PDF |
| 2 | [main.tex](./main.tex), [preamble.tex](./preamble.tex) | Main files |
| 3 | [aligned_equs.tex](./aligned_equs.tex) | Aligned equations |

## Snippets

Number equations withing sections

```tex
\numberwithin{equation}{section}
```

Align long equations using

```tex
\begin{align}
    \begin{split}
    ...
    \end{split}
    \begin{split}
    ...
    \end{split}
    ...
\end{align}
```

## References
