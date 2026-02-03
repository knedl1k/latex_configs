# LaTeX configs
This repo consists of my very own config files used for most of my LaTeX documents.

## Usage
To use it, add it as a submodule to your repo using
```bash
git submodule add git@github.com:knedl1k/latex_configs.git configs
```
It will create a directory called `configs` with all predefined styles, macros and configs.

Usage is as simple as putting this
```latex
\makeatletter
\def\input@path{{../configs/}{./}} 
\makeatother

\usepackage{math}
```
into your main file, for example.

## Updating
To update configs with to the latest version, use
```bash
git submodule update --remote
```

## License
GNU General Public License v3.0

©2026 knedl1k
