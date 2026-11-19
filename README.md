# 🚗 Parking Occupancy Prediction Using Machine Learning

## 📌 Project Overview

Parking Occupancy Prediction is a Machine Learning-based project that predicts parking availability using smart mobility data.

The project analyzes traffic conditions, vehicle count, weather conditions, road occupancy, and other related factors to classify parking availability into three categories:

- 🟢 High Availability
- 🟡 Medium Availability
- 🔴 Low Availability

The main goal is to reduce the time spent searching for parking spaces and support intelligent transportation systems.

## 🎯 Objectives

- Predict parking availability using Machine Learning.
- Analyze smart mobility and traffic data.
- Apply different classification algorithms.
- Compare model performance using accuracy.
- Understand the application of Machine Learning in smart cities.

## 🛠️ Technologies Used

- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

## 📂 Dataset Information

**Dataset:** `smart_mobility_dataset.csv`

- Total Records: 5,000
- Original Attributes: 15
- Final Features: 21
- Missing Values: 0
- Duplicate Records: 0

### Parking Availability Classification

| Parking Availability | Parking Status |
|---|---|
| 0–16 | Low Availability |
| 17–33 | Medium Availability |
| 34–49 | High Availability |

## 🤖 Machine Learning Algorithms

Three Machine Learning algorithms are implemented:

1. **Logistic Regression** – Used for classifying parking availability.
2. **Random Forest** – Uses multiple decision trees to improve classification.
3. **K-Nearest Neighbors (KNN)** – Predicts parking status based on nearby data points.

## ⚙️ Project Workflow

1. Import required Python libraries.
2. Load the smart mobility dataset.
3. Explore and analyze the dataset.
4. Handle missing values and duplicate records.
5. Create parking availability categories.
6. Perform Exploratory Data Analysis (EDA).
7. Apply categorical encoding.
8. Split the dataset into training and testing sets.
9. Train Machine Learning models.
10. Predict parking availability.
11. Compare model accuracy.

## 📊 Model Performance

| Machine Learning Model | Accuracy |
|---|---:|
| Logistic Regression | 32.6% |
| Random Forest | **35.7%** |
| KNN | 34.5% |

**Best Performing Model:** Random Forest with 35.7% accuracy.

## 📈 Visualizations

The project includes:

- Parking Availability Distribution
- Correlation Heatmap
- Parking Availability Histogram
- Traffic Condition vs Parking Availability
- Weather Condition vs Parking Availability
- Confusion Matrices
- Model Accuracy Comparison
- Feature Importance Graph

## 💻 How to Run the Project

**Step 1:** Clone the repository.

```bash
git clone https://github.com/your-username/parking-occupancy-prediction.git
```

**Step 2:** Open the project notebook in Google Colab or Jupyter Notebook.

**Step 3:** Upload the dataset:

```text
smart_mobility_dataset.csv
```

**Step 4:** Install the required libraries if necessary.

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

**Step 5:** Run all notebook cells to train the models and view the predictions.

## 📁 Repository Structure

```text
Parking-Occupancy-Prediction/
│
├── COA_project.ipynb
├── smart_mobility_dataset.csv
├── COA_Report.pdf
└── README.md
```

## 🔮 Future Enhancements

- Improve prediction accuracy through hyperparameter tuning.
- Integrate real-time parking data.
- Develop a user-friendly parking prediction web application.
- Integrate IoT-based parking sensors.
- Display available parking locations on a map.



