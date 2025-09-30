# IFL Project

This repository contains the code for Federated Learning (FL) experiments involving Differential Privacy (DP) methods. The code is written in Python using PyTorch and is designed for use in Google Colab or local Python environments.

## Files

- `IFL_main.py`: Main script for running the Federated Learning experiments with Differential Privacy.
- `IFL_main.ipynb`: Jupyter Notebook version of the code.

## Dependencies

The following Python packages are required to run the code:

- numpy
- matplotlib
- torch
- scikit-learn
- scipy
- torchvision

## Installation

1. Clone the repository:
```bash
git clone [<repository-url>](https://github.com/Souvenir060/IFL_Project.git)
cd IFL_Project
```

2. Create and activate a virtual environment:
```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

3. Install dependencies:
```bash
pip install -r requirements.txt
```
## Quick Start

```bash
python IFL_main.py
```

Alternatively, you can open and run the IFL_main.ipynb notebook in Google Colab or Jupyter Notebook.

## Dataset

The dataset used in this project is **VRIC.zip**. Due to its large size, it is not included in this repository. You can download it from the following link:

https://qmul-vric.github.io/index.html

Once downloaded, place the dataset in the `data/` directory.

Alternatively, you can use any similar dataset, and the code will work as long as you adjust the paths accordingly.

The code will automatically load the dataset and partition it for Federated Learning experiments.
