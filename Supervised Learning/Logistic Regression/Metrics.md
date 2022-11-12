True Positive  (TP) -->>> Predicted positive and Actual also positive  -> P -> +, A -> +
True Negative  (TN) -->>> Predicted negative and Actual also negative  -> P -> -, A -> -
False Positive (FP) -->>> Predicted positive and Actual negative       -> P -> +, A -> -
False Negative (FN) -->>> Predicted negative and Actual positive       -> P -> -, A -> +

AP -> Actual Positive
PP -> Predicted Positive

Accuracy = (TP + TN) / (TP + TN + FP + FN)
Recall = (TP) / (AP) = (TP) / (FN + TP)
Precision = (TP) / (PP) = (TP) / (TP + FP)
F1 Score = (2 * Precision * Recall) / (Precision + Recall)



Up Sampling -> Due to unbalance categorical data, we will increase the low number data so that both will be balance
Down Sampling -> Due to unbalance categorical data, we will decrease the high number of data so that both will be balance