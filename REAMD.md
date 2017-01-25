# MSSEG 2008 Manuals Project	

Re-doing manual lesion segmentations for algorithm validation.

### Motivation
Algorithms for MS lesion segmentation in brain MRI need training/testing data. It's hard to find. Many authors use the free database from [2008 MS Segmentation Challenge](apples.com). However, the challenge manuals are not very accurate. So, we're re-doing them.

Here is an example:

![e.g. Bad Manual CHB 01](docs/MSSEG2008-bad-manual-eg-CHB-01.png)

FLAIR, Challenge Seg, Updated Seg

### Contributions

Having many manuals per image lets us describe the uncertainty. It would be great if users could contribute a few of their own segmentations. 

To contribute, send a pull request with .nii.gz files and I'll update the table. Segmentations are enumerated with (#) for each contributer, summarized below. Please note the image you used to do the segmentation and the software tool.

| # | Author       | Contact                  | Image | Software  | 
|---|--------------|--------------------------|-------|-----------| 
| 1 | Jesse Knight | jesse.x.knight@gmail.com | FLAIR | 3D Slicer | 
