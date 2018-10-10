# Trovotutto

[![License: GPL v3+](https://img.shields.io/badge/license-GPL%20v3%2B-blue.svg)](http://www.gnu.org/licenses/gpl-3.0) 
[![Python 3.x Support](https://img.shields.io/pypi/pyversions/Django.svg)](https://python.org)


![trovotutto command line tool](https://raw.githubusercontent.com/tallero/trovotutto/master/screenshots/trovotutto-cmd.gif)

*Trovotutto* (Italian for *"I find everything*) is a small naive `python 3.x` search engine using k-grams. It was conceived as a `find` replacement that would be tolerant to typos and that would take paths into consideration when searching.

At the time of writing it supports recursively searching for files in a directory (according to various criteria) and in PGPgrams databases. Anyway, it is so small that can be easily extended to work on other data structures.

## Installation

*Trovotutto* is available through the [Python Package Index (PyPI)](https://pypi.org/). Pip is already installed if you are using Python 3 >=3.4 downloaded from [python.org](https://python.org); if you're using a GNU/Linux distribution, you can find how to install it on this [page](https://packaging.python.org/guides/installing-using-linux-tools/#installing-pip-setuptools-wheel-with-linux-package-managers).
After setting up pip, you can install *trovotutto* by simply typing in your terminal

    pip3 install trovotutto

## Usage

Trovotutto install a command line utility with the same name that can be used to search and open search results. Application selection is handled through `xdg-open`, so be sure to have it installed if you want to use it this way. The command line is not recommended for performance when searching in large directories because by defaults it rebuilds the database at each run.

More proficient usage is obtained in IPython console for repeated usage, as the index is kept in memory:

![trovotutto from ipython](https://raw.githubusercontent.com/tallero/trovotutto/master/screenshots/trovotutto-ipython.gif)

## About

This program is licensed under [GNU General Public License v3 or later](https://www.gnu.org/licenses/gpl-3.0.en.html) by [Pellegrino Prevete](http://prevete.ml). If you find this program useful, consider offering me a [beer](https://patreon.com/tallero), a new [computer](https://patreon.com/tallero) or a part time remote [job](mailto:pellegrinoprevete@gmail.com) to help me pay the bills.
