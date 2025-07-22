
# 🍷 Wine Quality Classification

A machine learning pipeline to predict wine quality based on physicochemical tests. The project handles class imbalance using SMOTE and undersampling, explores PCA for dimensionality reduction, and benchmarks multiple classifiers including SVM, Random Forest, and Gradient Boosting.

## 📂 Project Structure

```

red-wine-quality-classification/
│
├── data/                  # Dataset (CSV format)
├── notebook/              # Jupyter notebook containing all steps
├── requirements.txt       # Python dependencies
├── .gitignore             # Files to ignore in version control
├── README.md              # Project overview and documentation
└── LICENSE                # Optional open-source license

```

## 🔍 Features

- **Exploratory Data Analysis (EDA)**
- **Class Imbalance Handling** with SMOTE + Random Undersampling
- **PCA** for dimensionality reduction
- **Model Benchmarking** (SVM, Random Forest, Gradient Boosting, etc.)
- **Evaluation** using F1-score, precision, recall, and accuracy

## 🛠️ Tech Stack

- Python (pandas, scikit-learn, imbalanced-learn, matplotlib, seaborn)
- Jupyter Notebook

## 📊 Dataset

The dataset used is the [Wine Quality Data Set](https://www.kaggle.com/datasets/ammiyacine/wine-quality-red-and-white) from UCI Machine Learning Repository available at kaggle.

## 🚀 Quick Start

1. Clone the repo
2. Install dependencies  
```

pip install -r requirements.txt

```
3. Run the Jupyter notebook  
```

jupyter notebook notebook\red-wine-quality-classification.ipynb

```

## 🧪 Model Results

| Model             | F1 Score (Minority) |
|------------------|---------------------|
| SVM              | 0.63                |
| Random Forest    | 0.56                |
| Gradient Boosting| 0.57                |

## 📄 License

MIT License

