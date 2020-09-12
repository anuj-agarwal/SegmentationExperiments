# SegmentationExperiments
Experiments with Image Segmentation

# Datasets:
Mask RCNN LungCT Segmentation

This dataset has been collected from [Kaggle](https://www.kaggle.com/kmader/finding-lungs-in-ct-data). The lung images has been converted from .tif to .jpg
and a json file for each example has been added, which contains the annotations for the polygon points of the lungs in coco format utilizing 
[imantics](https://imantics.readthedocs.io/en/latest/index.html) library. For the experimentation purpose, I have created three categories: left_lung, right_lung, and 
unidentified (for the missing parts in the left/right lung). Notebook for reference.

This dataset was used in Mask RCNN framework for experimentation and learning purpose only.
