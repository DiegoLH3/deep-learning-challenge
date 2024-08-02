## Overview of the Analysis

*   The nonprofit foundation Alphabet Soup wants a tool that can help it select the applicants for funding with the best chance of success in their ventures.
*   We'll use the features in the provided dataset to create a binary classifier that can predict whether applicants will be successful if funded by Alphabet Soup.

## Results

* Data Preprocessing
    * These are the variables that were received:
        * EIN and NAME—Identification columns
        * APPLICATION_TYPE—Alphabet Soup application type
        * AFFILIATION—Affiliated sector of industry
        * CLASSIFICATION—Government organization classification
        * USE_CASE—Use case for funding
        * ORGANIZATION—Organization type
        * STATUS—Active status
        * INCOME_AMT—Income classification
        * SPECIAL_CONSIDERATIONS—Special considerations for application
        * ASK_AMT—Funding amount requested
        * IS_SUCCESSFUL—Was the money used effectively
    * The target that was used is 'IS_SUCCESSFUL' because it is what we're looking for. We are to find if a applicant will be successful if funded by the nonprofit.
    * The two variables that were removed were the 'EIN' and the 'NAME'
* Compiling, Training, and Evaluating the Model
    * In the original we used 2 hidden layers and one output layer (first(relu): 80, second(relu): 30, output(sigmoid): 1)
    * In the optimization we used 4 hidden layers and 1 output layer(first(relu): 80, second(relu): 50, third(relu): 30, fourth(relu):20, output(sigmoid): 1)
    * Was not able to acheive the target model performance of 75% but was close with 72.7%.
    * Increased the amount of hidden layers and their neurons but was not able to get higher than the 72.7%.

## Summary

* Overall with the results of the model that was come up with I do not beleive this model is fit enough to use, due to only getting 72.7% accuracy.