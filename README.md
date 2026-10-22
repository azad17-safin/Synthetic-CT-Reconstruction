# 🩻 Synthetic CT Reconstruction via Radon & Inverse Radon Transform

A biomedical image processing project demonstrating the fundamental physics of X-ray Computed Tomography (CT) scanning and mathematical image reconstruction. 

## 🔬 How It Works
1. **The Physics (Radon Transform):** Simulates a rotating X-ray source and sensor around a cross-sectional tissue phantom (`shepp_logan_phantom`) to collect parallel line integrals, generating a raw **Sinogram**.
2. **The Reconstruction (Inverse Radon Transform):** Applies Filtered Backprojection (FBP) with a **ramp filter** to convert the angular sinogram data back into a high-resolution spatial image.

## 🛠️ Tech Stack
* **Language:** Python
* **Libraries:** `scikit-image` (`radon`, `iradon`), `numpy`, `matplotlib`

## 🚀 Run in Colab
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/YOUR-USERNAME/Synthetic-CT-Reconstruction/blob/main/Synthetic_CT_Reconstruction.ipynb)
