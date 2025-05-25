
My First Project - v1 2025-04-09 2:10am
==============================

This dataset was exported via roboflow.com on April 8, 2025 at 8:43 PM GMT

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

The dataset includes 6335 images.
Objects are annotated in YOLOv11 format.

The following pre-processing was applied to each image:
* Auto-orientation of pixel data (with EXIF-orientation stripping)
* Resize to 320x320 (Stretch)

The following augmentation was applied to create 5 versions of each source image:
* Randomly crop between 0 and 29 percent of the image
* Random rotation of between -20 and +20 degrees
* Random shear of between -15° to +15° horizontally and -14° to +14° vertically
* Random brigthness adjustment of between -24 and +24 percent
* Random Gaussian blur of between 0 and 2 pixels
* Salt and pepper noise was applied to 1.64 percent of pixels


