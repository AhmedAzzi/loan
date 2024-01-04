---
jupyter:
  kernelspec:
    display_name: base
    language: python
    name: python3
  language_info:
    codemirror_mode:
      name: ipython
      version: 3
    file_extension: .py
    mimetype: text/x-python
    name: python
    nbconvert_exporter: python
    pygments_lexer: ipython3
    version: 3.11.4
  nbformat: 4
  nbformat_minor: 2
---


# Project Statement

### The goal of this project is to leverage machine learning methods to analyze data from a set of banks so that a bank can make lending decisions to applicants based on their characteristics (predicting loan eligibility based on client details). The information regarding the loan applications from a set of banks is listed in the file Loan.csv."

## Part A

#### 1. Display the information about the data in this dataset

    <class 'pandas.core.frame.DataFrame'>
    RangeIndex: 598 entries, 0 to 597
    Data columns (total 13 columns):
     #   Column             Non-Null Count  Dtype  
    ---  ------             --------------  -----  
     0   Loan_ID            598 non-null    object
     1   Gender             598 non-null    object
     2   Married            598 non-null    object
     3   Dependents         586 non-null    float64
     4   Education          598 non-null    object
     5   Self_Employed      598 non-null    object
     6   ApplicantIncome    598 non-null    int64  
     7   CoapplicantIncome  598 non-null    float64
     8   LoanAmount         577 non-null    float64
     9   Loan_Amount_Term   584 non-null    float64
     10  Credit_History     549 non-null    float64
     11  Property_Area      598 non-null    object
     12  Loan_Status        598 non-null    object
    dtypes: float64(5), int64(1), object(7)
    memory usage: 60.9+ KB

#### 2. Display the calculation of basic statistical operations

![Alt text](imgs/image.png)

## Part B: Visualization of Results

#### 1. Applicant's income based on gender and marital status (Married)

![](imgs/351836a110e05b21c4cba723e77c42121d8053c9.png)

#### 2. Applicant's income based on gender and level of education

![](imgs/e0eb31d8912d2c865048fc54a86fd7178d8f62f1.png)

#### 3. Applicant's income based on marital status and level of education

![](imgs/65cc199e957e08f6d6e9e47ecca1a6dc89f54f97.png)

#### 4. Applicant's income based on the type of employment (Self_Employed)

![](imgs/2ebe26074362a5f5afef73946059accaf2bb3fda.png)

#### 5. Applicant's income based on the number of dependents

![](imgs/0fee05496483ce25697a3cd841373e1e91c95546.png)

#### 6. Applicant's income based on the number of previous credits and location

![](imgs/9d876b56fcd0b696ff65f77bb44b14c5610c6fcc.png)

#### 7. Applicant's income based on the level of education and number of previous credits

![](imgs/319be411cadbb1c4d5dfb88dede2aba9160bce5f.png)

### B. Show the loan amount based on the applicant's income

![](imgs/2f6a99132f82844989edc364056133e78c2ccdef.png)

### Visualization of the decision tree

![](imgs/32c9c8c028693ad433806f31784f0153037fe603.png)
