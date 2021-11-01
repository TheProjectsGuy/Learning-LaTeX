# Modular LaTeX: Subfiles

Using `subfiles` package to break up a large LaTeX project into smaller sub-files. This method is common when the structure is like an inverted tree, with a single file containing multiple sub-files.

It is possible to include a file multiple times too. Make sure that the magic comment for `root` points to the common ancestors. An example is

```tex
% !TeX root = main.tex
```

## Table of contents

- [Modular LaTeX: Subfiles](#modular-latex-subfiles)
    - [Table of contents](#table-of-contents)
    - [Contents](#contents)

## Contents

The contents of this folder are described in the table below

| File Name | Description |
| :--- | :--- |
| [preamble.tex](./preamble.tex) | Contains the preamble (all important document tags). It is good to keep all preamble packages, configurations, etc. at one place. The `geometry` properties is a good example. |
| [main.tex](./main.tex) | Contains the title, author and the main document. It also has most of the commands for including other files. |
| [abstract.tex](./abstract.tex) | Document abstract |
| [s1.tex](./s1.tex), [s1-1.tex](./s1-1.tex) | Section 1 and sub-section 1.1 files (respectively). These files are inherited as `s1.1` in `s1` in `main`. |
| [s2.tex](./s2.tex) | Section 2 for the document. |
| [ipsum.tex](./ipsum.tex) | A file containing sample Lorem Ipsum text. This file is included in `s2` and `appendix` (shared with both). |
| [appendix.tex](./appendix.tex) | Appendix section of document (along with `ipsum` included). |

The resultant file for the above files is shown in [main.pdf](./main.pdf) file.
