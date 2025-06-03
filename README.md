# 🌍 Earthquake Prediction Model

A machine learning and deep learning-based project designed to predict earthquake magnitude and location using geospatial and temporal seismic data. This project helps in understanding seismic patterns and forecasting potential earthquake events with improved accuracy.

## 📊 Dataset

The dataset includes historical earthquake records with features such as:

- Date & Time  
- Latitude & Longitude  
- Depth  
- Magnitude  
- Region  
- Seismic Activity Pattern

## 🧠 Technologies & Tools

- Python 3.10+  
- Pandas, NumPy – Data processing  
- Matplotlib, Seaborn – Visualization  
- Scikit-learn – ML models and preprocessing  
- TensorFlow/Keras – Deep learning models  
- GridSearchCV – Hyperparameter tuning

## ⚙️ Project Workflow

1. **Data Collection & Preprocessing**
   - Cleaned and handled missing values
   - Engineered features from spatial and temporal data

2. **Exploratory Data Analysis (EDA)**
   - Visualized earthquake patterns, frequency distribution, and magnitude trends

3. **Model Development**
   - Trained ML models (Random Forest, SVR)
   - Built neural networks using TensorFlow/Keras
   - Applied GridSearchCV for tuning hyperparameters

4. **Model Evaluation**
   - Evaluated using metrics like RMSE, MAE, and accuracy
   - Tested for magnitude and location prediction capabilities

## 📈 Results

- **RMSE (Magnitude Prediction):** ~0.3  
- **Best Performing Model:** Deep Neural Network  
- **Key Insight:** Depth and region play a significant role in magnitude prediction

## ✅ How to Run

```bash
# Clone the repo
git clone https://github.com/yourusername/earthquake-prediction-model.git
cd earthquake-prediction-model

# Install dependencies
pip install -r requirements.txt

# Run a Jupyter notebook
jupyter notebook notebooks/model_training.ipynb
