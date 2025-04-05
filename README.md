# 🧠 Restricted Boltzmann Machines  

![Python](https://img.shields.io/badge/python-3.11%2B-blue.svg)
![Framework](https://img.shields.io/badge/framework-PyTorch-red)

---

## 📝 Overview
- Implementation from scratch of a RBM to generate and denoise one-hot-enoded sequences of proteins 

---

## 🗂️ Repository Structure
- RBM.ipynb contains the dataset import, the model definition and training
- DATA_b directory contains the dataset at different level of noise

--- 

## 📊 Results

![Generated Samples](rbm.png "rbm")  
*Representation of the RBM weights after training*

![Generated Samples](data_proteins.png "denoised data") 
*On top: noised data. Below: denoised data*

![Generated Samples](losses.png "losses")   
*Energy and Log-Likelihood evolution during training*

