# Data Science Project 1: Salary Prediction 📊

**Channel:** IGNITE ACADEMY KHAMGAON  
**Video:** https://youtu.be/1dMjWeuepPw  
**Topic:** Predicting Student Salary Package (in Lakhs) from CGPA using Linear Regression

---

## 📁 Project Structure

```
Salary_Prediction_Project/
│
├── dataset.csv                    ← Dataset: CGPA vs Package (200 records)
├── Salary_Prediction.ipynb        ← Main Jupyter Notebook (fully executed)
├── requirements.txt               ← Python dependencies
├── README.md                      ← This file
│
├── scatter_cgpa_vs_package.png    ← EDA: Scatter plot
├── correlation_matrix.png         ← Heatmap: Correlation
├── cgpa_distribution.png          ← Distribution of CGPA
├── package_distribution.png       ← Distribution of Package
├── linearity_check.png            ← Regression assumption plot
├── regression_line_train.png      ← Regression on training data
├── regression_line_test.png       ← Regression on test data
├── actual_vs_predicted.png        ← Actual vs Predicted plot
└── residuals_plot.png             ← Residuals analysis
```

---

## 📦 Dataset: `dataset.csv`

| Column        | Description                          |
|---------------|--------------------------------------|
| `CGPA`        | Cumulative Grade Point Average (6–10)|
| `PACKAGE (L)` | Salary package in Lakhs (LPA)        |

- **200 rows** × **2 columns**
- Positive linear relationship: higher CGPA → higher package

---

## 🔬 Notebook Workflow (Matches Video)

| Step | Description |
|------|-------------|
| 1 | Import Libraries (pandas, numpy, matplotlib, seaborn, sklearn) |
| 2 | Load Dataset → `df.head()`, `df.info()`, `df.describe()` |
| 3 | EDA: Scatter plot, Correlation Matrix, Distributions |
| 4 | Regression Assumptions check (Linearity, Residuals) |
| 5 | Feature Analysis (X = CGPA, y = PACKAGE) |
| 6 | Train-Test Split (80% train / 20% test) |
| 7 | Linear Regression Model Training |
| 8 | Predictions on test data + custom CGPA inputs |
| 9 | Evaluation: **MAE, MSE, RMSE, R² Score** |
| 10 | Final plots: Regression line (train & test), Actual vs Predicted, Residuals |

---

## 📈 Model Results

| Metric | Value |
|--------|-------|
| **MAE**  | 0.1500 |
| **MSE**  | 0.0348 |
| **RMSE** | 0.1867 |
| **R²**   | 0.8851 |

**Regression Equation:**
```
PACKAGE (L) = 0.4950 × CGPA + (-1.5277)
```

---

## ⚙️ Software Required

- Python 3.8+
- Jupyter Notebook or JupyterLab
- VS Code (optional)

---

## 🚀 How to Run the Project

### Step 1 — Download and Extract ZIP
Extract the ZIP file to a folder on your computer.

### Step 2 — Open Terminal / Command Prompt
Navigate into the extracted folder:
```bash
cd Salary_Prediction_Project
```

### Step 3 — Install Required Libraries
```bash
pip install -r requirements.txt
```

Or manually:
```bash
pip install pandas numpy matplotlib seaborn scikit-learn jupyter
```

### Step 4 — Launch Jupyter Notebook
```bash
jupyter notebook
```

### Step 5 — Open the Notebook
In the browser tab that opens, click on:
```
Salary_Prediction.ipynb
```

### Step 6 — Run All Cells
Go to menu: **Kernel → Restart & Run All**

---

## ✅ Expected Output

When the notebook runs successfully, you will see:

- ✔ Dataset loaded: **200 rows × 2 columns**
- ✔ No missing values, no duplicates
- ✔ Scatter plot: CGPA vs Package (blue dots + regression line in magenta)
- ✔ Correlation heatmap
- ✔ Linear Regression trained and fitted
- ✔ Predictions displayed in a table
- ✔ Custom predictions for CGPA = 7.0, 8.5, 9.5
- ✔ MAE, MSE, RMSE, R² printed clearly
- ✔ 4 visualization plots rendered

---

*Recreated from IGNITE ACADEMY KHAMGAON — Data Science Project 1: Salary Prediction*
