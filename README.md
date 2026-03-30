# DNSC 6330 - Individual Homework 2  
**Explaining the COMPAS Replacement Model**

## Purpose
This repository implements SHAP, LIME, and DiCE explanations on the logistic regression model that predicts actual two-year recidivism (`two_year_recid`).  
It exactly follows the live-coding section of Lecture 02 and fulfills all homework requirements:

- SHAP beeswarm summary plot on the test set  
- SHAP waterfall plots for the highest-risk and lowest-risk individuals in each racial group (Black and White)  
- LIME explanations on the same four individuals  
- DiCE counterfactual explanations for the same four individuals (with immutable feature flagging)

## Libraries Used
- pandas, numpy  
- scikit-learn (pipeline, preprocessing, logistic regression)  
- shap, lime, dice-ml (explainability methods)  
- matplotlib (plots)

## How to Reproduce
1. Clone the repository:  
   `git clone https://github.com/fsamedli/dnsc6330-hw2-explainability.git`
2. Install required packages:  
   `pip install pandas numpy scikit-learn shap lime dice-ml matplotlib`
3. Open `hw2_compas_explainability.ipynb` and run all cells.

All outputs are fully reproducible.

## AI Assistance Statement
AI assistance (Grok) was used **solely** to draft and refine this README.md file to improve clarity and professionalism.  
The entire Python notebook (`hw2_compas_explainability.ipynb`) — including data loading, preprocessing, model pipeline, SHAP, LIME, DiCE, and all plots — was implemented by the author. Only minor guidance was received on GitHub navigation and repository setup.
