# 📚 Simple-ViT-Implementation
This repo offers simple implementationi ViT (Vision Transformer) from scratch using PyTorch.

Find elaborated implementation [here](https://medium.com/@bskkim2022/paper-reimplementation-vit-vision-transformer-eed3ad20dfe7).


## 🚀 Getting started

Please follow the insturction below.

```bash
git clone https://github.com/bskkimm/Simple-ViT-Implementation.git
conda create -n ViT python=3.10 -y
conda activate ViT
pip install -r requirements.txt
```
Then, implement ViT step by step using `tutorial_from_scratch.ipynb`

## 📊 Results

| Model       | Dataset  | Train Accuracy | Test Accuracy | GPU Used        | Training Time |
|-------------|----------|----------------|---------------|------------------|----------------|
| ViT-B/12    | CIFAR-10 | 98.88%         | 77.40%        | RTX 4070 Laptop  | 2.0 hours       |

### 🔍 Attention Map Visualization

Due to the small image size in CIFAR-10, I implemented attention map visualization on the **Food-101** dataset instead, which offers higher-resolution samples more suitable for visual interpretability.

<div align="center">
  <img width="503" alt="ViT Attention Map on Food101" src="https://github.com/user-attachments/assets/7226dd65-e77b-4e28-a1bd-073de19e5720" />
</div>


