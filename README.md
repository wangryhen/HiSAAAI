# HiSTalk: Hierarchical Speech Feature-based Landmark Displacements for 3D Talking Head Animation

Official repository for the paper [HiSTalk: Hierarchical Speech Feature-based Landmark Displacements for 3D Talking Head Animation](http://cv2025h.bwbwiwn.site/).

<p align="center">
  <a href="http://cv2025h.bwbwiwn.site/">
    <img src="https://raw.githubusercontent.com/wangryhen/HiSTalk_Anonymous/main/paper_images/framework.png" alt="Framework overview" width="800"/>
  </a>
</p>

---

## 🔗 Quick Links

* **Project Page**: [Live demo & details](http://cv2025h.bwbwiwn.site/)
* **Code**: Coming soon.
---

## 🔍 Overview

Given an input speech signal, **HiSTalk** generates lifelike 3D talking-head animations by combining:

1. **Coarse Motion Generator (CMG)**: captures global facial trajectories from multi-scale speech embeddings via a lightweight Transformer.
2. **Fine Motion Refiner (FMR)**:

   * **HSF2S** (Hierarchical Speech Features → Sparse landmarks): encodes frame-, phoneme-, word-, and utterance-level cues into weighted sparse landmark displacements using a squeeze-and-excitation gating mechanism.
   * **S2D** (Sparse → Dense): lifts weighted sparse offsets into full-face 3D deformation fields with multi-branch attention-fusion Transformer decoders.

By fusing macro-level guidance with fine-grained refinements, HiSTalk achieves precise lip-sync and rich expressiveness on VOCASET and BIWI benchmarks.

---

## 🎥 Demos

Visit the **anonymous** Project Page for interactive demos and supplementary video: [http://cv2025h.bwbwiwn.site/](http://cv2025h.bwbwiwn.site/)

---

## 📦 Installation

1. Clone the repo
2. Install dependencies

> **Note**: Official code release pending paper acceptance.

---

## 🚀 Usage

1. Prepare data.
2. Train.
3. Inference.
> **Note**: Official code release pending paper acceptance.
---

## 📊 Results

| Dataset     | LVE ↓  | FDD ↓  | LRP ↑  |
| ----------- | ------ | ------ | ------ |
| VOCASET     | 2.6715 | 3.3657 | 97.21% |
| BIWI-Test-A | 3.7554 | 2.7129 | 91.92% |

---

## 📖 Citation

If you use this work, please cite:
@article{2025histalk,

     title={HiSTalk: Hierarchical Speech Feature-based Landmark Displacements for 3D Talking Head Animation},
  
     author={Anonymous},
  
     year={2025},
  
     eprint={arXiv},
  
     archivePrefix={arXiv},
   
     primaryClass={cs.CV} }

---

## 🙏 Acknowledgements

Inspired by and built upon:

* SpeechFormer++ 
* Learning Landmarks 
* S2D-Dec

Template courtesy of SyncTalk.

---

## ⚖️ License

This project is released under the MIT License. See LICENSE for details.
