# Part Segmentation of 3D Point Clouds with OpenVINO™ 

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/openvinotoolkit/openvino_notebooks/HEAD?labpath=notebooks%2F224-3D-segmentation-point-clouds%2F224-3D-segmentation-point-clouds.ipynb)

![3D chair](https://user-images.githubusercontent.com/91237924/185752178-3882902c-907b-4614-b0e6-ea1de08bf3ef.png)

Point clouds are an important type of geometric data structure. OpenVINO can directly consume point cloud data and perform inference with it.

## Notebook Contents

This notebook demonstrates how to process [point cloud](https://en.wikipedia.org/wiki/Point_cloud) data and run 3D Part Segmentation with OpenVINO. The inputs of this task are a collection of individual data points in a three-dimensional plane with each point having a set coordinates on the X, Y, and Z axes.

In this notebook, we use the [PointNet](https://arxiv.org/abs/1612.00593) pre-trained model to detect each part of a chair and return its category.


## Installation Instructions

If you have not done so already, please follow the [Installation Guide](../../README.md) to install all required dependencies.