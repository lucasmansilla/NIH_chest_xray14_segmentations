# NIH Chest-XRay14 segmentations
Anatomical segmentation masks produced for [NIH Chest-XRay14](https://www.nih.gov/news-events/news-releases/nih-clinical-center-provides-one-largest-publicly-available-chest-x-ray-datasets-scientific-community) dataset using [AC-RegNet](https://github.com/lucasmansilla/ACRN_Chest_X-ray_IA) with a multi-atlas segmentation model.

## Content:
- *segmentations.tar.gz.\**: Files containing the anatomical segmentation masks.
- *rca_dice_scores.csv*: File containing the Dice scores estimated with [Reverse Classification Accuracy (RCA)](https://arxiv.org/abs/1702.03407) for the segmentation masks.

To extract all segmentation masks you can use the *cat* command to first join the tar blocks and then the *tar* command to extract the entire file:
```
cat segmentations.tar.gz.* | tar xzvf -
```

## Reference:
If you use source code or results from this repository in your publication, please cite our paper:
- "Learning deformable registration of medical images with anatomical constraints. L. Mansilla, D.H. Milone and E. Ferrante. Neural Networks ISSN: 0893-6080 (2020, Elsevier)."
