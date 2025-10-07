# Age Group Prediction using Health Data

## Project Overview
This project is a **machine learning pipeline** designed to classify individuals into **Adult or Senior** age groups based on their health and lifestyle metrics. The goal is to demonstrate end-to-end data analysis, preprocessing, and predictive modeling using Python.

## Features
- Data cleaning and preprocessing including **KNN imputation**, outlier correction, and **Box-Cox/log transformations** for normalization.
- Exploratory Data Analysis (EDA) with **NumPy, Pandas, Matplotlib, and Seaborn**.
- Model training and evaluation with **Logistic Regression, Random Forest, and XGBoost**.
- Hyperparameter tuning using **GridSearchCV** to maximize **macro F1-score**.
- Ready-to-use Python scripts and Jupyter Notebook for demonstration.

## Technologies Used
- **Languages:** Python 3.x  
- **Data Analysis & Visualization:** NumPy, Pandas, Matplotlib, Seaborn  
- **Machine Learning:** scikit-learn, XGBoost  
- **Development Tools:** Jupyter Notebook, VS Code, Git, GitHub  

## Installation
1. Clone the repository:
    ```bash
    git clone https://github.com/<your-username>/<your-repo>.git
    ```
2. Navigate into the project directory:
    ```bash
    cd <your-repo>
    ```
3. Install dependencies:
    ```bash
    pip install -r requirements.txt
    ```

## Usage
1. Open `Age_Group_Prediction.ipynb` in **Jupyter Notebook** or **VS Code**.  
2. Run all cells sequentially to preprocess the data, train models, and evaluate results.  
3. You can modify the dataset or models to experiment with predictions.

## Dataset
- Health and lifestyle metrics dataset (included in `data/` folder or instructions to download).  
- Columns may include: Age, Weight, Height, Blood Pressure, Activity Level, etc.  

## Results
- Achieved classification into **Adult or Senior** with optimized macro F1-score.  
- Models include **Logistic Regression, Random Forest, and XGBoost**.  
- Visualizations include feature distributions and correlation heatmaps.

## Project Structure
Age-Group-Prediction/
│
├── data/ # Dataset files
├── Age_Group_Prediction.ipynb # Main Jupyter notebook
├── requirements.txt # Python dependencies
├── README.md # Project documentation
└── outputs/ # Model evaluation plots and results

## Key Achievements
- Developed a **complete ML workflow** from preprocessing to modeling.  
- Implemented **feature transformations and imputation** techniques to handle missing/outlier values.  
- Tuned multiple models for **optimal classification performance**.  
