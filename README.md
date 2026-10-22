# Python Machine Learning

Machine learning and data visualization notebooks in Python, built with **pandas**, **NumPy**, **scikit-learn**, **Matplotlib** and **Seaborn**.

## Notebooks

| Notebook | Description |
|----------|-------------|
| [`project.ipynb`](project.ipynb) | **Heart Disease Prediction** — end-to-end classification project |
| [`train&test.ipynb`](train%26test.ipynb) | Reusable train/test template using a Decision Tree classifier |
| [`visualization.ipynb`](visualization.ipynb) | Data visualization techniques with Seaborn |

## ❤️ Heart Disease Prediction

Predicts whether a patient has heart disease based on 13 clinical features (age, sex, chest pain type, cholesterol, max heart rate, etc.).

**Workflow**
1. **Exploratory analysis** — target distribution and correlation heatmap
2. **Data split** — 80% training, 20% testing
3. **Model** — Logistic Regression
4. **Evaluation** — accuracy, precision, recall, F1-score and confusion matrix

**Results**

| Metric | Score |
|--------|-------|
| Accuracy | ~84% |
| Recall | ~94% |

The high recall means the model correctly detects most patients who actually have heart disease — the most important metric in a medical context.

> Results may vary slightly between runs because the train/test split is random.

## 📊 Visualization

Explores the Seaborn `tips` dataset using distribution plots, scatter and joint plots, heatmaps, bar/box/violin plots, FacetGrid and regression plots.

## Run

Each notebook includes an **Open in Colab** badge — click it to run the notebook in your browser with no setup.

For the heart disease project, upload `heart.csv` when prompted.
