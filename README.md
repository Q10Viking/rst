## 介绍
reStructuredText 教程 使用Sphinx生成文档

在线预览[https://hzz-rst.readthedocs.io/zh_CN/latest/](https://hzz-rst.readthedocs.io/zh_CN/latest/)

## 环境


[安装参照博客](https://www.cnblogs.com/zhaojiedi1992/p/zhaojiedi_python_013_rst_spinx.html) 以及[官网](http://www.sphinx-doc.org/en/master/usage/quickstart.html)

> [更加详细的文档](https://docs.readthedocs.io/en/stable/intro/getting-started-with-sphinx.html#quick-start-video)


```
conda install sphinx
conda install -c conda-forge restructuredtext_lint 
```


### 主题

[主题官网](https://sphinx-themes.org/)

> 需要安装 **sphinx_theme** [官网](https://pypi.org/project/sphinx-theme/)

```bash
pip install sphinx_theme
```

选择一个主题，然后点击conf.py,复制相应的代码到自己的conf.py,如：

```python
#---sphinx-themes-----
html_theme = 'neo_rtd_theme'
import sphinx_theme
html_theme_path = [sphinx_theme.get_html_theme_path()]
```

