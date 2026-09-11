# CCPG: Category-Conditioned Prior Guidance for Cross-Domain Few-Shot Hyperspectral Image Classification

## Requirements

The current requirements are:

* NumPy
* SciPy
* scikit-learn
* h5py
* Matplotlib
* PyTorch
* TensorBoard
* Transformers
* PEFT

## 

## Training

Run the desired dataset entry point from the repository root.

### Indian Pines

```bash
python train\\\_ccpg\\\_indian\\\_pines.py
```

### Salinas

```bash
python train\\\_ccpg\\\_salinas.py
```

### University of Pavia

```bash
python train\\\_ccpg\\\_university\\\_of\\\_pavia.py
```

### Houston

```bash
python train\\\_ccpg\\\_houston.py
```

Each entry point loads its default configuration from `configs/`.

