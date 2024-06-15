
MOUTH - v2 2022-10-07 10:55am
==============================

This dataset was exported via roboflow.com on September 21, 2023 at 3:45 AM GMT

Roboflow is an end-to-end computer vision platform that helps you
* collaborate with your team on computer vision projects
* collect & organize images
* understand and search unstructured image data
* annotate, and create datasets
* export, train, and deploy computer vision models
* use active learning to improve your dataset over time

For state of the art Computer Vision training notebooks you can use with this dataset,
visit https://github.com/roboflow/notebooks

To find over 100k other datasets and pre-trained models, visit https://universe.roboflow.com

The dataset includes 509 images.
Mouth are annotated in YOLOv8 format.

The following pre-processing was applied to each image:
* Auto-orientation of pixel data (with EXIF-orientation stripping)
* Resize to 416x416 (Stretch)

The following augmentation was applied to create 3 versions of each source image:

The following transformations were applied to the bounding boxes of each image:
* Equal probability of one of the following 90-degree rotations: none, clockwise, counter-clockwise, upside-down
* Random brigthness adjustment of between -46 and +46 percent


