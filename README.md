RESNET 18 VS VGG16 FOR AUTOMATED DIAGNOSIS AND CLASSIFICATION OF WHITE MATTER LESIONS IN BRAIN SURFACES OF MULTIPLE SCLEROSIS PATIENTS

This research compares the ResNet 18 and VGG 16 performances and results for automatically analyzing brain MRI scans from multiple sclerosis (MS) patients.
The goal is to identify these WMLs and classify them into two classes, the class that contains the MRIs with white matter lesions, and the other
class is for MRIs that do not have these lesions, ultimately helping diagnose and assess this disease. The image dataset was modified by applying data augmentation, preprocessing methods, compression, and normalization. 
The performance of each model was then evaluated using the metrics of accuracy, precision, recall, and F-score.
Results include the evaluation of ResNet 18 and VGG 16 applied to the modified image dataset. 
The models achieved promising results showcasing powerful tools for medical imaging diagnosis. 
ResNet 18 achieved a success rate of 94% and VGG 16 obtained a success rate of 86% for accurately detecting white matter lesions on the brain surfaces of multiple sclerosis patients and classifying them.

ResNet 18 architecture with transfer learning:

<img width="546" alt="Screen Shot 2024-05-17 at 1 33 01 PM" src="https://github.com/hajami0802/Multiple_Sclorisis_Deep_Learning/assets/169827483/7678863c-20b2-4124-b809-003e21e007cd">


VGG 16 architecture with transfer learning:

<img width="579" alt="Screen Shot 2024-05-17 at 1 33 20 PM" src="https://github.com/hajami0802/Multiple_Sclorisis_Deep_Learning/assets/169827483/81b76128-91a4-4ad0-bc94-c3e3777998d0">


References:
Umbaugh, Scott E. Digital Image Enhancement, Restoration and Compression: Digital Image Processing and Analysis. CRC Press, 2023.
CVIPtools (2023), “Computer Vision and Image Processing Tools for MATLAB”,
https://cviptools.siue.edu/downloads.php

Ajami, Hanieh, Mahsa Kargar Nigjeh, and Scott E. Umbaugh. "Unsupervised white matter lesion
identification in multiple sclerosis (MS) using MRI segmentation and pattern classification: a
novel approach with CVIPtools." Applications of Digital Image Processing XLVI. Vol. 12674.
SPIE, 2023.

Nigjeh, Mahsa Kargar, Hanieh Ajami, and Scott E. Umbaugh. "Automated classification of
 white matter lesions in multiple sclerosis patients' MRI images using gray level enhancement and
 deep learning." Applications of Digital Image Processing XLVI. Vol. 12674. SPIE, 2023.

Ayoub, Shahnawaz & Gulzar, Yonis & Reegu, Faheem & Turaev, Sherzod. (2022). Generating Image Captions Using Bahdanau Attention Mechanism and Transfer Learning. Symmetry. 14. 2681. 10.3390/sym14122681.
