# This fork of the cocoapi is re-forked from YoutubeVOS. You can follow the same instructions to install this api. Both apis are identical, except for the range of the 'areaRng' key, which now evalutes the size of an instance based on the amount of voxels instead of average area per frame.

## Note that you might only need this repo to test out https://github.com/ygCoconut/mAP_3Dvolume. The master branch is optimized to run super fast mAP 3D evaluation for large 3D volumes that contain many 3D instances. The master branch does not require the cocoapi. If you wish so, you can test the master branch results with the mAP_3Dvolume legacy branch. The legacy branch requires this reforked cocoapi.
- Use cases for this repo:
    1. You want to make sure the 3D object mAP evaluation is running properly from the legacy branch of mAP_3Dvolume 
    2. you want to create .json files that respect the coco format.
- If you are just looking for fast mAP evaluation of 3D objects, you should rather use the master branch of mAP_3Dvolume. It is optimized to run super fast and does not require compiling 

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
