# 🚭 Tobacco-Cessation Precision Tool

This repository implements a machine learning-based tobacco cessation prediction tool. 

---

## 📁 Project Structure

- `Code.ipynb` – Jupyter Notebooks for data preprocessing, model training, and evaluation.
- `requirements.txt` – Lists all required Python libraries.
- `Data_Final.csv` – Input dataset files.
- `README.md` – Overview and usage instructions (this file).

---

You can install all dependencies by running the comman pip install -r requirements.txt

## 🧪 Sample Results :

- **AUC Score**: `0.7176`

**Confusion Matrix:**

[[253 130]
 [124 253]]

Classification Report:

| Class | Precision | Recall | F1-Score | Support |
|-------|-----------|--------|----------|---------|
| 0     | 0.62      | 0.60   | 0.61     | 383     |
| 1     | 0.61      | 0.63   | 0.62     | 377     |


The above results can be easily replicated by:

1. Opening the `Code.ipynb` file.
2. Updating the dataset path in the data loading cell.
3. Running all cells sequentially to train the model and view performance metrics.
