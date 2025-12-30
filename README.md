# auto_imports_price_prediction
Best ML Model to predict auto mobile imports price using regression method

##  Problem Statement
Predict automobile prices based on technical specifications and categorical attributes using machine learning regression techniques. The goal is to understand key factors influencing vehicle pricing and build a reliable predictive model.

---

##  Dataset Overview
- Dataset contains automobile-related features such as engine specifications, dimensions, fuel type, and body style.
- Target variable: **Price**
- Includes both numerical and categorical attributes.

---

## Approach
1. **Data Cleaning & Preprocessing**
   - Handled missing values
   - Converted categorical features using encoding techniques
   - Scaled numerical features where required

2. **Exploratory Data Analysis (EDA)**
   - Analyzed feature distributions
   - Identified correlations between variables and price
   - Detected influential features affecting automobile pricing

3. **Feature Engineering**
   - Encoded categorical variables
   - Removed irrelevant or highly correlated features

4. **Model Building**
   - Trained and compared multiple regression models
   - Evaluated models using error-based metrics

5. **Model Evaluation**
   - Selected the best-performing model based on prediction accuracy and error reduction

---

##  Models Used
- Linear Regression  
- Decision Tree Regressor  
- Random Forest Regressor  
- (Any other model you used – optional)

---

##  Results
- Built a regression model capable of predicting automobile prices with reasonable accuracy
- Identified engine size, horsepower, and vehicle dimensions as major price-influencing factors

---

##  Key Insights
- Engine specifications and vehicle size strongly impact automobile pricing
- Ensemble models handle non-linear relationships better than linear models
- Proper feature encoding significantly improves regression performance

---

##  Tech Stack
- **Programming Language:** Python  
- **Libraries:** NumPy, Pandas, Scikit-learn  
- **Visualization:** Matplotlib, Seaborn  
- **Modeling:** Regression algorithm


---

##  How to Run the Project
1. Clone the repository:
   ```bash
   git clone https://github.com/Ranganath141/auto-imports-price-prediction.git

2. Navigate to the project directory

   cd Auto-price-imports

3. Install dependencies:

   pip install -r requirements.txt

4. Open and run the notebook

   Auto_price_imports.ipynb

 
Future Improvements :

Hyperparameter tuning for regression models

Feature selection using statistical methods

Model deployment using Flask or FastAPI

Integration with a simple web interface





 Author

Ranganath
Aspiring Data Scientist / AI-ML Engineer

GitHub: https://github.com/Ranganath141
   
