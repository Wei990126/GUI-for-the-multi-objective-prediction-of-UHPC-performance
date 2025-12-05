This repository contains the original supplementary materials and GUI source code. For inquiries regarding the original manuscript, please contact weizhang01@tongji.edu.cn. If you find these resources useful, please cite the original publication.

The GUI is structured around three core panel modules:

(1) Data Input Module
Configures 21 feature parameter input fields covering key variables such as raw material quantities, specimen dimensions, and curing conditions. The module includes dynamic range validation to ensure all entries comply with predefined constraints.

(2) Multi‑Objective Output Module
Displays real‑time computational results across five optimization dimensions, including performance metrics and cross‑scale environmental indicators.

(3) Control Unit Module
Integrates functional buttons (“Predict”, “Clear”, “Save”, “Exit”). Clicking “Predict” triggers the immediate display of prediction outcomes corresponding to the entered parameters.

Reproducibility Checklist：

(1) Environment and Core Libraries: 

(2) GUI Framework: tkinter version 8.6  

(3) Numerical Computation: numpy version 1.23.5  

(4) Model Persistence: joblib version 1.4.2    

(5) Gradient Boosting (CatBoost): catboost version 1.2.7 

(6) Gradient Boosting (XGBoost): xgboost version 2.1.4
