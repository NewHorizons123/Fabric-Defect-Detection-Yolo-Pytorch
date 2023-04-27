
Fabric Defect Detection - v5 V1
==============================

This dataset was exported via roboflow.ai on September 20, 2021 at 10:41 PM GMT

It includes 202 images.
Hole-Knot-Stain are annotated in YOLO v5 PyTorch format.

The following pre-processing was applied to each image:
* Auto-orientation of pixel data (with EXIF-orientation stripping)
* Resize to 416x416 (Stretch)

The following augmentation was applied to create 3 versions of each source image:
* 50% probability of horizontal flip
* 50% probability of vertical flip
* Randomly crop between 0 and 25 percent of the image
* Random shear of between -15° to +15° horizontally and -15° to +15° vertically
* Random brigthness adjustment of between -23 and +23 percent
* Salt and pepper noise was applied to 7 percent of pixels

The following transformations were applied to the bounding boxes of each image:
* Random exposure adjustment of between -25 and +25 percent


