#   Mobilenetv2 MXNET
## Features 
- An MXNet implementation of mobilenetv2. [Inverted Residuals and Linear Bottlenecks Mobile Networks for Classification  Detection and Segmentation](https://arxiv.org/pdf/1801.04381).
- use relu as it activation layer rather than use relu6 in inverted residual bottleneck layers.

## Results 

We got 0.235 map on coco datasets for mobilenetv2+ssdlite with 512 input size,[here](https://pan.baidu.com/s/1c3IJGOC).
Imagenet model will be released as soon as we reach the accuacy of the paper. 


## Requirements

We tested our code on:

Ubuntu 16.04, Python 2.7 with

numpy(1.11.0), cv2(3.3.0-dev)

mxnet 0.11.0
