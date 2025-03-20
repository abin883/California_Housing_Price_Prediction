# California Housing Price Prediction 🏡💰

This project analyzes the **California Housing Dataset** to predict house prices based on various features. The process includes **Exploratory Data Analysis (EDA), feature engineering, and multiple machine learning models** such as Linear Regression, Ridge, Lasso, and Random Forest.

## 📚 Dataset Overview
The dataset contains information about housing prices in California, including features like median income, house age, and location coordinates.

## 📚 Files in this Repository
- **`California_Housing_EDA.ipynb`** - Jupyter Notebook with EDA, feature engineering, and model training.
- **`random_forest_model.pkl`** - Saved Random Forest model (tracked using Git LFS).
- **`.gitattributes`** - Configures Git LFS to handle large files.
- **`README.md`** - This file, describing the project details.

## 🛠️ Tools & Libraries Used
- **Python**: Pandas, NumPy, Matplotlib, Seaborn
- **Scikit-Learn**: Machine Learning models
- **Random Forest**: Final selected model
- **Git & GitHub**: Version control & project sharing

## 🚀 How to Use This Project
### 1. Clone this repository:
```bash
git clone https://github.com/abin883/California_Housing_Price_Prediction.git
```
### 2. Open the Jupyter Notebook:
Run `California_Housing_EDA.ipynb` to see the data analysis and model training steps.

### 3. Load the trained model and make predictions:
```python
import pickle
with open('random_forest_model.pkl', 'rb') as file:
    model = pickle.load(file)
```

## 📈 Model Performance
- **Final Model**: Random Forest Regressor
- **Best R² Score**: 0.814
- **Feature Importance Analysis** performed

## 👥 Connect with Me
If you have any questions or suggestions, feel free to reach out:
- **GitHub**: [abin883](https://github.com/abin883)
- **Kaggle**: [abinabraham883](https://www.kaggle.com/abinabraham883)

---
### ✨ Happy Coding! ✨

