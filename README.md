# PCMTRefer
PCMTRefer: Symmetry-Aware Text-Guided Point Mamba for Indoor 3D Referring Segmentation

---
Introduction
Indoor 3D referring segmentation aims to segment the target object from a point cloud according to a given natural language description. Existing multimodal methods mainly focus on feature fusion between language and point clouds, while neglecting inherent structural symmetry and repetitive geometric patterns in indoor scenes.
In this work, we propose PCMTRefer, a symmetry-aware text-guided Point Mamba framework for indoor 3D referring segmentation. The framework leverages bidirectional Mamba state-space modeling to capture direction-consistent structural geometric features, and adopts language-guided semantic injection and semantic primitive learning to enhance cross-modal alignment. Extensive experiments on the ScanRefer benchmark demonstrate that our method achieves competitive performance on 3D referring segmentation tasks.
News
[2026] This repository is officially established. The full code, training scripts, configuration files, and experimental results will be gradually released after paper acceptance.
Code Release Schedule
We are currently organizing and standardizing the project code. All complete source code, preprocessing scripts, training pipelines, and visualization codes will be fully open-sourced once the paper is officially accepted and published.
Please star and watch this repository for the latest updates.
Visualization Results
We provide qualitative visualization of typical successful segmentation cases and challenging failure cases, including object occlusion, intra-class interference, complex spatial layout, and ambiguous language description scenarios.
<div align="center">
  <img width="528" height="431" alt="image"
       src="https://github.com/user-attachments/assets/5ff66cf8-c525-4907-8138-c2ed8a1c5ed1" />

  <br><br>

  <img width="515" height="456" alt="image"
       src="https://github.com/user-attachments/assets/d2a99140-7624-440f-a8d8-a112ff348c21" />
</div>

