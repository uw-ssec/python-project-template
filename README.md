# python-project-template

<span><img src="https://img.shields.io/badge/SSEC-Project-purple?logo=data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAA0AAAAOCAQAAABedl5ZAAAACXBIWXMAAAHKAAABygHMtnUxAAAAGXRFWHRTb2Z0d2FyZQB3d3cuaW5rc2NhcGUub3Jnm+48GgAAAMNJREFUGBltwcEqwwEcAOAfc1F2sNsOTqSlNUopSv5jW1YzHHYY/6YtLa1Jy4mbl3Bz8QIeyKM4fMaUxr4vZnEpjWnmLMSYCysxTcddhF25+EvJia5hhCudULAePyRalvUteXIfBgYxJufRuaKuprKsbDjVUrUj40FNQ11PTzEmrCmrevPhRcVQai8m1PRVvOPZgX2JttWYsGhD3atbHWcyUqX4oqDtJkJiJHUYv+R1JbaNHJmP/+Q1HLu2GbNoSm3Ft0+Y1YMdPSTSwQAAAABJRU5ErkJggg==&style=plastic" /><span>
![BSD License](https://badgen.net/badge/license/BSD-3-Clause/blue)
[![Hatch project](https://img.shields.io/badge/%F0%9F%A5%9A-Hatch-4051b5.svg)](https://github.com/pypa/hatch)
[![Ruff](https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/astral-sh/ruff/main/assets/badge/v2.json)](https://github.com/astral-sh/ruff)

[![Documentation Status](https://readthedocs.org/projects/ssec-python-project-template/badge/?version=latest)](https://ssec-python-project-template.readthedocs.io/en/latest/?badge=latest)
[![pre-commit.ci status](https://results.pre-commit.ci/badge/github/uw-ssec/python-project-template/main.svg)](https://results.pre-commit.ci/latest/github/uw-ssec/python-project-template/main)
[![CI](https://github.com/uw-ssec/python-project-template/actions/workflows/ci.yml/badge.svg)](https://github.com/uw-ssec/python-project-template/actions/workflows/ci.yml)
[![codecov](https://codecov.io/gh/uw-ssec/python-project-template/graph/badge.svg?token=13LYMLQBZL)](https://codecov.io/gh/uw-ssec/python-project-template)

Python project repository template for developing python package. This template
includes a basic structure for developing a python package, including a license,
documentation, testing, and continuous integration. It is based on the
[Scientific Python Library Development Guide and Cookiecutter](https://github.com/scientific-python/cookie).

This repository contains a template for developing a python project. To start,
click on the green
[Use this template](https://github.com/uw-ssec/python-project-template/generate)
in the top right. This will allow you to create a new project using this base
template.

## What's included

This template contains the following:

1. Python package setup files for building python package to a distribution. See
   [PyPA packaging user guide](https://packaging.python.org/en/latest/) for more
   info.
2. Basic license file (currently BSD 3-Clause License, but can be modified to
   specific project). See [choose a license](https://choosealicense.com/) for
   more licenses.
3. Starter [Jupyter Book](https://jupyterbook.org) based documentation
   structure.
4. Single test example to demonstrate the use of
   [pytest](https://docs.pytest.org/en/7.2.x/).
5. [GitHub workflow](https://docs.github.com/en/actions/using-workflows/workflow-syntax-for-github-actions)
   config to run tests.
6. [Pre-commit](https://pre-commit.com/) config to enable code style checks
   before committing.
7. [Read The Docs](https://readthedocs.org/) config to enable free hosting of
   documentation.
8. Code coverage analysis with
   [`coverage.py`](https://coverage.readthedocs.io/en/7.2.3/) via
   [`pytest-cov`](https://pytest-cov.readthedocs.io/en/latest/).

## Open source licensing

We encourage that any software that is built upon this template
to be licensed with an [OSI Approved Licenses](https://opensource.org/licenses)
