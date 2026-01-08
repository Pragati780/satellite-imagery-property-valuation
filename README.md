# Satellite Imagery–Based Property Valuation

This project implements a **multimodal regression pipeline** to predict residential property prices by combining **tabular real estate data** with **satellite imagery–based visual features**.

Satellite images are fetched using latitude–longitude coordinates, and **CNN-based embeddings (ResNet-18)** are extracted to capture neighborhood and environmental context. These embeddings are fused with structured features to improve traditional house price prediction models.

## Key Components
- Tabular baseline regression model
- CNN-based satellite image feature extraction
- Multimodal feature fusion
- Model explainability using Grad-CAM

## Data
- `data/train.xlsx`, `data/test.xlsx` – tabular housing data  
- Satellite images used only for feature extraction (not stored)

## Outputs
- `outputs/predictions.csv` – final price predictions  
- `image_embeddings.csv / .npy` – extracted visual embeddings

## Tech Stack
Pandas, NumPy, Scikit-learn, PyTorch, OpenCV, Matplotlib

## Project Details
- **Track:** Data Science  
- **Initiative:** CDC Open Project Initiative  
- **Industry Partner:** YHills  
- **Type:** Individual Project  

**Pragati Yadav**, IIT Roorkee
