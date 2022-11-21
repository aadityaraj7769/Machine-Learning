# Machine-Learning

Confidence, Support and Lift

Support for the rule = (no. of records with both antecedent and consequent) / (Total no. of Records)
                     = P (A intersection B) / N

Confidence for the rule (A->B) = (no. of records with both antecedent and consequent) / (No. of records of the antecedent)
                        = P (A intersection B) / P (A)
                        = Support (A->B) / Support (A)

Expected Confidence = (No. of records of the consequent) / (Total no. of records)


Lift(A->B) = Support(A->B) / Support(B) * Support (A)