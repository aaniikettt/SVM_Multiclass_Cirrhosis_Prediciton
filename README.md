# SVM_Multiclass_Cirrhosis_Prediciton

Utilizing a Support Vector Machine with a polynomial kernel, I meticulously fine-tune the model using GridSearchCV, optimizing hyperparameters to ensure high precision and robust generalization. Post-training, the model predicts class probabilities on the test set, providing a detailed view of its prediction confidence, crucial for informed decision-making. This sophisticated approach exemplifies the depth of modern machine learning, valuable for both competitive and practical applications.

### This was submitted to the Kaggle Competition "Multi-Class Prediction of Cirrhosis Outcomes".

## Files
1. train.csv - the training dataset; Status is the categorical target; C (censored) indicates the patient was alive at N_Days, CL indicates the patient was alive at N_Days due to liver a transplant, and D indicates the patient was deceased at N_Days.
2. test.csv - the test dataset; our objective is to predict the probability of each of the three Status values, e.g., Status_C, Status_CL, Status_D.

## Output
The output is provided in the "submission.csv" file with columns: id, Status_C, Status_CL, Status_D. For each id, there's a set of predicted probabilities for each of the three possible outcomes, e.g., Status_C, Status_CL, and Status_D.
