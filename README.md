This is the colorectal adenoma dataset for "CAMEL: A Weakly Supervised Learning Framework for Histopathology Image Segmentation" (ICCV 2019). [Paper](http://arxiv.org/abs/1908.10555)

## Overview

We open-source the colorectal adenoma dataset with image-level labels for weakly supervised learning. This dataset contains 177 whole slide images (156 contain adenoma) gathered and labeled by pathologists from the Department of Pathology, The Chinese PLA General Hospital.

## Download

The dataset is hosted on [Google Drive](https://drive.google.com/open?id=1brr8CnU6ddzAYT157wkdXjbSzoiIDF9y) or [Baidu Drive](https://pan.baidu.com/s/1kk3rUgFkY7b3FX9g--w_5g) with password `x2o5`.

## Description

The images are cropped from the whole slide images with size 1280x1280. The image-level label is given as 

`
image_name,label
`

where the label can be either 1 (adenoma) or 0.
