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

### 1.Inflight entertainment impact on customers satisfaction
![Satisfaction vs inflight entertainment](assets/img1.png)
*Figure 1: The figure shows a logistics relation along the satisfaction and inflight-entertainment.*

### 2.Feature Importance
![Feature Importance](assets/img2.png)
*Figure 2: The figure clearly shows that the highest impacting key factor on satisfation are seat-comfort , inflight-entertaiment and leg-room service.*

## Model Performance & Evaluation

The models were evaluated using Accuracy, Precision, Recall, and the F1-Score. For this business case, maximizing overall **Accuracy** and **Precision** ensures the airline correctly identifies satisfied customers without misallocating resources to areas that don't need improvement.

                    
| Model | Accuracy | Precision | Recall | F1-Score |
| :--- | :--- | :--- | :--- | :--- |
| **Logistic Regression** | 0.77 | 0.76 | 0.84 | 0.80 |
| **Tuned Decision Tree** | 0.93 | 0.94 | 0.95 | 0.94 |
| **Tuned Random Forest** | 0.91 | 0.91 | 0.91 | 0.92 |
| **Tuned XGBoost** | **0.88** | **0.86** | **0.94** | **0.90** |

> **Conclusion:** The Tuned decision tree model demonstrated the highest predictive capability, effectively decoding the complex matrix of passenger satisfaction while it may account for overfitting the data. 

## Environment Setup & Installation

To ensure reproducibility, please run this project within an isolated virtual environment.

### 1. Clone the Repository
```bash
git clone [https://github.com/yourusername/xyz-airlines-satisfaction.git](https://github.com/yourusername/xyz-airlines-satisfaction.git)
cd xyz-airlines-satisfaction
```
2. Create a Virtual Environment
 * For Windows:
   ``` bash
   python -m venv venv
   venv\Scripts\activate
   ```
 * For MacOS And Linux:
   ``` bash
   python3 -m venv venv
   source venv/bin/activate
   ```
3. Install the dependencies
   ``` bash
   pip install --upgrade pip
   pip install -r requirements.txt
   ```
4. Run the Jupiter Notebook.


