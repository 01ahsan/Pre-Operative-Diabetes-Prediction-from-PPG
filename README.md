# Pre-Operative Diabetes Prediction from Photoplethysmography (PPG)


---

## Overview

This repository contains code to predict preoperative diabetes from Photoplethysmography (ppg) using Viotaldb dataset 
---

## ⚙️ Key Features

-  1 s PPG segmentation (100 Hz)
- Six deep learning models:
  - MLP  
  - CNN-LSTM  
  - Transformer Encoder  
  - ResNet-1D  
  - GRU  
  - LSTM + Attention
- Multi-metric evaluation: Accuracy, Precision, Recall, F1, Specificity

---

## 📁 Repository Structure

├── data collection/
│ └── data_collection_from_Vitaldb.ipynb
├── data preprocessing/
│ ├── data_filtering.ipynb
│ ├── data_repair.ipynb
│ └── remove_invalid_data.ipynb
├── segmentation/
│ └── segmentation.ipynb
├── model running/
│ ├── MLP.ipynb
│ ├── CNN_LSTM.ipynb
│ ├── GRU.ipynb
│ ├── ResNet1D.ipynb
│ ├── Transformer.ipynb
│ └── lstm_attention.ipynb
└── README.md


## Dataset
- Vitaldb dataset https://vitaldb.net/dataset
- Lee HC, Park Y, Yoon SB, Yang SM, Park D, Jung CW. VitalDB, a high-fidelity multi-parameter vital signs database in surgical patients. Sci Data. 2022 Jun 8;9(1):279. doi: 10.1038/s41597-022-01411-5. PMID: 35676300; PMCID: PMC9178032.
