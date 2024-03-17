# Brain-Tumor-Segmentation


## Image segmentation using Vanilla UNet, UNet with ResNeXt50 backbone, and Feature Pyramid Network.¶
Steps:

1. Data Preparation

2. Data Visualization

3. Data Augmentaions

4. UNet

5. FPN

6. UNet ResNeXt50

7. Train Models

8. Prediction on test data

9. Visualization of the prediction on test data

Based on BONHART's Kaggle notebook



## About Dataset:


LGG Segmentation Dataset


Dataset used in:

Mateusz Buda, AshirbaniSaha, Maciej A. Mazurowski "Association of genomic subtypes of lower-grade gliomas with shape features automatically extracted by a deep learning algorithm." Computers in Biology and Medicine, 2019.

and

Maciej A. Mazurowski, Kal Clark, Nicholas M. Czarnek, Parisa Shamsesfandabadi, Katherine B. Peters, Ashirbani Saha "Radiogenomics of lower-grade glioma: algorithmically-assessed tumor shape is associated with tumor genomic subtypes and patient outcomes in a multi-institutional study with The Cancer Genome Atlas data." Journal of Neuro-Oncology, 2017.

This dataset contains brain MR images together with manual FLAIR abnormality segmentation masks.
The images were obtained from The Cancer Imaging Archive (TCIA).
They correspond to 110 patients included in The Cancer Genome Atlas (TCGA) lower-grade glioma collection with at least fluid-attenuated inversion recovery (FLAIR) sequence and genomic cluster data available.
Tumor genomic clusters and patient data is provided in data.csv file.
