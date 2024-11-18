
# **Urban Environment and Public Health: EDA and Hybrid Model Analysis**

## **Overview**
This project explores the relationship between urban environmental factors and public health metrics, focusing on the Air Quality Index (AQI). By leveraging **Exploratory Data Analysis (EDA)** and a **Hybrid Machine Learning Model**, we aim to analyze and predict AQI based on features such as green coverage, population, vehicle count, and disease cases.

## **Dataset**
The dataset contains 2000 rows and 11 columns, including:
- **Population (%)**
- **AQI**
- **Green Coverage (%)**
- **Factories**
- **Vehicles Count**
- **Education Institutions Count**
- **Hospitals Count**
- **Waterborne Disease Cases**
- **Respiratory Disease Cases**
- **Year**

### **Data Source**
Provide the dataset source (e.g., a CSV file, Kaggle link, or other sources).

---

## **Project Goals**
1. Perform comprehensive **EDA** to uncover trends and insights.
2. Use a **hybrid machine learning model** combining Random Forest and Gradient Boosting to predict AQI.
3. Evaluate and visualize model performance using metrics and plots.
4. Highlight key urban factors influencing AQI and public health.

---

## **Project Structure**
```plaintext
Urban_Environment_and_Public_Health/
├── data/
│   └── dataset.csv                   # Dataset used for analysis and modeling
├── notebooks/
│   └── EDA_and_Hybrid_Model.ipynb    # Jupyter notebook with full analysis and modeling
├── src/
│   ├── preprocessing.py              # Data preprocessing scripts
│   ├── models.py                     # Model implementation and training scripts
│   └── evaluation.py                 # Evaluation metrics and plot functions
├── results/
│   └── plots/                        # Generated plots (e.g., feature importance, prediction results)
├── README.md                         # Project documentation
├── requirements.txt                  # Python dependencies
└── LICENSE                           # Project license
```

---

## **Installation**
To replicate this project, follow these steps:

1. **Clone the repository**:
   ```bash
   git clone https://github.com/username/Urban_Environment_and_Public_Health.git
   ```
2. **Navigate to the project directory**:
   ```bash
   cd Urban_Environment_and_Public_Health
   ```
3. **Install dependencies**:
   ```bash
   pip install -r requirements.txt
   ```

---

## **Usage**
1. **Run the EDA and modeling notebook**:
   ```bash
   jupyter notebook notebooks/EDA_and_Hybrid_Model.ipynb
   ```
2. **Preprocess data and train models**:
   ```bash
   python src/preprocessing.py
   python src/models.py
   ```
3. **Evaluate and generate plots**:
   ```bash
   python src/evaluation.py
   ```

---

## **Features**
- **EDA**:
  - Univariate, bivariate, and multivariate analysis.
  - Visualizations: Heatmaps, pair plots, box plots, histograms.
- **Hybrid Model**:
  - Combines **Random Forest** and **Gradient Boosting**.
  - Weighted average for robust AQI predictions.
- **Evaluation**:
  - Metrics: Mean Squared Error (MSE), Mean Absolute Error (MAE), R² Score.
  - Plots: Actual vs Predicted, Residual Distribution, Learning Curves, Feature Importance.

---

## **Results**
- **Model Performance**:
  - MSE: `5934.15`
  - MAE: `67.22`
  - R² Score: `-0.04`
- **Key Insights**:
  - Green coverage and factories significantly impact AQI.
  - Urban planning strategies can mitigate respiratory diseases linked to AQI levels.

---

## **Contributing**
Contributions are welcome! Please follow these steps:
1. Fork the repository.
2. Create a feature branch:
   ```bash
   git checkout -b feature-name
   ```
3. Commit changes and push to the branch:
   ```bash
   git commit -m "Add feature-name"
   git push origin feature-name
   ```
4. Open a pull request.

---

## **License**
This project is licensed under the MIT License. See the `LICENSE` file for more details.

---

## **Contact**
**Author**: Arif Mia  
📧 [Arif Miah]  
💼 [www.linkedin.com/in/arif-miah-8751bb217]  

Feel free to reach out for collaboration or feedback! 😊

