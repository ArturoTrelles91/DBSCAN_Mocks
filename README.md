# DBSCAN Mocks – Cone Experiments

This repository contains practical experiments using the **DBSCAN** clustering algorithm,
applied to synthetic cone-like particle distributions.

The focus is on:
- Density-based clustering
- Noise detection
- Parameter sensitivity (`eps`, `min_samples`)
- Spatial vs velocity-space clustering

---
histof_pruebas_con_vrho_0.23_662.png

### Distribution of data previous to apply DBSCAN
![Histogram of particles in epsilon for KNN](histof_pruebas_con_vrho_0.23_662.png)
*This gives separation between groups before apply DBSCAN, to get the hyperparameter epsilon*

---

## 📊 DBSCAN Clustering Results

### DBSCAN in Position Space
![DBSCAN position clustering](DBSCAN_pos_con_vx_0.02_390.png)
*DBSCAN clustering applied in position space. Different colors represent detected clusters,
while noise points are shown separately.*

---

### DBSCAN in Velocity Space
![DBSCAN velocity clustering](DBSCAN_vel_0.02_con_vx_400.png)
*DBSCAN clustering applied in velocity space, highlighting how velocity information
affects cluster separation.*

---

## 🔍 Intermediate Particle Projections

### X–Y Projection
![XY projection](plot1_h+s_xy.png)
*Projection of particle distribution in the X–Y plane.*

---

### X–Z Projection
![XZ projection](plot1_h+s_xz.png)
*Projection of particle distribution in the X–Z plane, showing cone structure.*

---

## 🧪 Individual Particle Selections

![Particle vx = -1](part_-1_con_vx_0.02_400.png)
*Particles selected for negative velocity component.*

![Particle vx = 0](part_0_con_vx_0.02_400.png)
*Particles selected for zero velocity component.*

![Particle vx = +1](part_1_con_vx_0.02_400.png)
*Particles selected for positive velocity component.*

---

## 📓 Notebooks

- `Reescaled_with_poisson_10_1.ipynb`  
- `Reescaled_with_poisson_10_1_snap_1.ipynb`  

These notebooks contain:
- Dataset generation
- Feature rescaling
- DBSCAN execution
- Visualization routines

---

## 🛠️ Tech Stack

- Python
- NumPy
- scikit-learn
- Matplotlib
- Jupyter Notebook

---

> **Note:** This repository is intended for academic and exploratory purposes.
