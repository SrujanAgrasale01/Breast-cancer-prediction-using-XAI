 Breast Cancer Prediction using Explainable AI

> Best Paper Presentation Award — IEEE International Conference ETFI-2026, DES Pune University  
> Track: AI-Powered Systems and Intelligent Measurements

 Overview

A machine learning system that predicts breast cancer risk from patient diagnostic data, 
integrated with **Explainable AI (XAI)** techniques to make predictions interpretable for medical professionals.
Built to bridge the gap between ML accuracy and clinical trust.

Key Features

- Predicts malignant vs benign tumors using patient data
- Integrates **SHAP (SHapley Additive exPlanations)** for global feature importance
- Hyperparameter tuning for optimized model performance
- Evaluated using Precision, Recall, F1-Score, and AUC-ROC metrics

Tech Stack

| Category | Tools |
|----------|-------|
| Language | Python |
| ML Library | Scikit-learn |
| XAI | SHAP |
| Data Handling | Pandas, NumPy |
| Visualization | Matplotlib, Seaborn |
| Environment | VS code |

 Model Performance

| Metric | Score |
|--------|-------|
| Precision | High |
| Recall | High |
| AUC-ROC | > 0.95 |

 Explainability — Why It Matters

Traditional ML models are "black boxes" — doctors can't trust predictions they can't understand.  
This project uses:
- **SHAP** → Shows which features globally drive cancer risk predictions

 Project Structure

breast-cancer-explainable-ai/
│
├── data/                  # Dataset files
├── notebooks/             # Jupyter notebooks
├── models/                # Saved ML models
├── explainability/        # SHAP outputs
├── requirements.txt       # Dependencies
└── README.md


## How to Run

```bash
# Clone the repository
git clone https://github.com/SrujanAgrasale01/Breast-cancer-prediction-using-XAI.git

# Navigate to the project folder
cd breast-cancer-prediction-using-xai

# Install Python dependencies
pip install -r requirements.txt

# Start the backend
python app.py

# Start the frontend (in a new terminal)
cd Frontend
npm install
npm start
```

## Deploy on Render

1. Push this project to a GitHub repository.
2. In Render, choose **New > Blueprint** and select the repository.
3. Render will use `render.yaml` to create the API and frontend services.

The frontend is configured to use `https://breast-cancer-api.onrender.com` in production. If Render assigns a different API URL, set `REACT_APP_API_URL` on the frontend service and redeploy it.

 Recognition

- 🥇 **Best Paper Presentation** — ETFI-2026, IEEE International Conference
- Institution: DES Pune University | Feb 2026
- Paper: *Breast Cancer Prediction using Explainable AI*


 Author

**Srujan Agrasale**  
BE — Artificial Intelligence & Machine Learning  
[LinkedIn](https://www.linkedin.com/in/srujan-agrasale-421870280/) | [GitHub](https://github.com/SrujanAgrasale01)
