# Simple-ViT-Implementation
This repo offers simple implementationi ViT (Vision Transformer) from scratch using PyTorch.


## Guidance

Please follow the insturction below.

```bash
git clone https://github.com/bskkimm/Simple-ViT-Implementation.git
conda create -n ViT python=3.10 -y
conda activate ViT
pip install -r requirements.txt
```
Then, implement ViT step by step using `tutorial_from_scratch.ipynb`

## Result

| Model         | Dataset   | Train Accuracy | Test Accuracy | GPU Used       | Training Time     |
|---------------|-----------|----------------|---------------|----------------|-------------------|
| ViT-B/{12} | CIFAR-10 | 98.88%         | 77.40%        | RTX 4070 Laptop | 2.0 hours         |
