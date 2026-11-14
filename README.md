# Machine Learning Football Analysis

A collection of practical machine-learning exercises and football analytics projects using Python and Jupyter Notebook. The repository explores supervised and unsupervised learning techniques through football-related datasets.

## Project Overview

The repository covers three main machine-learning topics:

### 1. Supervised Learning — Classification

A classification exercise using a **Decision Tree Classifier**.

The notebook demonstrates:
- Preparing the dataset.
- Training a Decision Tree model.
- Generating predictions.
- Evaluating model performance using accuracy and a confusion matrix.

A recorded notebook run reports approximately **61.3% accuracy**.

### 2. Supervised Learning — Linear Regression

A regression project that predicts a team's English Premier League rank based on its goals scored, using historical league data from 1996 to 2020.

The notebook evaluates the model using:
- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)
- R-squared (R²)
- Mean Absolute Percentage Error (MAPE)

Recorded results:

| Metric | Value |
|---|---:|
| MAE | 2.87 |
| MSE | 11.52 |
| RMSE | 3.39 |
| R² | 0.63 |
| MAPE | 61.27% |

### 3. Unsupervised Learning — Clustering

A football analytics project analyzing passes made by **England and Spain in the 2023 FIFA Women's World Cup Final**.

The notebook uses the starting and ending coordinates of passes to group passing events into **five clusters**.

This helps explore spatial patterns and similarities in the teams' passing behavior without predefined labels.

## Machine Learning Concepts Covered

- Supervised and unsupervised learning.
- Decision Tree Classification.
- Linear Regression.
- K-Means Clustering.
- Model training and prediction.
- Classification and regression evaluation.
- Feature preparation and data manipulation.
- Football data analysis.

## Technologies and Libraries

- Python
- Jupyter Notebook
- pandas — data manipulation.
- NumPy — numerical operations.
- Matplotlib — data visualization.
- Seaborn — statistical visualization.
- scikit-learn — machine-learning models and evaluation.

## Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/Aminsfwt/Machine-Learning-Football-Analysis.git
cd Machine-Learning-Football-Analysis
```

### 2. Create a virtual environment

```bash
python -m venv .venv
```

Activate it on Windows:

```bash
.venv\Scripts\activate
```

### 3. Install dependencies

```bash
pip install pandas numpy matplotlib seaborn scikit-learn jupyter
```

### 4. Launch Jupyter Notebook

```bash
jupyter notebook
```

Open the notebook you want to explore and execute its cells in order. Keep each supporting dataset in the location expected by its notebook.

## Model Evaluation

The repository explores different evaluation techniques depending on the machine-learning task.

| Task | Evaluation techniques |
|---|---|
| Classification | Accuracy, Confusion Matrix |
| Regression | MAE, MSE, RMSE, R², MAPE |
| Clustering | Grouping and interpretation of cluster patterns |

## Notes

- Model scores are recorded experimental results and may vary with different data splits and configurations.
- MAPE can be misleading when actual values are zero or close to zero.
- Clustering results depend on feature selection, scaling, and the number of clusters.

## Author

**Amin Safout**

GitHub: [@Aminsfwt](https://github.com/Aminsfwt)

---

An educational portfolio demonstrating the application of machine-learning techniques to football data.
