# nfl-play-prediction-knn
K-Nearest Neighbors (KNN) classification model to predict NFL play types (Run or Pass) based on in-game features like down, yard line, and score differential.

 NFL Play Type Prediction Using KNN

This project uses a K-Nearest Neighbors (KNN) classification model to predict play types—either "Run" or "Pass"—in NFL games. It was developed as part of the ALY6020 Predictive Analytics course at Northeastern University.

## Objective
To analyze key play attributes and develop a model that enhances strategic football decision-making. The project explores how features like `yards_to_go`, `yard_line`, and `score_diff` influence play calls.

## Data Preparation
- Dropped irrelevant columns (`game_id`, `play_id`, etc.)
- Handled missing values and outliers using the IQR method
- Encoded categorical variables and standardized numerical ones
- Balanced the dataset using SMOTE

##  Modeling & Evaluation
- Tested K values of 3, 7, and 11
- Achieved best test accuracy of **58.99%** with **K = 7**
- Balanced performance across classes
- Used 5-fold cross-validation for evaluation

##  Files Included
- `ALY6020_Assignment week1.ipynb`: Jupyter notebook with full code
- `ALY6020_Assignmentweek1.docx`: Final report
- `README.md`: Project summary

## Tech Stack
- Python, Pandas, Scikit-learn
- Matplotlib, Seaborn
- Jupyter Notebook

##  Key Takeaways
- KNN effectively models play type tendencies using basic play context.
- Model improvements can come from adding richer features or switching to ensemble methods.
