# **Machine Learning for European Option Pricing**

## **Project Overview**
This project aims to develop a machine learning-based system for pricing **European options** and estimating **implied volatility** using open-source data from [OptionDX.com](https://www.optiondx.com). The system will leverage state-of-the-art **machine learning algorithms**, including **Random Forest, XGBoost, and Neural Networks**, to analyze historical option data and predict market behavior.

## **Key Steps**
### 1. Data Collection
- Gather **historical European option data** from OptionDX.com, including:
  - **Strike price**
  - **Expiration date**
  - **Underlying asset price**
  - Other relevant financial variables  
- The **SPX (S&P 500 Index)** is a European-style option instrument and will serve as the primary dataset.

### 2. Model Development
- Implement three different **machine learning models**:
  - **Random Forest** – Tree-based model, useful for feature importance analysis.
  - **XGBoost** – Ensemble learning model optimized for gradient boosting.
  - **Neural Networks** (e.g., **Multi-Layer Perceptron**) – Capturing complex non-linear pricing patterns.

### 3. Model Evaluation
- Compare model performance using the following metrics:
  - **Root Mean Squared Error (RMSE)**
  - **R-squared (R²)**
  - **Computational efficiency (training & inference time)**

### 4. Visualization
- Create **visual representations** of model predictions versus actual **implied volatility surfaces**.

### 5. Documentation & Deployment
- Document all findings and develop a **user-friendly interface** for real-world application.

## **Goals**
### **Comparison with Numerical Methods**
- Compare **machine learning approaches** to traditional numerical methods like the **Black-Scholes model**.
- Investigate whether **ML models provide a time advantage** over numerical methods.
- Analyze if there is a trade-off in **accuracy** when using ML-trained models instead of numerical solvers.

### **Impact of Training Set Size**
- Evaluate model performance on **different dataset sizes**.
- Measure the impact on **accuracy vs. computational time**.
- Assess the trade-off between **training time and predictive performance**.

## **Technologies & Tools**
- **Programming Language**: Python  
- **ML Libraries**: Scikit-learn, XGBoost, TensorFlow/PyTorch  
- **Data Processing**: Pandas, NumPy  
- **Visualization**: Matplotlib, Seaborn  
- **Deployment**: Google Colab, Streamlit (if interactive UI is developed)

## **How to Run the Project**
1. Clone the repository:
   ```bash
   git clone https://github.com/your-repository-name.git
   cd your-repository-name

2. Install dependencies:
   ```bash
    pip install -r requirements.txt
   
3. Run the notebook in Google Colab or Jupyter Notebook.
4. Follow the instructions in the notebook to train models and analyze results.

## **Contributors**
- Leon Chien
