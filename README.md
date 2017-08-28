[![Build Status](https://travis-ci.org/neka-nat/tensorboard-chainer.svg?branch=master)](https://travis-ci.org/neka-nat/tensorboard-chainer)

[![PyPI version](https://badge.fury.io/py/tensorboard-chainer.svg)](https://badge.fury.io/py/tensorboard-chainer)

# tensorboard-chainer

Write tensorboard events with simple command.
including scalar, image, histogram, audio, text, graph and embedding.

This is based on [tensorboard-pytorch](https://github.com/lanpa/tensorboard-pytorch).

## Usage

Install tensorflow.

```
pip install tensorflow
```

Execute demo.py and tensorboard.
Access "localhost:6006" in your browser.

```
python demo.py
tensorboard --logdir runs
```

## Scalar example

![graph](screenshots/scalar.png)

## Histogram example

![graph](screenshots/histogram.png)

## Graph example

![graph](screenshots/graph.gif)

## Reference

* https://github.com/lanpa/tensorboard-pytorch
* https://github.com/TeamHG-Memex/tensorboard_logger
* https://github.com/mitmul/tfchain