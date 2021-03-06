# Elasticsearch_kernel

Elasticsearch  Kernel for Jupyter

![PyPI version](https://img.shields.io/pypi/pyversions/elasticsearch_kernel.svg)
![Github license](https://img.shields.io/github/license/Hourout/elasticsearch_kernel.svg)
[![PyPI](https://img.shields.io/pypi/v/elasticsearch_kernel.svg)](https://pypi.python.org/pypi/elasticsearch_kernel)
![PyPI format](https://img.shields.io/pypi/format/elasticsearch_kernel.svg)
![contributors](https://img.shields.io/github/contributors/Hourout/elasticsearch_kernel)
![downloads](https://img.shields.io/pypi/dm/elasticsearch_kernel.svg)


[中文介绍](document/chinese.md)

## Installation

#### step1:
```
pip3 install elasticsearch_kernel
```

To get the newest one from this repo (note that we are in the alpha stage, so there may be frequent updates), type:

```
pip3 install git+git://github.com/Hourout/elasticsearch_kernel.git
```

#### step2:
Add kernel to your jupyter:

```
python3 -m elasticsearch_kernel.install
```

ALL DONE! 🎉🎉🎉

## Uninstall

#### step1:

View and remove elasticsearch kernel
```
jupyter kernelspec list
jupyter kernelspec remove elasticsearch
```

#### step2:
uninstall elasticsearch kernel:

```
pip3 uninstall elasticsearch-kernel
```

ALL DONE! 🎉🎉🎉

## Using

```
jupyter notebook
```
<img src="image/elasticsearch1.png" width = "700" height = "300" />

### step1: you should set elasticsearch server (host and port)

### step2: write your elasticsearch sql
![](image/elasticsearch2.png)

## Quote 
kernel logo

<img src="https://avatars0.githubusercontent.com/u/6764390?s=200&v=4" width = "32" height = "32" />

- https://www.elastic.co/cn/elasticsearch
