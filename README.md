# Energy-Based OOD Detection for Forest Recovery Monitoring  

## Overview  
This repository implements an energy-based **out-of-distribution (OOD) detection** framework for forest recovery monitoring using remote sensing data. The method combines:  
- A frozen **DINOv2 Vision Transformer** for feature extraction  
- **Linear Discriminant Analysis (LDA)** for interpretable dimensionality reduction  
- **Energy-based scoring** to detect anomalies (e.g., invasive species, degraded patches)  

---

## Key Features  
| Feature | Description |  
|---------|-------------|  
| **Energy-Based OOD Detection** | Flags anomalies using cluster distances in LDA space |  
| **Multispectral Band Analysis** | Evaluates pseudo-RGB, visible-only, and vegetation-sensitive bands |  
| **No OOD Labels Required** | Unsupervised thresholding via ROC analysis |  
| **Pretrained Backbone** | Uses frozen DINOv2 for efficient feature extraction |  
