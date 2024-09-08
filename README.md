# Loan Approval Prediction using Machine Learning

This project predicts whether a loan should be approved or not based on the applicant's profile using key features like Marital Status, Education, Applicant Income, Credit History, etc. The project uses machine learning techniques to assist banks in making informed loan approval decisions.

## Dataset

The dataset used for this project is named `LoanApprovalPrediction.csv` and contains 13 features such as:
- Gender: Gender of the applicant
- Married: Marital status of the applicant
- Dependent: Number of dependents
- Education: Educational qualification (Graduate/Not Graduate)
- Self_Employed: Employment status of the applicant
- ApplicantIncome: Income of the applicant
- CoapplicantIncome: Income of the co-applicant (if any)
- LoanAmount: Amount of loan requested (in thousands)
- Loan_Amount_Term: Term of loan (in months)
- Credit_History: Credit history of the applicant
- Property_Area: Type of property area (Urban, Rural, Semi-Urban)
- Loan_Status: Whether the loan is approved (Y/N)

## Project Files

- Dataset: `LoanApprovalPrediction.csv`
- Code: `Loan_Approval_Prediction.ipynb`

## Machine Learning Models Used

Several machine learning models were trained and evaluated to predict loan approval status:
- Random Forest Classifier: Achieved 82.5% accuracy on the test set
- KNeighborsClassifier
- Support Vector Classifier (SVC)
- Logistic Regression

## Results

- The Random Forest Classifier provided the highest accuracy on the test set with an 82.5% success rate.
- Other models, including KNN, SVC, and Logistic Regression, were also tested but yielded comparatively lower accuracy.

## How to Run

1. Clone the repository: git clone https://github.com/Yash070707/Loan-Approval-Prediction-using-Machine-Learning
2. Install the required libraries:pip install pandas numpy scikit-learn matplotlib seaborn
3. Open the Jupyter Notebook `Loan_Approval_Prediction.ipynb` to view and run the code.
4. The dataset `LoanApprovalPrediction.csv` is preloaded in the code.

## Visualizations

Several visualizations were created to show data distribution and correlations:
- Bar plots: For categorical variables like Gender, Married status, etc.
- Heatmap: To show the correlation between features, highlighting the importance of Credit_History on Loan_Status.

## Conclusion

This project demonstrates how machine learning can be used to streamline the loan approval process for banks, making it more efficient and reliable. Future improvements could involve implementing ensemble learning techniques like Bagging and Boosting to further enhance model performance.


