# Learning LaTeX

LaTeX is a powerful tool for writing. You only focus on content, and let LaTeX take care of the appearance. This repository serves as a reference for all LaTeX related things.

## Table of contents

- [Learning LaTeX](#learning-latex)
    - [Table of contents](#table-of-contents)
    - [Installation and Setup](#installation-and-setup)
        - [Windows](#windows)
    - [Contents](#contents)
    - [References](#references)

## Installation and Setup

All things LaTeX can be done through an online editor like [overleaf](https://www.overleaf.com/). However, this repository focuses on a local setup. The primary editor used is [VSCode](https://code.visualstudio.com/) and the extension [James-Yu.latex-workshop](https://marketplace.visualstudio.com/items?itemName=James-Yu.latex-workshop) is very helpful.

### Windows

On a windows system, do the following steps

1. Install `MikTeX` to handle everything `TeX`
    1. Install [miktex](https://miktex.org/) for Windows.
    2. Choose to install missing packages on the fly (preferably install with prompt).
    3. Open `MikTeX Console` and click `Check for Updates`. Then go to `Updates` -> `Update now` which will install updates.
    4. Go to `Packages` and install `latexmk` (which allows making LaTeX files), `chktex` (for semantic checking).
    5. Add the path of `MikTeX Console` (usually is `%USERPROFILE%\AppData\Local\Programs\MiKTeX\miktex\bin\x64`) to the `Path` user variable (under `Environment Variables`). This is to find all the executables from command line.
2. Install [Strawberry Perl](https://strawberryperl.com/) for Windows and add path to the `Path` variable (under `System Variables`). Add the path for Perl and C binaries, usually is `C:\Strawberry\c\bin`, `C:\Strawberry\perl\site\bin` and `C:\Strawberry\perl\bin`. This is for Perl dependency which MikTeX doesn't package.
3. Install the [James-Yu.latex-workshop](https://marketplace.visualstudio.com/items?itemName=James-Yu.latex-workshop) extension on VSCode.

## Contents

The contents of this repository are divided into folders listed below

| S. No. | Folder | Description |
| :--- | :--- | :--- |
| 1 | [Hello World](Hello%20World/README.md) | First steps in LaTeX. Contains a simple TeX file. |
| 2 | [Concepts](./Concepts/README.md) | Concepts in LaTeX. Contains folders for individual concepts. |
| 3 | [Templates](./Templates/README.md) | Simple reusable templates to prevent reinventing the wheel every time. |

## References

- [CTAN: Comprehensive TeX Archive Network](https://www.ctan.org/)
- [Learn on Overleaf](https://www.overleaf.com/learn)
- Equations using [codecogs](https://www.codecogs.com/latex/eqneditor.php)
- Lorem Ipsum from [here](https://www.lipsum.com/)
