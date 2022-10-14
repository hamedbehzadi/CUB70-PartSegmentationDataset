# CUB70-PartSegmentationDataset


This repository contains the part segmentation dataset for first 70 classes of CUB-200-2011 dataset used in the paper:

"A Protocol for Evaluating Model Interpretation Methods from Visual Explanations" accepted at IEEE/CVF winter Conference on Applications of Computer Vision (WACV2023).

The dataset CUB70 is a subset derived from the first 70 classes of the CUB-200-2011. For this subset we manually produced pixel-wise annotation masks for 11 parts including head, right eye, left eye, beak, neck, body, right wing, left wing, right leg, left leg, and tail. Worth noting, there is no spatial overlap among the parts in the datasets. 



![CUB-Dataset](https://user-images.githubusercontent.com/45251957/195791993-8b1892a9-9799-4898-9d24-6566f18fa2a8.jpg)


There are two files in this repository.
1- part_labels.txt : this file contains the name of parts.
2- Masks_Per_class: this file contains the part sementation binary mask for each class separately.
