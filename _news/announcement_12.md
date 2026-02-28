---
layout: post
title: Paper accepted at 2026 International Conference on Learning Representations (ICLR)
date: 2026-01-26 00:00:00-0400
inline: false
related_posts: false
---

#### Nef-Net v2: Adapting Electrocardio Panorama in the wild

Zehui Zhan, Yaojun Hu, Jiajing Zhang, Wanchen Lian, Wanqing Wu, Jintai Chen

[PDF](/assets/pdf/iclr2026.pdf)

---

Conventional multi-lead electrocardiogram (ECG) systems capture cardiac signals from a fixed set of anatomical viewpoints defined by lead placement. However, cer- tain cardiac conditions (e.g., Brugada syndrome) require additional, non-standard viewpoints to reveal diagnostically critical patterns that may be absent in standard leads. To systematically overcome this limitation, Nef-Net was recently introduced to reconstruct a continuous electrocardiac field, enabling virtual observation of ECG signals from arbitrary views (termed Electrocardio Panorama). Despite its promise, Nef-Net operates under idealized assumptions and faces in-the-wild challenges, such as long-duration ECG modeling, robustness to device-specific signal artifacts, and suboptimal lead placement calibration. This paper presents NEF-NET V2, an enhanced framework for realistic panoramic ECG synthesis that supports arbitrary-length signal synthesis from any desired view, generalizes across ECG devices, and compensates for operator-induced deviations in electrode place- ment. These capabilities are enabled by a newly designed model architecture that performs direct view transformation, incorporating a workflow comprising offline pretraining, device calibration tuning steps as well as an on-the-fly calibration step for patient-specific adaptation. To rigorously evaluate panoramic ECG synthe- sis, we construct a new Electrocardio Panorama benchmark, called Panobench, comprising 4470 recordings with 48-view per subject, capturing the full spatial variability of cardiac electrical activity. Experimental results show that NEF-NET V2 delivers substantial improvements over Nef-Net, yielding an increase of around 6 dB in PSNR in real-world setting.
