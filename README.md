# Hands-on Security and Privacy on ML/DL

This repository contains hands-on examples for exploring **security and privacy challenges in Machine Learning and Deep Learning**. It focuses on both **attacks** and **defenses**, helping learners understand how models can be manipulated and how to protect them.

## Features

- **FGSM (Fast Gradient Sign Method)**: Generate adversarial examples to attack models.
- **Adversarial Training**: Train models with adversarial samples to improve robustness.
- **Backdoor Attacks**: Inject triggers into training data and analyze model behavior.
- **I-FGSM (Iterative FGSM)**: Stronger adversarial attacks and iterative defense evaluation.
- **Multiple Defense Strategies**: Gaussian Noise, JPEG Compression, Defensive Distillation, Certified Defenses.
- **Evaluation & Visualization**: Compare model performance under clean and adversarial inputs, visualize example images.

## Getting Started

1. Clone the repository:
```bash
git clone https://github.com/your-username/Hands-on-Security-and-Privacy-on-ML-DL.git
cd Hands-on-Security-and-Privacy-on-ML-DL
```

2. Install dependencies:
```bash
pip install torch torchvision matplotlib tqdm pandas
```

3. Open the Jupyter Notebook and run the cells:
```bash
jupyter notebook
```

4. Explore attacks and defenses, visualize results, and modify parameters to see effects.

## Notebook Content

1. Preprocessing for ImageNet and MNIST datasets.

2. FGSM attacks and defense evaluation.

3. Backdoor attack implementation.

4. I-FGSM attack with multiple defenses (Gaussian, JPEG, Adversarial Training, Distillation, Certified Defense).

5. Comparison tables and example images to illustrate the effect of defenses.
