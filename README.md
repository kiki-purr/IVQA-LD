# IVQA-LD: Inclusive Multimodal Understanding for Population with Limb Deficiency

## 🔥 News
- [2026/05] IVQA-LD has been accepted to ICML 2026.
- [2026/07] Dataset is released.

---

## 📖 Overview

People with limb differences often face significant barriers in benefiting from inclusive AI services, largely because existing vision–language resources rarely provide structured, high-quality data grounded in disability contexts. To bridge this gap, we introduce a limb-deficiency–aware, body-centric learning and evaluation paradigm for multimodal reasoning, comprising (i) a large-scale limb-aware vision–language dataset and benchmark, and (ii) a dedicated model adaptation strategy for Vision–Language Models (VLMs) in limb-difference scenarios.

Our data collection covers all eight limb-deficiency types across diverse real-world scenes, and is systematically organized into 96 limb-affected human action categories and 68 functional classes developed with reference to the WHO functioning framework and Paralympic classification resources. Building on this foundation, we curate an expert-annotated vision–language dataset, Inclusive VQA for Limb Deficiency (IVQA-LD), featuring 80K VQA pairs spanning eight core tasks such as visual grounding, quantitative reasoning, functional semantic classification, and instructional text generation. We benchmark state-of-the-art VLMs on IVQA-LD and observe consistent failures across tasks, revealing substantial gaps in limb-aware perception and reasoning. To address these challenges, we further propose Body-centric Structure-aware Initialization (BSI), which aligns model representations with limb-specific semantics. With BSI, VLMs fine-tuned on IVQA-LD achieve significant performance gains across all tasks. The IVQA-LD dataset is publicly available to support future research on inclusive AI.

---

## 📥 Download

### Datasets

| Split | Download |
|--------|----------|
| Training Set | [Google Drive](https://drive.google.com/drive/folders/17tAE8iNQ0Utz2LfjhEX3LLDD0WCOMrCP?usp=sharing) |
| Test Set | [Google Drive](https://drive.google.com/drive/folders/1umbi3JR5nJqKOtjdi3fF434jPQEil53K?usp=sharing) |

### Annotations

| File | Download |
|------|----------|
| Training Annotations | [Google Drive](https://drive.google.com/drive/folders/1oXiiVX3pGfKPFJvOw1hWpnC-D9fZVsuv?usp=sharing) |
| Test Annotations | [Google Drive](https://drive.google.com/file/d/1vN0V5-YQOPsjSSLXQoZUXeX0ihHsRTph/view?usp=sharing) |

## Dataset Usage

The dataset is released for academic research purposes only.
Please cite our paper when using the dataset.

## Citation

The BibTeX entry will be available after the paper is officially published.
