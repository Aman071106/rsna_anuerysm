✅ Week-by-Week Breakdown
🔍 Week 1 (Aug 4–10): Deep Dive into Data + Problem
Read competition overview, rules, metric

Parse DICOMs, load into NumPy/Nifti format

Visualize scans in 3D using ITK-SNAP / matplotlib

Read 2 key aneurysm detection papers

Explore localizers.csv and segmentation series

Set up codebase (PyTorch, MONAI, 3D U-Net starter)

📌 Deliverable: Clean preprocessed dataset + summary of papers

📦 Week 2 (Aug 11–17): Reproduce Public Baseline
Clone 1–2 Kaggle notebooks (3D U-Net or 2.5D CNN)

Adapt to 6GB GPU: patch training, AMP, batch=1

Train baseline model for 10–20 epochs

Evaluate using pseudo ground truth, .csv generation

Submit first .csv to Kaggle

📌 Deliverable: First submission (score on LB) + working baseline

🏗️ Week 3 (Aug 18–24): Build Modular Pipeline
Create train.py, eval.py, infer.py pipeline

Integrate MONAI transforms + augmentations

Implement patch extractor, dataset caching

Train your own 2D/2.5D or small 3D U-Net from scratch

Run validation loop + metric calculation (sensitivity at FPs)

📌 Deliverable: Your own working training pipeline + custom logs

📚 Week 4 (Aug 25–31): Read & Replicate from Literature
Read 2 advanced papers:

Anatomically Guided Masked Autoencoder (2024)

nnDetection (2023)

Try pretrained ViT / MAE / nnUNet

Train model with MedicalNet weights or ViT backbone

Compare learning curves with your baseline

📌 Deliverable: Transfer learning experiment vs from-scratch baseline

🧪 Week 5 (Sep 1–7): Hyperparameter Tuning + Multi-Modality
Train on other modalities (T1-post, T2)

Implement multi-input model or ensemble

Add contrast enhancement / vessel filters

Use axial + sagittal + coronal fusion (2.5D)

Submit best checkpoint

📌 Deliverable: Multi-modality model and 2nd top submission

🧠 Week 6 (Sep 8–14): Postprocessing + Error Analysis
Implement false positive filtering (morphology, volume)

Analyze FP cases → tune threshold

Add detection head (bounding box, blobs)

Implement TTA (test-time augmentation)

Start ensembling top 3 models

📌 Deliverable: Cleaned-up .csv predictions with lower FP rate

🧬 Week 7 (Sep 15–21): Smart Ensembling & Robust Validation
Blend models (soft-voting, detection + segmentation merge)

K-fold validation (3 or 5 folds)

Implement automatic model scoring

Run ensemble across folds

📌 Deliverable: Ensemble submission with metric tracker

🧹 Week 8 (Sep 22–28): Pipeline & Inference Polishing
Clean up CLI code and config files

Automate test-time .csv generation

Add Docker or Colab-compatible pipeline

Visualize predictions overlayed on CT/MRA

📌 Deliverable: Final inference pipeline + Colab test run

🏁 Week 9 (Sep 29–Oct 5): Final Submissions Round 1
Submit 2–3 polished models

Track performance vs public leaderboard

Rank ensemble variants

Optimize run-time (faster inference / batching)

📌 Deliverable: Top-3 best-scoring submissions

🥇 Week 10 (Oct 6–13): Final Ensembling + Write-up
Lock in final model architecture

Final ensemble with weights or selection

Write technical writeup (for discussion forum)

Backup all models & notebooks

📌 Deliverable: Submit final .csv + clean notebook for reproducibility