# pySym
Python Symbolic Execution

[ ![Codeship Status for Owlz/pySym](https://codeship.com/projects/691a2930-c591-0133-c81b-4e8753dd3f97/status?branch=master)](https://codeship.com/projects/138556)
[![Coverage Status](https://coveralls.io/repos/github/Owlz/pySym/badge.svg?branch=HEAD)](https://coveralls.io/github/Owlz/pySym?branch=HEAD)

# Disclaimer
This is just for me to mess around with symbolic execution of python scripts. Likely not going to work/be broken so probably not something you care to play with.

# Tests
Tests need to be done from somewhere that has z3 access. For my env, this means the virtual environment.

```bash
$ workon z3
(z3)$ py.test --cov=. --cov-config=.coveragerc
```