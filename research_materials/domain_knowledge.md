# 🧠 Intracranial Aneurysm Domain Terms

1. **Aneurysm** means bulging of blood in a blood vessel, and **intracranial** means within the skull.  
2. **Focal dilation** in the brain refers to an abnormal, localized widening or expansion of a structure, most commonly blood vessels or fluid-filled spaces within the brain.  
3. [RSNA Competition Discussion](https://www.kaggle.com/competitions/rsna-intracranial-aneurysm-detection/discussion/591648)

---

## 📄 Relevant Papers and Extracts

- **[https://arxiv.org/pdf/2305.13398](https://arxiv.org/pdf/2305.13398)**  
  → TOF-MRA, MRI  
  → Localization + classification  
  → ADAM dataset  
  → Model  

- **[https://arxiv.org/pdf/2502.21244](https://arxiv.org/pdf/2502.21244)**  
  → Bo et al. dataset  
  → Focused on various institutions  
  → Self-supervised learning  
  → CMHA dataset  

  **Table 1: Summary of the Head CT Datasets Used in This Paper**

  | Dataset           | Origin      | Purpose      | Resolution       | # Scans | # Aneurysms |
  |------------------|-----------|------------|----------------|-------|------------|
  | Sino-CT [18]     | China     | Pre-training | Low            | 5,406 | – |
  | CQ500 [10]       | India     | Pre-training | Medium-High   | 396   | – |
  | MosMED [20]      | Russia    | Pre-training | High          | 870   | – |
  | TopCoW [29]      | Switzerland | Pre-training | High        | 125   | – |
  | Bo, Int. Train [5] | China  | Fine-tuning | High          | 1,186 | 1,373 |
  | Bo, Int. Test [5]  | China  | Evaluation | High          | 152   | 126 |
  | Bo, Ext. Test [5]  | China  | Evaluation | High          | 138   | 101 |
  | CMHA [24]         | China  | Evaluation | High          | 141   | 95 |
  | Private           | United States | Evaluation | High  | 143   | 219 |

- **Baseline:** 3D U-Net & Segmentation Approaches: [GitHub Link](https://github.com/eloraschoerverth/aneurysm-detection?tab=readme-ov-file)

- **Intracranial aneurysm detection: an object detection perspective** – introduces a 3D anchor-free detection model outperforming SCPM-Net and nnUNet baselines, achieving ~86% sensitivity and ~0.5 FP/case.  
  [PDF Link](assets/s11548-024-03132-z.pdf)  
  → Datasets  
  → Reduction of hyperparameters and anchor approaches  

- **Systematic surveys/meta-analyses** – e.g. *AI in IA* (European Journal of Radiology 2022, J Neuro-interv Surg 2023) assess sensitivity, workflows, clinical utility.  
  [Article Link](https://www.jneurology.com/articles/enhancing-intracranial-aneurysm-detection-with-artificial-intelligence-in-radiology.html?utm_source=chatgpt.com)

- **Deep learning for automated aneurysm detection on CTA** – uses 2D projections with Faster-RCNN on CTA volumes with ~92% sensitivity overall and ~97% for aneurysms >3 mm.  
  [PDF Link](assets/s11548-020-02121-2.pdf)

---

## 🔑 Key Things

- Sensitivity vs. FPR metric  
- Understand voxels
