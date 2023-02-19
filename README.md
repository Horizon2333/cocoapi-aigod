# COCO API for AI-GOD Dataset

In this repo, we fork the cocoapi from AI-TOD and modify it for AI-GOD Dataset. And add several detailed metrics for AP and AR. 

## Installation

Currently, you could install by run

```shell
pip install "git+https://github.com/Horizon2333/cocoapi-aigod.git#subdirectory=aigodpycocotools"
```

Or you can choose clone the whole project

```shell
git clone https://github.com/Horizon2333/cocoapi-aigod
cd cocoapi-aigod/aigodpycocotools
python setup.py build_ext --inplace
```

## Reference

* [cocoapi-aigod](https://github.com/jwwangchn/cocoapi-aitod) of [AI-TOD dataset](https://github.com/jwwangchn/AI-TOD).
