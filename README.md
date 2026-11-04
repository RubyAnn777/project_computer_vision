# project_computer_vision

Photomosaics with OpenCV, NumPy and SciPy.

| Stage | Notebook | Status |
|---|---|---|
| 1. Hexagonal tiles | [`hexagonal_photomosaic.ipynb`](hexagonal_photomosaic.ipynb) | guided walkthrough |
| 2. Random (non-grid) layout | – | to do |

## Data

Put the data next to the notebook, with the same layout as in class:

```
data/
├── collection/      # tiles, all the same size (png by default)
└── test-images/     # target images, e.g. ferrari.jpeg
```

The paths are set in the "Configuration" cell of the notebook. If `data/` is missing, the notebook
generates a small synthetic demo dataset in `data/demo/` so every cell still runs.

## Requirements

```
pip install numpy opencv-python scipy matplotlib jupyter
```
