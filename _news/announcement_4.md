---
layout: post
title: Oral presented at 2025 IEEE International Symposium on Biomedical Imaging (ISBI)
date: 2025-04-14 00:00:00-0400
inline: false
related_posts: false
---

#### ASAM: Anatomy-Encoded Segment Anything Model for Medical Images

Jiajing Zhang, Haotian Guan, Wei-Ning Lee

[PDF](/assets/pdf/zhang2025asam.pdf)

---

SAM is a foundation model for image segmentation, aiming to segment any target in any scene. MedSAM is its pretrained version on medical images and can be generalized to different imaging modalities. However, current studies have overlooked the biggest difference between natural and medical images: anatomical features pertaining to biological tissues. Real-world medical imaging can be conceptualized as a convolution of the system impulse response with its interrogated medium. We herein propose an Anatomy-encoded SAM (ASAM), featuring an unsupervised cross-attention to emulate the imaging process, where the values of full-image, anatomy, and modality characteristics constrain each other in every attention operation via convolution and deconvolution in Fourier domain. Specifically, anatomy values are extracted from full-image values by deconvolution with modality values. ASAM focuses on CT, MR, US, X-ray, and PET modalities, and is trained on 37 large-scale public datasets. ASAM achieves a high average Dice of 91.46%, thereby being an advanced foundation model for medical image segmentation.

---

@inproceedings{zhang2025asam,
  title={ASAM: Anatomy-Encoded Segment Anything Model for Medical Images},
  author={Zhang, Jiajing and Guan, Haotian and Lee, Wei-Ning},
  booktitle={2025 IEEE 22nd International Symposium on Biomedical Imaging (ISBI)},
  pages={1--5},
  year={2025},
  organization={IEEE}
}
