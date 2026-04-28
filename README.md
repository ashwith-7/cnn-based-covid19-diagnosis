# CNN-Based COVID-19 Diagnosis

## Overview
This project performs automated COVID-19 diagnosis from radiographic images using deep learning and transfer learning techniques. The framework employs VGG16 and VGG19 architectures for feature extraction and classification, with comparative evaluation against baseline machine learning models.

The goal is to accurately classify radiographic images for COVID-19 diagnosis and support automated medical image analysis.

## Publication
This repository contains the implementation associated with our Springer conference publication.

**DOI:** 10.1007/978-981-95-3489-0_26

**Paper Link:**  
https://link.springer.com/chapter/10.1007/978-981-95-3489-0_26

## Dataset
The dataset used in this project is the **COVID-19 Radiography Database**, containing radiographic images for COVID-related classification.

Dataset source:  
https://www.kaggle.com/datasets/tawsifurrahman/covid19-radiography-database

## Features
- Data Preprocessing:
  - Image resizing and normalization  
  - Data augmentation  
  - Dataset preparation for training and validation

- Model Training:
  - VGG16 transfer learning model  
  - VGG19 transfer learning model  
  - CNN-based classification framework

- Comparative Analysis:
  - Support Vector Machine (SVM) baseline  
  - Logistic Regression baseline  
  - Naive Bayes baseline

- Model Evaluation:
  - Accuracy evaluation  
  - Confusion matrix  
  - Classification metrics  
  - Performance comparison

## Dependencies
Make sure the following Python libraries are installed:

```python
pip install tensorflow keras numpy pandas matplotlib scikit-learn
```

Or install:

```python
pip install -r requirements.txt
```

## How to Run
1. Clone the repository:

```bash
git clone https://github.com/ashwith-7/cnn-based-covid19-diagnosis.git
cd cnn-based-covid19-diagnosis
```

2. Launch Jupyter Notebook:

```bash
jupyter notebook coviddetfinal.ipynb
```

3. Run all cells to train and evaluate the model.

## Results
- The proposed deep learning framework demonstrates strong performance for automated COVID-19 classification.
- Evaluation includes:
  - Classification accuracy  
  - Confusion matrix visualization  
  - Comparative analysis with machine learning baselines

## Repository Contents
```bash
coviddetfinal.ipynb      # Main implementation notebook
requirements.txt         # Dependencies
README.md                # Documentation
```

## Citation
If you use this code, please cite:

```bibtex
@incollection{ashwith2025covid,
doi={10.1007/978-981-95-3489-0_26},
booktitle={Proceedings of ICCCT 2025},
publisher={Springer},
year={2025}
}
```

## License
This project is released under the MIT License.

## Authors
Mrinal Ashwith S P
