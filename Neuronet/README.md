# NeuroNet: RNA-Seq Cell Type Classifier

A supervised deep learning project that leverages RNA-Seq gene expression data to classify cell types using neural networks. Built as part of a biomedical machine learning portfolio to showcase real-world data handling, model tuning, and explainability in high-dimensional biological datasets.

---

## Project Overview

Cell-type classification from RNA-Seq data is critical for understanding disease states, tissue heterogeneity, and treatment response. This project walks through the development of a neural network that ingests transcriptomic profiles and outputs predicted cell types.

Key steps include:

- Data ingestion and preprocessing  
- Baseline neural network development  
- Model performance evaluation and tuning  
- Explainability of feature importance  

---

## Project Structure
neuronet-cell-classifier/
│
├── data/ # Raw and cleaned RNA-Seq data
├── notebooks/
│ ├── 01-data-prep.ipynb # Load, clean, and normalize RNA-Seq data
│ ├── 02-baseline-model.ipynb # Build and evaluate initial model
│ └── 03-model-tuning.ipynb # Hyperparameter tuning & architecture tweaks
├── src/ # Utility scripts for training/evaluation
├── outputs/ # Saved models, results, and plots
├── requirements.txt # Python dependencies
├── README.md
└── .gitignore


---

## Technologies Used

- Python (3.10+)  
- TensorFlow / Keras or PyTorch  
- Pandas, NumPy  
- Scikit-learn  
- Matplotlib / Seaborn  
- SHAP or LIME *(optional, for explainability)*  

---

## Key ML Concepts

- Feature normalization  
- Neural network architecture design  
- Overfitting prevention (Dropout, BatchNorm)  
- Confusion matrix and classification reports  
- Cross-validation and hyperparameter tuning  
- Feature importance for biological insights  

---

## Future Directions

- Add CNN or transformer-style models for alternative architectures  
- Explore multi-label classification for cells with mixed identities  
- Wrap in a Streamlit dashboard for real-time inference  
- Deploy model via REST API  

---

## Credits & Data Sources

Data sourced from publicly available repositories such as [GEO](https://www.ncbi.nlm.nih.gov/geo/), [Kaggle](https://www.kaggle.com/), or simulated RNA-Seq datasets. Final dataset details TBD.

