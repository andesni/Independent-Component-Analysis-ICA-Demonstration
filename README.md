# Independent-Component-Analysis-ICA-Demonstration
This Python script showcases the application of Independent Component Analysis (ICA) using sklearn.decomposition.FastICA to separate mixed signals into their original independent sources.

## Overview
The code generates two synthetic signals (sinusoidal and sawtooth), mixes them using a predefined mixing matrix, and then applies ICA to recover the originals. It also demonstrates ICA's performance on noisy data by adding random noise to the mixed signals. Visualizations are created using matplotlib to compare original, mixed, and recovered signals, with and without noise.

### Key Features
- Signal generation with `numpy` and `scipy.signal`
- ICA implementation via `sklearn`
- Visualization of results with `matplotlib`
- Signal normalization for consistent amplitude scaling
- Demonstration of ICA with noisy data

## Requirements
- Python 3.x
- Libraries: `numpy`, `matplotlib`, `sklearn`, `scipy`

Install dependencies with:
```
bash
pip install numpy matplotlib scikit-learn scipy
```

### Screenshots
<img width="594" alt="Screenshot 2025-03-04 at 11 56 58 AM" src="https://github.com/user-attachments/assets/adf344b1-6b3d-439c-92f8-6598ea574102" />

<img width="594" alt="Screenshot 2025-03-04 at 11 57 23 AM" src="https://github.com/user-attachments/assets/e562c2f9-65a2-47c4-8099-d3f421cad0d5" />
