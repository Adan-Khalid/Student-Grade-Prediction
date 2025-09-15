# 🎓 Student Grade Prediction Project

## 📌 Overview
This project predicts student grades using machine learning techniques. By analyzing various student-related features, the model provides insights into academic performance and helps identify factors that influence final grades.

## 🎯 Objective
The goal is to build and evaluate predictive models that estimate a student's final grade (**G3**) based on other academic and personal attributes from the dataset.

## 📊 Dataset
- **Source**: student.csv (included in the repository)
- **Target Variable**: `G3` (final grade)
- **Features**: Multiple academic and demographic attributes related to student performance.

## 🔍 Methodology
1. **Data Exploration & Preprocessing**
   - Loaded and inspected dataset
   - Summary statistics and correlation analysis
   - Visualized relationships between variables

2. **Model Training**
   - Implemented multiple regression models:

     - Linear Regression
     - Ridge Regression
     - Random Forest Regressor

3. **Evaluation Metrics**
   - Mean Absolute Error (MAE)
   - Mean Squared Error (MSE)
   - Root Mean Squared Error (RMSE)
   - R² Score

4. **Visualization**
   - Correlation heatmap
   - Predicted vs Actual grade comparison

5. **Model Saving**
   - The best-performing model is saved using `joblib` for future use.

## 📈 Results & Insights
- Models were compared based on multiple error metrics.
- Random Forest often outperforms linear methods by capturing non-linear relationships.
- Evaluation results are summarized in a performance table within the notebook.

## 🛠 How to Run
1. Clone this repository
   ```bash
   git clone <repo-link>
   cd Student_Grade_Prediction_Project
   ```
2. Install dependencies
   ```bash
   pip install -r requirements.txt
   ```
3. Open the Jupyter Notebook
   ```bash
   jupyter notebook Student_Grade_Prediction_Project_Enhanced.ipynb
   ```

## 🚀 Future Improvements
- Hyperparameter tuning for better performance
- Adding more advanced models (e.g., XGBoost, Neural Networks)
- Feature engineering for deeper insights
- Deployment as a web app for interactive use

---
✅ This enhanced version ensures portability, professional structure, and reliable performance.
