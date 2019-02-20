# Loan Predictor
## Model Evaluation & Validation

### Install
This project requires the following Python libraries installed:

* [NumPy](www.numpy.org)
* [Pandas](pandas.pydata.org)
* [matplotlib](matplotlib.org)
* [scikit-learn](scikit-learn.org/stable/)

You will also need to have software installed to run and execute a [Jupyter Notebook](http://ipython.org/notebook.html)

### Run
In a terminal or command window, navigate to the top-level project directory `Loan-Predictor/` (that contains this README) and run one of the following commands:
> ipython notebook Loan_Predictor.ipynb

or

> jupyter notebook Loan_Predictor.ipynb

This will open the Jupyter Notebook software and project file in your browser.

### Data

The Loan predictor dataset consists of 614 data points, with each datapoint having 13 features. Dataset can be found in repository directory.

##### Features
`Loan_ID` - Unique Loan ID
`Gender` - Male/ Female
`Married` - Applicant married (Y/N)
`Dependents` - Number of dependents
`Education` - Applicant Education (Graduate/ Under Graduate)
`Self_Employed` - Self employed (Y/N)
`ApplicantIncome` - Applicant income
`CoapplicantIncome` - Coapplicant income
`LoanAmount` - Loan amount in thousands
`Loan_Amount_Term` - Term of loan in months
`Credit_History` - credit history meets guidelines
`Property_Area` - Urban/ Semi Urban/ Rural

##### Target Variable
`Loan_Status` - Loan approved (Y/N)
