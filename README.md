# Jupyter nbconvert 中文 PDF 模板

Chinese LaTeX/PDF template for Jupyter notebook `nbconvert` using CTeX.

[![PyPI - Version](https://img.shields.io/pypi/v/nb-tmpl-ctex.svg)](https://pypi.org/project/nb-tmpl-ctex)
[![PyPI - Python Version](https://img.shields.io/pypi/pyversions/nb-tmpl-ctex.svg)](https://pypi.org/project/nb-tmpl-ctex)

-----

## Installation

```console
pip install nb-tmpl-ctex
```

## Usage

```bash
# 默认 ctexart
jupyter nbconvert example.ipynb --to pdf --template ctex
# 使用 ctexrep
jupyter nbconvert example.ipynb --to pdf --template ctex --template-file report
```

## License

`nb-tmpl-ctex` is distributed under the terms of the [MIT](https://spdx.org/licenses/MIT.html) license.
