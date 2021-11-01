# Modularity in LaTeX

LaTeX projects become BIG fast, it's best to keep things modular. For a big document, it is better if the source is divided into small manageable files.

## Table of contents

- [Modularity in LaTeX](#modularity-in-latex)
    - [Table of contents](#table-of-contents)
    - [Contents](#contents)
    - [Comments](#comments)
    - [Reference](#reference)

## Contents

Various methods of accomplishing this is explored in the folders. They're described in the table below

| S. No. | Method | Description |
| :---- | :---- | :---- |
| 1 | [Subfiles](./Subfiles/README.md) | Using `subfiles` package |

## Comments

When using modules, it is possible to prevent compilation of individual `.tex` files by specifying the master document in a TeX [magic comment](https://www.texdev.net/2011/03/24/texworks-magic-comments/)

```tex
% !TeX root = main.tex
```

## Reference

- [Overleaf: Multi-file LaTeX projects](https://www.overleaf.com/learn/latex/Multi-file_LaTeX_projects)
