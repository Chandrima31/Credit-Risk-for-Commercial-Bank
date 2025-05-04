<b> Credit Risk Part-1: Binning, WoE, IV, PD Model </b>

Context & Objective:
The dataset being used here has 7 years' historical loan data taken from LendingClub. By looking at the loan status, we can check if the loan was sanctioned to the customers or not. If the loan status is "charged off" or "default" or the issuance of loan got delayed by 31-120 days, it is a bad loan. We will analyze the characteristics of the customers whose loans belong to "bad loan" category and will build a Probability of Default (PD) Model, so that is can be used in future to predict the customer will default or not.

We have used some useful concepts:

Binning,
Weight of Evidence (WoE),
Information Value (IV)

<b> Credit Risk Part-2: Black-Box Model Explainability </b>

Background:
In Part-1, we built PD model (white box) which is fully explainable. While using Black-Box models like Neural Net, Gradient Boosting, Random Forest etc. explability is a challenge. We will use two packages LIME (Local Interpretable Model-Agnostic Explanations) and SHAP (SHapley Additive exPlanations) here to work on model explainability.

For data preprocessing, we will work more or less on the same line of approach that we followed in Part-1, except for the fact, here we need to use Label Encoder to convert categorical variables to numeric.
