# EDA Package

## Template Doc
https://docs.google.com/document/d/1FfXoe7X7a7DY6xb3ryDc7LlQD1rxT-w3tqYePUXJ0Ig

## Plan to create Template
1. Preprocessing
    1. Change the data types
    1. Missing Values
    1. Feature Engineering
        1. Feature Selection
            1. Correlation based
            1. Tree based 
        1. Feature Reduction
            1. PCA
        1. Feature Addition
            1. By combining some features together
    1. Outlier
        1. Use describe to figure out any Outliers
        1. Use scatter plots
    1. Check individual Column distribution (Plotly Express)
        1. Heatmap
        1. PairPlot
        1. Scatter Plot
    1. Transformation of Columns
        1. Log Transformation
    1. Scaling of Columns
    1. Handle The Imbalance (of Class - SalesPrie Category)
1. Plotting

# README references
* https://help.github.com/en/github/writing-on-github/basic-writing-and-formatting-syntax
* https://guides.github.com/features/mastering-markdown/
* https://github.com/tchapi/markdown-cheatsheet/blob/master/README.md

## Install
Install with either:

```
git clone https://github.com/ksranjith786/EDA.git
cd EDA
pip install --user .
```
or directly
```
pip install --user git+https://github.com/ksranjith786/EDA.git#egg=Basic
```

## PLEASE

* the same is true for PYTHONPATH too
* use [PEP-370](https://www.python.org/dev/peps/pep-0370/) instead of virtualenv, it's a standard feature and not a hack around the `python` executable. Quickest Howto about pep-370, use `pip install --user`, and optionally set the `PYTHONUSERBASE` environment variable to choose another directory than `~/.local/`.

Thanks!


## Other resources:

* https://towardsdatascience.com/publishing-your-own-python-package-3762f0d268ec
* http://python-packaging.readthedocs.org/en/latest/
* https://pip.pypa.io/en/stable/
* https://chriswarrick.com/blog/2014/09/15/python-apps-the-right-way-entry_points-and-scripts/