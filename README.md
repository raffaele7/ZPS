# Automated ZPS Grading

## ZPS Determination
"ZPS determination.ipynb": Function to automatically determine the zurich pituitary score (https://radiopaedia.org/articles/zurich-pituitary-score). As input, a segmentation of a pituitary adenoma and the cavernous segments of the internal carotid artery should be used.

## Automated Segmentation
For generating the corresponding mask, trained nnU-Net models can be downloaded here: https://owncloud.damutten.ch/s/zCbVKWkpILpABgW.

To set up the nnU-Net environment, please consider the original repository: https://github.com/MIC-DKFZ/nnUNet.


## Citation
Raffaele Da Mutten, Olivier Zanier, Massimo Bottini, Yves Baumann, Olga Ciobanu-Caraus, Luca Regli, Carlo Serra, Victor Staartjes,
Automatic Grading of the Zurich Pituitary Score: Using Semantic Segmentation and a Seed-Growing Algorithm,
Brain and Spine,
Volume 4, Supplement 3,
2024,
103523,
ISSN 2772-5294,
https://doi.org/10.1016/j.bas.2024.103523.
(https://www.sciencedirect.com/science/article/pii/S2772529424007793)

