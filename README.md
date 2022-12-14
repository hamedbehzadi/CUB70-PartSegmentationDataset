# CUB70-PartSegmentationDataset


This repository contains the part segmentation dataset for first 70 classes of test category of CUB-200-2011 dataset used in the paper:

"A Protocol for Evaluating Model Interpretation Methods from Visual Explanations" accepted at IEEE/CVF winter Conference on Applications of Computer Vision (WACV2023).

For this subset we manually produced pixel-wise annotation masks for 11 parts including head, right eye, left eye, beak, neck, body, right wing, left wing, right leg, left leg, and tail. Worth noting, there is no spatial overlap among the parts in the datasets. 

There are two files in this repository.

1- part_labels.txt : this file contains the name of parts.

2- AnnotationMasksPerclass.tar.xz: this file contains the part annotation masks for each class separately.


![CUB-Dataset](https://user-images.githubusercontent.com/45251957/195791993-8b1892a9-9799-4898-9d24-6566f18fa2a8.jpg)



If you use the dataset in a publication, please cite the dataset as bellow.

Hamed Behzadi-Khormouji, Jose Oramas. "A Protocol for Evaluating Model Interpretation Methods from Visual Explanations". Winter Conference on Applications of Computer Vision (WACV), 2023.  

@article{eval_protocol,
  title={A Protocol for Evaluating Model Interpretation Methods from Visual Explanations},
  author={Behzadi-Khormouji, Hamed, Oramas, Jos{\'e}},
  journal={Winter Conference on Applications of Computer Vision (WACV)},
  year={2023}
}
