# Machine_Learning

# Challenge Analysis

After performing each of the methods, even though the results are similar, the same improve when utilizing each other. 

Highly sensitive tests and algorithms tend to be aggressive, as they do a good job of detecting the intended targets, but also risk resulting in a number of false positives. High precision, on the other hand, is usually the result of a conservative process, so that predicted positives are likely true positives.

In this investigation high-risk loans are assigned to value 0 and low-risk loans to value 1, the purpose is to predict high-risk loans so even though these are assigned as assigned as True Positives, this means that these are in fact high-risk loans, which means that the result is negative.  

The difference between low-risk loans and high-risk loans, is really big, hence an over or under sampling method is really necessary in this scenario. After performing over or under sampling methods, oversampling with SMOTE method provided the highest results in regards to balanced accuracy score and low-risk recall, yet a different method provided a higher recall for high-risk loans. This is the SMOTEENN method which is a combination of under an over sampling. This method provided a high-risk loan recall of 75% and a 66% of balanced accuracy score which is closely the same as the SMOTE method, making the SMOTEENN method the most accurate for this analysis.

Having said this the high-risk loans precision in all of the methods applied is very low, this might be attribute to the large difference between both variables. 

As a conclusion, the SMOTEENN provided the most accurate and reliable information hence this method should continue to be used for this evaluation.
