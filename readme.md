# Invistico Airlines: Customer Satisfaction Prediction & Analysis

## Project Summary
In the highly competitive aviation industry, passenger satisfaction is the ultimate driver of brand loyalty and revenue generation. This project analyzes the post-flight survey data of Invistico Airlines to uncover the hidden patterns separating a "unsatisfied" passenger from a "satisfied" one. By deploying a suite of advanced classification models, this analysis predicts passenger sentiment while it's impact due specific service areas—such as boarding efficiency, inflight entertainment, and seat comfort etc.

## Project Objective
* **Sentiment Prediction:** Build a robust system capable of predicting a passenger's satisfaction level based on the dataset provided.
* **Identify Key Drivers:** Pinpoint which aspects of the flight experience have the highest statistical impact on overall satisfaction.
* **Strategic Allocation:** Provide data-driven insights to airline management, allowing them to optimize investments in areas that actually impact to passengers satisfaction.


## Methodology & Machine Learning Models
To ensure high predictive accuracy and interpretability, multiple classification algorithms were trained, optimized, and evaluated:

1. **Logistic Regression:** Serves as the baseline model, highlighting clear, linear relationships between satisfaction and inflight-entertaiment etc.
2. **Decision Tree Classifier:** Captures non-linear patterns and offers clear, rule-based decision paths.
3. **Random Forest:** An ensemble approach utilized to handle the high variance of survey data, preventing overfitting and improving generalization.
4. **XGBoost:** A powerful gradient boosting framework optimized to capture complex, non-linear interactions.

## 📊 Exploratory Data Analysis & Visual Insights

### 1. Satisfaction by Travel Class & Flight Distance
![Satisfaction Distribution](path/to/your/class_distance_distribution.png)
*Figure 1: Proportion of satisfied vs. dissatisfied passengers categorized by travel class and flight distance.*

### 2. What Drives Passenger Happiness? (Feature Importance)
![Feature Importance](path/to/your/airline_feature_importance.png)
*Figure 2: The top service factors driving customer satisfaction, extracted from the optimized XGBoost model. (e.g., Inflight Wi-Fi, Online Boarding, Legroom).*


## Model Performance & Evaluation

The models were evaluated using Accuracy, Precision, Recall, and the F1-Score. For this business case, maximizing overall **Accuracy** and **Precision** ensures the airline correctly identifies satisfied customers without misallocating resources to areas that don't need improvement.

| Model | Accuracy | Precision | Recall | F1-Score |
| :--- | :--- | :--- | :--- | :--- |
| **Logistic Regression** | 0.00 | 0.00 | 0.00 | 0.00 |
| **Decision Tree** | 0.00 | 0.00 | 0.00 | 0.00 |
| **Random Forest** | 0.00 | 0.00 | 0.00 | 0.00 |
| **XGBoost** | **0.00** | **0.00** | **0.00** | **0.00** |

> **Conclusion:** The XGBoost model demonstrated the highest predictive capability, effectively decoding the complex matrix of passenger feedback and flight logistics. 

---

## Environment Setup & Installation

To ensure reproducibility, please run this project within an isolated virtual environment.

### 1. Clone the Repository
```bash
git clone [https://github.com/yourusername/xyz-airlines-satisfaction.git](https://github.com/yourusername/xyz-airlines-satisfaction.git)
cd xyz-airlines-satisfaction
