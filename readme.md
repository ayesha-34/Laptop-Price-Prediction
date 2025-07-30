# 💻 Laptop Price Prediction

This project predicts laptop prices using machine learning based on hardware specifications. The dataset includes a variety of categorical and numerical features, and the model achieves over **84% accuracy (R² score)** using **Random Forest Regressor**.

---

## 📊 Dataset Features

| Column Name     | Description                        |
|------------------|------------------------------------|
| Company          | Laptop brand                       |
| TypeName         | Type of laptop (Ultrabook, Gaming) |
| Inches           | Screen size                        |
| Ram              | RAM size in GB                     |
| Gpu              | Graphics card model                |
| Gpu Brand        | Extracted GPU brand                |
| OpSys            | Operating system                   |
| Weight           | Weight in kg                       |
| Price            | Target variable (in ₹)             |
| Touchscreen      | 1 if touchscreen, else 0           |
| X_res, Y_res     | Screen resolution                  |
| Cpu Brand        | Extracted CPU brand                |
| HDD              | HDD capacity in GB                 |
| SSD              | SSD capacity in GB                 |
| Hybrid           | Hybrid storage (1/0)               |
| Flash_Storage    | Flash storage (1/0)                |

---

## 🔍 Exploratory Data Analysis (EDA)

EDA steps included:

- ✅ Count plots for categorical features (Company, TypeName, etc.)
- ✅ Histograms and scatter plots for numerical features (Inches, Ram, Weight, etc.)
- ✅ Correlation matrix with respect to `Price`
- ✅ Log transformation on `Price` to reduce skewness

---

## 🛠️ Feature Engineering

- Dropped less informative columns after derivation
- Label encoded categorical variables
- Applied log transformation to `Price`

---

## 🤖 Modeling

### Algorithms Tried:
- Linear Regression
- Random Forest Regressor ✅ (Best Performer)

### Final Evaluation:

- ✅ **R² Score**: `0.8457`
- ✅ **MAE**: `8491.70`

---

## 📂 Files

- `Laptop_Price_Prediction.ipynb` – Main notebook
- `laptop_data.csv` – Dataset

---

## 📦 Libraries Used

```bash
pandas
numpy
seaborn
matplotlib
scikit-learn




