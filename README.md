# PyTorch Geometric Deep Learning Library

[![Build Status][build-image]][build-url]
[![Code Coverage][coverage-image]][coverage-url]
[![Requirements Status][requirements-image]][requirements-url]

[build-image]: https://travis-ci.org/rusty1s/pytorch_geometric.svg?branch=master
[build-url]: https://travis-ci.org/rusty1s/pytorch_geometric
[coverage-image]: https://codecov.io/gh/rusty1s/pytorch_geometric/branch/master/graph/badge.svg
[coverage-url]: https://codecov.io/github/rusty1s/pytorch_geometric?branch=master
[requirements-image]: https://requires.io/github/rusty1s/pytorch_geometric/requirements.svg?branch=master
[requirements-url]: https://requires.io/github/rusty1s/pytorch_geometric/requirements/?branch=master

## Requirements

Install `pytorch` and `torchvision` manually.
If cuda is available, it is recommended to install `cupy`.

To install the additional python packages needed, run:

```shell
pip install -r requirements.txt
```

## Running tests

Install the test requirements and run the test suite:

```shell
pip install -r requirements_test.txt
nosetests
```
