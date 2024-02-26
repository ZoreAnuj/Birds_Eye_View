# Bird's Eye View

<p align="center">
  <img src="task_overview.png" height="180">
</p>

This code accompanies the paper *["Learning to map surrounding vehicles into bird's eye view using synthetic data"](https://arxiv.org/pdf/1706.08442.pdf)*.

It contains the code for loading data and pre-trained SDPN model proposed in the paper.

## Dataset 
In this repository only one example is provided, to the end of verifying that the model is working correctly.

The **whole dataset**, which comprises more than **1M** couples of bounding boxes, can be found <a href="http://imagelab.ing.unimore.it/imagelab/page.asp?IdPage=19" target="_blank"><b>here</b></a>.

## Input - Prediction - Output

<p align="center">
  <img src="helloworld.PNG">
</p>

#### Dependencies
The code was developed with the following configuration:
* python 2.7.11
* numpy 1.11.2
* opencv 3.1.0
* Theano 0.9.0.dev3
* Keras 1.1.2

Other configuration will reasonably work, but have never been explicitly tested.



