# EDA Package

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