# This fork of the cocoapi is re-forked from YoutubeVIS. You can follow the same instructions to install this api. Both apis are identical, except for the range of the the 'areaRng' key, which now evalutes the size of an instance based on the amount of voxels instead of average area per frame.


# YouTubeVIS data loading and evaluation
## Introduction

This package provides data loading and evaluation functionalities for video instance segmentation on [YouTubeVIS](https://youtube-vos.org/dataset/vis/). It is built based on [COCO API](https://github.com/cocodataset/cocoapi) designed for the MSCOCO dataset (http://cocodataset.org/). For evaluation metrics, please refer to the [descriptions](https://youtube-vos.org/dataset/vis/) for details.
We have only implemented Python API for YouTubeVIS. API in other languages are not available for now.

## Installation
To install:
```
cd PythonAPI
# To compile and install locally 
python setup.py build_ext --inplace
# To install library to Python site-packages 
python setup.py build_ext install
```

## Contact
If you have any questions regarding the repo, please create an issue.
