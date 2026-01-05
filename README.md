# PDE-AdamW-LRMP experiments 

- PDE-AdamW-LRMP (plain / Saitoh)
- AdamW-LRMP (preconditioner smoothing baseline)
- AdamW + GradSmooth (LSGD) baseline (gradient smoothing)
- Multiple datasets/models (MNIST LogReg/MLP/CNN, FashionMNIST CNN, CIFAR-10 ConvNet/ResNet18, IMDB logreg)
- Optional multi-seed runs and longer budgets
- Optional ablations (LRMP off/const, Young-stability off)

## Install
```bash
pip install -r requirements.txt
```

## Run all (default)
```bash
python run_all.py
```

Results are written under `results/` by default.

Tran Kim Huong : maintainer
