# Customer Churn Prediction Using Machine Learning

Artificial Intelligence Assignment 1 — The University of Lahore

## Files
- `Customer_Churn_Prediction.ipynb` — complete executed Jupyter Notebook
- `WA_Fn-UseC_-Telco-Customer-Churn.csv` — supplied dataset
- `Customer_Churn_Prediction_Final_Report.pdf` — final report
- `requirements.txt` — Python dependencies

## How to run
1. Install Python 3.10+.
2. Install dependencies:
   `pip install -r requirements.txt`
3. Open the notebook:
   `jupyter notebook Customer_Churn_Prediction.ipynb`
4. Run all cells from top to bottom.

## Models
- Logistic Regression
- Random Forest

## Test-set results
| Model | Accuracy | Precision | Recall | F1 |
|---|---:|---:|---:|---:|
| Logistic Regression | 80.55% | 65.72% | 55.88% | 60.40% |
| Random Forest | 78.92% | 63.51% | 48.40% | 54.93% |

The final model for the sample application is Logistic Regression based on the higher test-set F1-score.

## Dataset note
The assignment brief names an Excel dataset, while the supplied file is CSV. The supplied CSV is used directly because it contains the provided Telco Customer Churn data.
