# Peer Review: Derek Fintel

As part of the final for CSIS 44670 we are performing peer reviews. The rest of the class is not doing a quantified self study, so this peer review will seem disjointed from the analysis I've done on myself. 

[Link to my peer's work on this assignment](https://github.com/dfintel25/ml_regression_Fintel/blob/main/lab04/regression_fintel.ipynb).

Derek analyzed an automative dataset, predicting **miles per gallon** of a vehicle given several other facts about it.

**Clarity & Organization (Is the notebook structured and easy to follow?)**  
I think Derek did a phenomenal job in his organization. I don't know a thing about cars, but I found his layout easy to follow along with. Things are structured well, with a consistent approach to labeling and indentation which I really like.

**Feature Selection & Justification (Do the chosen features make sense given the objectives?)**  
Derek makes a good argument for his feature selection. The use of the features highly correlated with the target is, in principle, *exactly* what I did in my own research.  

**Model Performance & Comparisons (Are the results and comparisons clearly explained?)**  
Derek's models were highly variable in terms of their predictive power. He tested two separate pipelines, the one *not* including polynomial fitting performed well, but the one including polynomials performed worse than just taking the average. This, he surmises, is liekly due to overfitting the training data. I'm inclined to agree. 

**Reflection Quality (Are insights well thought out?)**  
Structurally Derek's entire notebook is impeccable. Much less clutter than I left in my own. His conclusion:

> there is indeed a strong relationship of 'horsepower' + 'weight' to 'mpg' results

is inarguable. It's supported by intuition and machine learning techniques.
