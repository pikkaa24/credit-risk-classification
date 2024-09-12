# Module 12 Report Template

## Overview of the Analysis

This analysis aims to determine loan risk based on loan size, interest rate, income, debt-to-income ratio, number of account, deragatory marks, and total debt. These demographics help determine if the borrower will have the ability to make the payments on the loan. If the debt-to-income ratio or total debt is too large, then taking on another loan would be too risky. The loans will be determined to be either a healthy loan or a high-risk loan via logistic regression.

## Results

* Logistic Regression:
Logistic regression takes multiple variables to statistically determine a binary outcome. In this case, the outcome would be a healthy loan or a high-risk loan.

    * Accuracy
        This model has a 99% accuracy. This means that 99% of the predictions are correct.
 
    * Precision
        The precision for healthy loans is 100%, meaning all loans the model identified as healty were actually heathy. The precision for high-risk loans is 85%, meaning of all the loans the model identified as high-risk 85% were acutally high-risk.
 
    * Recall
        Recall for healthy loans is 99%. This means that of all the healthy loans, the model correctly identified 99% of them. Recall for the high-risk loans is 91%. This means that of all the high-risk loans, the model correctly identified 91%

## Summary

This model accurately predicts healthy loans, but is not as accurate for high-risk loans. Accurately determining a healthy loan is more important than determining a high-risk loan. Higher accuracy in healthy loan means less high-risk loans are identified as healthy loans. A lower accuracy for high-risk loans means more healthy loans are identified as high-risk loans. The accuracy for the high-risk loans on this model is still high with an f-1 score of 88%. The business lost from the healthy loans identified as high-risk would be minimal. This model would be beneficial for any loan institution.
