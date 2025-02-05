# Jupyter nbconvert 中文 PDF 模板

Chinese LaTeX/PDF template for Jupyter notebook `nbconvert` using CTeX.

[![PyPI - Version](https://img.shields.io/pypi/v/nb-tmpl-ctex.svg)](https://pypi.org/project/nb-tmpl-ctex)
[![PyPI - Python Version](https://img.shields.io/pypi/pyversions/nb-tmpl-ctex.svg)](https://pypi.org/project/nb-tmpl-ctex)

-----

## 安装

```console
pip install nb-tmpl-ctex
```

## 使用

通过 `nbconvert` 调用：
```bash
# 默认 ctexart
jupyter nbconvert example.ipynb --to pdf --template ctex
# 使用 ctexrep
jupyter nbconvert example.ipynb --to pdf --template ctex --template-file report
```

如果需要在 Jupyter 网页导出时自动使用 CTeX 模板，需要在 `~/.jupyter/jupyter_nbconvert_config.py` 将 `ctex` 模板设置为默认：

```python
c.LatexExporter.template_name = "ctex"
# c.LatexExporter.template_file = "report"
```

## License

`nb-tmpl-ctex` is distributed under the terms of the [MIT](https://spdx.org/licenses/MIT.html) license.
