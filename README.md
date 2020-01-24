# NIH Chest-XRay14 segmentations
Anatomical segmentation masks produced for [NIH Chest-XRay14](https://www.nih.gov/news-events/news-releases/nih-clinical-center-provides-one-largest-publicly-available-chest-x-ray-datasets-scientific-community) dataset using [AC-RegNet](https://github.com/lucasmansilla/ACRN_Chest_X-ray_IA) with a multi-atlas segmentation model.

## Content:
- *segmentations.tar.gz.\**: Files containing the anatomical segmentation masks.
- *rca_dice_scores.csv*: File containing the Dice scores estimated with [Reverse Classification Accuracy (RCA)](https://arxiv.org/abs/1702.03407) for the segmentation masks.

To extract all segmentation masks you can use the *cat* command to first join the tar blocks and then the *tar* command to extract the entire file:
```
cat segmentations.tar.gz.* | tar xzvf -
```

## Dataset Metadata
The following table is necessary for this dataset to be indexed by search
engines such as <a href="https://g.co/datasetsearch">Google Dataset Search</a>.

<div itemscope itemtype="http://schema.org/Dataset">
<table>
  <tr>
    <td>name</td>
    <td><code itemprop="name">NIH Chest-XRay14 segmentations</code></td>
  </tr>
  <tr>
    <td>url</td>
    <td><code itemprop="url">https://github.com/lucasmansilla/NIH_chest_xray14_segmentations</code></td>
  </tr>
  <tr>
    <td>description</td>
    <td><code itemprop="description">Anatomical segmentation masks of lung and heart produced for NIH Chest-XRay14 dataset using AC-RegNet with a multi-atlas segmentation model</code></td>
  </tr>
  <tr>
    <td>citation</td>
    <td><code itemprop="citation">Learning deformable registration of medical images with anatomical constraints. L. Mansilla, D.H. Milone and E. Ferrante. Neural Networks. ISSN: 0893-6080 (2020, Elsevier)</code></td>
  </tr>
  <tr>
    <td>datePublished</td>
    <td><code itemprop="datePublished">2019-08-08</code></td>
  </tr>
</table>
</div>

## Reference:
If you use source code or results from this repository in your publication, please cite our paper:
- "Learning deformable registration of medical images with anatomical constraints. L. Mansilla, D.H. Milone and E. Ferrante. Neural Networks. ISSN: 0893-6080 (2020, Elsevier)."
