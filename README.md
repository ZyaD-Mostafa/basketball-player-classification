# Basketball Player Classification

A Machine Learning project focused on exploring basketball-related data and building a classification model to predict whether a person is classified as a basketball player.

## Project Overview

This project explores the use of Machine Learning techniques to classify individuals into two categories:

- **Yes:** Basketball Player
- **No:** Not a Basketball Player

The project uses a structured dataset containing personal information such as names, cities, and ages. The dataset is prepared for data analysis, preprocessing, and classification experiments.

## Dataset Information

The dataset is stored in `basketball_players_180.csv`.

It contains **180 records** and the following columns:

| Column | Description |
|---|---|
| Name | Individual's name |
| City | City of residence |
| Age | Individual's age |
| Label | Classification result (Yes/No) |

### Data Composition

- 7 original sample records from the assignment.
- 173 synthetically generated records.
- 180 total records.

**Data Note:** The additional records are synthetic data created for educational and experimental purposes. Their labels are simulated and should not be interpreted as verified real-world basketball player records.

## Project Objectives

- Understand and explore structured datasets.
- Perform basic data analysis.
- Apply data preprocessing techniques.
- Convert categorical values into numerical representations.
- Train and evaluate classification algorithms.
- Make predictions using new input data.

## Technologies

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Git and GitHub

## Project Structure

```text
basketball-player-classification/
│
├── basketball_players_180.csv
│
├── README.md
│
└── (Machine Learning notebooks and scripts will be added)
```

## Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/YOUR_USERNAME/basketball-player-classification.git
```

### 2. Install Required Libraries

```bash
pip install pandas numpy scikit-learn matplotlib
```

### 3. Load the Dataset

```python
import pandas as pd

df = pd.read_csv("basketball_players_180.csv")

print(df.head())
print(df.info())
print(df.shape)
```

## Machine Learning Approach

The project is designed as a binary classification problem.

Potential algorithms include:

- Decision Tree Classifier
- K-Nearest Neighbors (KNN)
- Logistic Regression
- Random Forest Classifier

Model training, testing, and evaluation will be documented as the implementation progresses.

## Limitations

- Most records are synthetically generated.
- Classification labels are simulated, not independently verified.
- Age and city alone are insufficient to determine whether someone is actually a basketball player.
- Model results should be considered educational experiments rather than reliable real-world predictions.

## Future Improvements

- Add verified real-world basketball datasets.
- Include additional features such as height, weight, and playing statistics.
- Compare different classification algorithms.
- Improve model evaluation and prediction reliability.

## Author

Developed as an educational Machine Learning project to explore data analysis and classification techniques.

---

**Project Status:** Dataset Preparation Completed | Model Implementation In Progress
