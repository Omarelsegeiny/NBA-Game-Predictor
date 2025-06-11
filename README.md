# 🏀 NBA Game Outcome Predictor Using Machine Learning

A machine learning project built to predict the outcome (win/loss) of NBA games based on historical data and performance metrics using models like Logistic Regression and Ridge Classifier.

## 📌 Overview

This project explores the feasibility of predicting NBA game outcomes using statistical learning techniques. It leverages the NBA API to collect relevant game and player data, processes and engineers features, and applies classification models to predict game results.

## ✨ Features

- Pulls real-time and historical data using the NBA API
- Preprocesses and transforms raw data into model-ready format
- Applies Logistic Regression and Ridge Classification
- Uses time-series aware cross-validation to avoid data leakage
- Outputs model performance metrics for evaluation

## 🧪 Tech Stack

- **Python**
- **Pandas**, **NumPy**
- **Scikit-learn**
- **Matplotlib**, **Seaborn**
- **NBA API** ([swar/nba_api](https://github.com/swar/nba_api))
- **Jupyter Notebook**

## 📂 Dataset

The data is programmatically pulled from the [NBA API](https://github.com/swar/nba_api). It includes:

- Team-level statistics (e.g., FG%, plus-minus)
- Aggregated player statistics (e.g., rebounds, assists)
- Game outcomes (win/loss)

## 🚀 Getting Started

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/nba-game-predictor.git
   cd nba-game-predictor
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Run the notebook:
   ```bash
   jupyter notebook nba_ml_pred.ipynb
   ```

## 📈 Model Details

| Model               | Description                              |
|--------------------|------------------------------------------|
| Logistic Regression| Baseline binary classifier               |
| Ridge Classifier   | Linear model with L2 regularization      |

Evaluation metric: **Accuracy**  
Cross-validation: **TimeSeriesSplit**

## 🧠 Future Work

- Incorporate betting odds, injury reports, and strength of schedule
- Implement ensemble models for improved performance
- Build an interactive web dashboard

## 🙌 Authors

- **Omar Elsegeiny** – omarelsegeiny@gmail.com  
- **Xander Johnson** – xander.johnson@ndsu.edu

## 📘 References

- [NBA API](https://github.com/swar/nba_api)
- Raschka & Mirjalili (2019). *Python Machine Learning*
- [Dataquest YouTube](https://www.youtube.com/@Dataquestio)

## 📄 License

This project is licensed for educational and research purposes.
