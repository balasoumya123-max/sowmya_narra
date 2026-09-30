# TensorFlow Lab: Tasks 1-4

A Jupyter notebook for introductory neural network and deep learning exercises.

## Contents

- Tensor manipulation, reshaping, transposition, and broadcasting
- Mean squared error vs. categorical cross-entropy
- MNIST training comparison: Adam and SGD
- MNIST training with TensorBoard logging

## Setup

Use Python 3.10 or newer. Create and activate a virtual environment, then install the dependencies:

```bash
python -m venv .venv
# Windows PowerShell: .venv\Scripts\Activate.ps1
# macOS/Linux: source .venv/bin/activate
python -m pip install -r requirements.txt
```

Open `Home_work1.ipynb` in Jupyter Notebook, JupyterLab, or Google Colab. Run the cells in order. The MNIST training tasks download the dataset through TensorFlow and may take several minutes, depending on your hardware.

For the TensorBoard section, run the notebook's TensorBoard cells after training. If TensorBoard is unavailable in your environment, install it with `python -m pip install tensorboard` and restart the notebook kernel.
