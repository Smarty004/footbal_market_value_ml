# Football Player Market Value Prediction

This is a machine learning project developed for the Machine Learning course (30412) at Bocconi University.

The objective is to predict the market value of football players (in Euros) using a dataset of over 15,000 players and more than 70 features, including technical attributes, physical stats, and other relevant data.

We tested multiple models and selected LightGBM as the final one. We used:
- Data cleaning and preprocessing  
- Feature engineering  
- Log transformation of the target variable  
- Optuna for hyperparameter tuning  
- SHAP for model interpretation  

The final model achieved a Root Mean Squared Error (RMSE) of approximately **597,000 Euros** on the test set.

---

## How to Run

1. **Clone the repository**
```bash
git clone https://github.com/Smarty004/footbal_market_value_ml.git
cd footbal_market_value_ml
```

2. **Install the required libraries**
```bash
pip install -r requirements.txt
```

3. **Launch Jupyter Notebook**
```bash
jupyter notebook
```

4. **Open the notebook**
```
notebooks/final_notebook.ipynb
```

5. **Run all the cells** in order to reproduce the results.

---

## Team

- **Zhansaya Akhmetova** 
- **Albina Cyuzuzo Ntivuguruzwa** 
- **Martina Favata**  
- **Jakob Lutz** 
- **Martina Russo** 
