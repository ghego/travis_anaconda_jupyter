
[![Build Status](https://travis-ci.org/ghego/travis_anaconda_jupyter.svg?branch=master)](https://travis-ci.org/ghego/travis_anaconda_jupyter)

# Travis + Anaconda + Jupyter

Testing Jupyter notebooks with Travis.ci

Barebone example of how to check for execution errors in Jupyter notebook using Travis CI and a custom conda environment file.

The notebook is executed using `jupyter nbconvert` in a subprocess while monitoring for errors.

Requirements:
- jupyter
- py.test
