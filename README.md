# LaTeX configs
This repo consists of my very own config files used for most of my LaTeX documents.

## Usage
To use it, add it as a submodule to your repo using
```bash
git submodule add git@github.com:knedl1k/latex_configs.git configs
```
It will create a directory called `configs` with all predefined styles, macros and configs.

Usage is as simple as
```latex
\usepackage{configs/logics}
```
for example.

## Updating
```bash
git submodule update --init
```

## License
GNU General Public License v3.0

©2026 knedl1k
