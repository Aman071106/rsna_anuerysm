
# Learnings from RSNA Anuerysm Prediction Challenge
- 3d slicer
- pydicom
- nibabel
- transfer learning 
- inference servers
- efficient net
- viT
- timm
- SOTA models
- use_amp
In deep learning, use_amp refers to the enabling or disabling of Automatic Mixed Precision (AMP) training. AMP is a technique that significantly accelerates the training of deep learning models by utilizing a combination of different numerical precisions, typically 32-bit floating-point (FP32) and 16-bit floating-point (FP16 or bfloat16).
Here's how use_amp and AMP function:
Mixed Precision:
Deep learning models traditionally train using FP32, which offers high precision but can be computationally intensive. AMP introduces FP16 or bfloat16 for certain operations, which are less precise but require less memory and computational power.
Automatic Management:
Instead of manually converting data types for each operation, AMP automates this process. It intelligently determines which operations can safely be performed in lower precision without significantly impacting model accuracy, while keeping numerically sensitive operations in higher precision (FP32).
Benefits:
Faster Training: By using lower precision where appropriate, AMP reduces the computational workload, leading to faster training times.
Reduced Memory Usage: Lower precision data types require less memory, allowing for larger batch sizes or more complex models to be trained on the same hardware.
Improved Hardware Utilization: AMP takes advantage of specialized hardware capabilities (like Tensor Cores on NVIDIA GPUs) designed for efficient FP16 computations.