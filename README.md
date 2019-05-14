# Deep Learning Coursework: The COMP6248 Reproducibility Challenge  

## Introduction

This is the re-implementation of [Learning to Count Objects in Natural Images for Visual Question Answering][0].

Codes are re-implemented base on [Counting component for VQA][1].

## How to train

To train the two models, run either of the following two commands (or both):
```
python vqa-counter.py 
python vqa-baseline.py 
```
Both models were trained with easy and hard task.

## Plot accuracy

Run the following commands to plot the result.
```
python plot.py  
```
Alternatively, pretrained model weights and evaluation accuracy are stored in `.txt` files, you can just run `plot.py` directly without training.

## Dependencies

This code was confirmed to run with the following environment:

- Python 3.6.3
  - torch 0.4.0
  - torchvision 0.2.1
  - torchbearer 0.3.0
  - numpy 1.14.5

- Cuda 10.0

[0]: https://openreview.net/forum?id=B12Js_yRb
[1]: https://github.com/Cyanogenoid/vqa-counting
