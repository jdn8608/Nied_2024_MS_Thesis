# Thesis Title: Evaluating the Capabilities of Supervised Machine Learning Techniques for Operational Over-Ocean Cloud Masking with Satelitte Imagers  
## Description:  
This repository contains the code and data for my thesis on the application of machine learning techniques to enhance cloud detection in satellite imagery. The focus is on evaluating various supervised machine learning models, including convolutional neural networks (CNNs), Dense Neural Networks (DNNs), & Random Forests (RFs), for semantic segmentation and cloud masking.  

We aim to compare performative enhancements of CNNs that utilize texture over spectral-only ML models. Furthermore, we focus on the aspects and neccessary requirements to use these methods globally and operationally.  

## Structure  
The following is the layout of the code base
```bash
├── notebooks                   # All code used within the thesis to create models or plots
├── MOD35 datasets              # Spreadsheets to retrieve the MODIS and MOD35 for training/testing data 
├── RCCM datasets               # RCCM-nadir files for training/testing data
├── requirements.txt            # Dependencies for all notebooks (besides mapping)
├── requirements_mapping.txt    # Dependencies for mapping plots
└── README.md
```  
## Install Dependencies:
Install main conda environment: 
```bash
conda create --name <env> --file requirements.txt
```

Install secondary conda environment for plotting maps: 
```bash
conda create --name <env> --file requirements_mapping.txt
```
## Contact
For any questions or concerns regarding this repository, please contact me via email at jdnied2@illinois.edu
