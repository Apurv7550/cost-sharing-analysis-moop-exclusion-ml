
# Cost-Sharing & MOOP Exclusion Prediction (Healthcare Plans)

This project analyzes U.S. health plan benefits to understand **cost-sharing differences** (copay/coinsurance) between **in-network vs out-of-network** services, and builds ML models to predict whether a service is **excluded from Maximum Out-of-Pocket (MOOP)** limits.

## What’s inside
- **EDA**: copay/coinsurance patterns, limits, and service-level trends  
- **Regression**: predict **Out-of-Network Copay**  
- **Classification**: predict **MOOP Exclusion** for in-network and out-of-network

## Models used
- Random Forest
- Gradient Boosting
- XGBoost (for classification)

## Files in this repo
- `Insurance_analysis_EDA.ipynb` — exploratory analysis and visuals  
- `costsharing_ML1.ipynb` — regression (CopayOutofNet prediction)  
- `moopExclusion_ML2.ipynb` — classification (MOOP exclusion prediction)  
- `Capstone_Project_Report.docx` — full report  
- `Capstone Final Presentation.pptx` — slides  

## How to run
1. Install libraries:
   ```bash
   pip install pandas numpy matplotlib scikit-learn xgboost jupyter
2. Put the dataset in a data/ folder (or update the file path inside the notebooks).

3. Run notebooks in this order:
a.Insurance_analysis_EDA.ipynb
b. costsharing_ML1.ipynb
c. moopExclusion_ML2.ipynb
