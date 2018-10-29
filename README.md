# Marketing-Optimisation
Optimizing sales of a grocery store by using apriori model to train machine on given dataset.

Approach:
Used the association rules algorithm i.e. APRIORI ALGORITHM.
Based on:
"one who buys ....... also buys....."

Procedure:
-set minimum support and confidence
-take all rules having support > min support
-take all rules having confidence > min confidence
-sort by decreasing lift

Support(M)=total transaction containg M / total transactions

Confidence(M1->M2) = transaction containing M1 and M2 / transaction containg M1

Lift = Confidence / Support
