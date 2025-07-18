# $N^2$ Bench Downloaded Data
This repo contains the downloaded and masked data files for the $N^2$ bench introduced in the $N^2$ [repository](https://github.com/aashish-khub/NearestNeighbors).

## Usage
After downloading, the mask and data files can be loaded using numpy:
```python
import numpy as np
data = np.load('path/to/file.npy', allow_pickle=True)
```
Ensure that `allow_pickle=True` to avoid complications.
