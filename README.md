# Heart_Disease_Prediction_Project_Using_Logistic_Regression

**Project Description**
The aim of this project is to develop a logistic regression model to predict the presence of heart disease in patients based on a set of clinical and demographic features. By analyzing these features, the model will help healthcare professionals in diagnosing heart disease early, enabling timely interventions and potentially saving lives. The project involves preprocessing the data, performing exploratory data analysis, building and tuning the model, and evaluating its performance to ensure accuracy and reliability.

**Dataset Description: heart1.csv**
The heart1.csv dataset contains 13 columns that represent various attributes related to the health of patients. The dataset includes the following features:

**age:** Age of the patient (years).
    
**sex:** Gender of the patient (1 = male, 0 = female).
    
**cp:** Chest pain type (categorical):
        
1: Typical angina.
    
2: Atypical angina.
    
3: Non-anginal pain.
    
4: Asymptomatic.
    
**trestbps:** Resting blood pressure (mm Hg) at the time of hospital admission.
    
**chol:** Serum cholesterol level (mg/dl).
    
**fbs:** Fasting blood sugar > 120 mg/dl (1 = true, 0 = false).
    
**restecg:** Resting electrocardiographic results (categorical):
        
0: Normal.
    
1: Having ST-T wave abnormality.
    
2: Showing probable or definite left ventricular hypertrophy.
    
**thalach:** Maximum heart rate achieved.
    
**exang:** Exercise-induced angina (1 = yes, 0 = no).
    
**oldpeak:** ST depression induced by exercise relative to rest.
    
**slope:** Slope of the peak exercise ST segment (categorical):
        
1: Upsloping.
    
2: Flat.
    
3: Downsloping.
    
**ca:** Number of major vessels (0-3) colored by fluoroscopy.
    
**target:** Target variable indicating heart disease (1 = presence, 0 = absence).

**Installation**
To run the project in your Jupyter Notebook or Google Colab, follow these steps:

1. **Clone the repository**:
   - If using Jupyter Notebook:
     ```bash
     !git clone  https://github.com/DivyaSriThatikonda/Heart_Disease_Prediction_Project_Using_Logistic_Regression
     ```
   - If using Google Colab:
     - Open a new Colab notebook.
     - Execute the following code cell:
       ```python
       !git clone https://github.com/DivyaSriThatikonda/Heart_Disease_Prediction_Project_Using_Logistic_Regression
       ```
2. **Install dependencies**:
   - Run the following code cell in the notebook to install the required libraries:
     ```python
     !pip install numpy pandas matplotlib seaborn scikit-learn
     ```
**2.Install dependencies:**
Run the following code cell in the notebook to install the required libraries:

!pip install numpy pandas matplotlib seaborn scikit-learn

**3.Access the dataset:**
The insurance.csv dataset is already included in the repository.

**4.Tools used:**

**Numpy**: Used for numerical computations and array manipulation.

**Pandas** :Used for data manipulation, analysis, and cleaning.

**Seaborn** : Used for data visualization and statistical plotting.

**Scikit-learn:** Used for building and evaluating the linear regression model. -Descriptive Statistics: Used to summarize and analyze the dataset, including measures such as mean, median, standard deviation, and correlation coefficients.

**Matplotlib** : Used for data visualization.

**Results and Performance:**
This project aimed to develop a logistic regression model to predict heart disease presence based on medical and demographic features. With an accuracy of 84% on the training data and 83.6% on testing, the model effectively distinguishes between individuals with and without heart disease. Its interpretability makes it suitable for clinical settings, offering valuable insights for early detection and intervention in heart disease cases.
