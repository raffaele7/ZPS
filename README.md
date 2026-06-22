# Automated ZPS Grading

## ZPS Determination

`ZPS determination.ipynb` automatically computes the Zurich Pituitary Score from the segmentation of a pituitary adenoma and the cavernous segments of the internal carotid artery.

Reference:
https://radiopaedia.org/articles/zurich-pituitary-score

## Automated Segmentation

For generating the corresponding mask, trained nnU-Net models can be downloaded here:

https://owncloud.damutten.ch/s/zCbVKWkpILpABgW

To set up the nnU-Net environment, please consider the original repository:

https://github.com/MIC-DKFZ/nnUNet

## Graphical User Interface for Segmentation

The Pituitary GUI provides a comprehensive, user-friendly workflow designed for clinical and research use. It streamlines the entire process of pituitary adenoma analysis:

- **Study Selection**: Easily browse and select pituitary MRI studies from your local file system
- **Automated Segmentation**: Automatically runs the task-local nnU-Net segmentation model to identify and segment the pituitary adenoma and cavernous carotid artery segments
- **Interactive Review**: Provides an intuitive interface for reviewing and validating the resulting adenoma mask before proceeding to ZPS grading
- **Integrated Scoring**: Seamlessly generates the Zurich Pituitary Score (ZPS) based on the validated segmentation

The GUI eliminates the need to manually run scripts, making it accessible for clinicians without programming expertise. It is available here:

https://owncloud.damutten.ch/s/agXBIRGZuzZsII8

![Pituitary GUI](pituitary_2.png)

## Citations

Please cite the following publications when using this software:

Da Mutten R, Zanier O, Bottini M, Baumann Y, Ciobanu-Caraus O, Regli L, Serra C, Staartjes VE. Fully automated grading of pituitary adenoma. *Neuroimage Rep.* 2025 Jan 29;5(1):100233. doi: 10.1016/j.ynirep.2025.100233

Da Mutten R, Zanier O, Regli L, Serra C, Staartjes V. Ventricular Volume and Width Quantification using Deep Convolutional Networks Incorporated in a Graphical User Interface. *Brain and Spine*. https://doi.org/10.1016/j.bas.2024.102848

Da Mutten R, Zanier O, Ciobanu-Caraus O, Voglis S, Hugelshofer M, Pangalu A, Regli L, Serra C, Staartjes VE. Automated volumetric assessment of pituitary adenoma. *Endocrine* 83:171-177 (2024). https://doi.org/10.1007/s12020-023-03548-6

## License

This software is provided under the **Academic Non-commercial Use License**. For full details, please see [LICENSE.txt](LICENSE.txt).

**Key Points:**
- Non-exclusive, non-transferable, royalty-free license for academic, non-commercial purposes only
- Software is provided "AS IS" with no warranties
- Redistribution and commercial use are prohibited
- Users must cite the associated publications and the University of Zurich
- The University of Zurich retains all title and intellectual property rights

For the complete terms and conditions, refer to [LICENSE.txt](LICENSE.txt).
