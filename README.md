# Credit Rating Modeling 
I used various machine learning algorithms in Python to build credit rating model to fulfill loan lenders' (banks) needs. 

When banks issue loans to individuals, they have two goals that conflict with each other:
- Give as many loans as possible (fees, interest, all add to revenue)
- Try not to give loans to individuals who won't pay it back (lose money on the loan, collection costs, etc.)
A typical machine learning program in this space tries to find a suitable tradeoff between finding many good loans and not calling a bad loan good.
In this [project](code.ipynb), using the popular Lending club [loan data](loan_data_small.csv), I tried to build a "good" model that finds a good tradeoff between these two objectives. 

1. Data preparation and feature engineering.
   - Build a binary target
   - Label Encoding
   - One-hot encoding
   - Scaling
   - Train/Test split
2. I trained and tuned various models, including SGD Classifier, Random Forest Classifier, and Gradient Booster Classifier. 
3. For each model, I calculated model metrics, including accuracy, precision, recall, f1-score, area under the ROC curve (AUC), average precision (AP). By comparing these metrics, I suggested the useful credit rating model to banks. 
