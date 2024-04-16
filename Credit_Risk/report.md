## Overview of the Analysis

This analysis focused on determining whether a loan is high or low-risk based on a synthetic dataset of historical lending activity from a peer-to-peer lending services company. The model was trained and evaluated on this data in order to determine the creditworthiness of future borrowers.

<ul>
<li>Acuracy Score: 0.9917973586463062</li>
<li>Precision Score (healthy loan): 1.00<br>
    Precision Score (high-risk loan): 0.86 </li>
<li>Recall Score (healthy loan): 1.00<br>
    Recall Score (high-risk loan): 0.89 </li>
</ul>

I do not recommend this model for use in this particular application. Although the model has a very high accuracy rating (0.99), both the precision score (0.86) and the recall score (0.89) for a high-risk loan were below 0.90. While this is objectively quite high, I do not think it is high enough for a model meant to predict the risk-level of a loan. A model meant to predict high-risk loan candidates should have better performance than this model achieved. With some additional training data for high-risk loan status, I believe the model could be improved to a level appropriate for the problem at hand. 

