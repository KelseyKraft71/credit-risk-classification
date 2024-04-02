# Module 12 Report Template

## Overview of the Analysis

In this section, describe the analysis you completed for the machine learning models used in this Challenge. This might include:

This analysis focused on determining whether a loan is high or low-risk based on a synthetic dataset of historical lending activity from a peer-to-peer lending services company. The model was trained and evaluated on this data in order to determine the creditworthiness of future borrowers.

<ul>
<li>Acuracy Score: 0.9917973586463062</li>
<li>Precision Score (healthy loan): 1.00<br>
    Precision Score (high-risk loan): 0.86 </li>
<li>Recall Score (healthy loan): 1.00<br>
    Recall Score (high-risk loan): 0.89 </li>
</ul>

I do not recommend this model for use in this particular application. A model meant to predict high-risk loan candidates should have better performance than this model achieved. With some additional training data for high-risk loan status, I believe the model could be improved to a level appropriate for the problem at hand. 

* Explain the purpose of the analysis.
* Explain what financial information the data was on, and what you needed to predict.
* Provide basic information about the variables you were trying to predict (e.g., `value_counts`).
* Describe the stages of the machine learning process you went through as part of this analysis.
* Briefly touch on any methods you used (e.g., `LogisticRegression`, or any other algorithms).

## Results

Using bulleted lists, describe the accuracy scores and the precision and recall scores of all machine learning models.

* Machine Learning Model 1:
    * Description of Model 1 Accuracy, Precision, and Recall scores.

## Summary

Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. For example:

* Which one seems to perform best? How do you know it performs best?
* Does performance depend on the problem we are trying to solve? (For example, is it more important to predict the `1`'s, or predict the `0`'s? )

If you do not recommend any of the models, please justify your reasoning.
