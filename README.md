# Medical Insurance Cost Prediction

This project uses machine learning to predict medical insurance charges based on demographic and health-related factors. It demonstrates data preprocessing, visualization, model training, and evaluation using regression techniques.

##  Problem Statement

Insurance companies use demographic data and health indicators to estimate a person's medical insurance charges. The goal of this project is to build a predictive model using a dataset containing features like age, sex, BMI, number of children, smoking status, and region.

##  Technologies Used

* Python 3
* Pandas
* NumPy
* Matplotlib & Seaborn (for visualization)
* Scikit-learn (for machine learning)

##  Dataset

The dataset includes the following features:

* `age`: Age of primary beneficiary
* `sex`: Insurance contractor gender
* `bmi`: Body mass index
* `children`: Number of children covered by health insurance
* `smoker`: Smoking status
* `region`: Residential area in the US
* `charges`: Individual medical costs billed by health insurance

##  Key Steps

1. **Importing Libraries**
2. **Loading the Dataset**
3. **Exploratory Data Analysis (EDA)**
4. **Data Preprocessing**
5. **Feature Engineering (if any)**
6. **Train-Test Split**
7. **Model Training (Linear Regression)**
8. **Model Evaluation (R², MAE, MSE, RMSE)**

##  Model Used

* **Linear Regression**: A baseline model used to fit and predict medical charges.
* Performance metrics such as R² score and RMSE are used for evaluation.

##  Results

The model shows how features such as smoking and BMI strongly influence medical charges. Proper feature selection and data normalization help improve predictive accuracy.

##  How to Run

1. Clone this repository:

   ```bash
   git clone https://github.com/yourusername/medical-insurance-cost-prediction.git
   ```
2. Navigate to the project directory:

   ```bash
   cd medical-insurance-cost-prediction
   ```
3. Install required libraries:

   ```bash
   pip install -r requirements.txt
   ```
4. Run the notebook:
   Open `Medical insurance cost prediction.ipynb` in Jupyter Notebook or JupyterLab.

##  Future Work

* Incorporate advanced regression models (Random Forest, XGBoost)
* Hyperparameter tuning
* Deploy the model via a web application (Flask/Streamlit)
