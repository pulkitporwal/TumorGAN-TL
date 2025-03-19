# TumorGAN-TL: Enhancing Brain Tumor Detection with DCGAN-Generated MRI Images and Transfer Learning Models  

This repository contains the code and resources associated with the paper titled **"TumorGAN-TL: Enhancing Brain Tumor Detection with DCGAN-Generated MRI Images and Transfer Learning Models,"** which will be presented at **CODE-AI 2025** — *2nd International Conference on Data Science & Exploration in Artificial Intelligence*, held at **MAHE, Dubai** on **7th & 8th April 2025**. The conference is organized by the **Department of Information Technology, Manipal Institute of Technology, Manipal Academy of Higher Education (MAHE), Bengaluru** in collaboration with the **School of Engineering & IT (SoEIT), Manipal Academy of Higher Education (MAHE), Dubai, UAE**.  

## Project Overview  
This project investigates the use of Deep Convolutional Generative Adversarial Networks (DCGAN) to generate synthetic Brain MRI images and improve brain tumor classification using transfer learning models (ResNet, MobileNet, and EfficientNet). The study explores how synthetic data generation can enhance the accuracy of tumor detection models and optimize model performance using hyperparameter tuning with Optuna.  

---
## Directory Structure  
```
📂 TumorGAN-TL  
├── 📂 data/               # Dataset that have been used
├── 📂 models/             # Model files 
├── 📂 notebooks/          # Jupyter Notebook 
│   ├── dcgan.ipynb                       # Generation using DCGANs
│   ├── resnet_classification.ipynb       # Classification using ResNet  
│   ├── mobilenet_classification.ipynb    # Classification using MobileNet  
│   └── efficientnet_classification.ipynb # Classification using EfficientNet  
├── 📂 results/            # Generated images and Traning Loop Images
├── .gitignore             # Files to ignore  
├── README.md              # Project details  
└── requirements.txt       # Python dependencies  
```


## Dataset Details
- The dataset consists of real MRI brain scan images, categorized into two classes: yes and no.
- [Click Here to Download the Datasets](<https://www.kaggle.com/datasets/navoneel/brain-mri-images-for-brain-tumor-detection>)  
