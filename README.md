# Random Forest on credit card default

Many classification algorithms assumes that the class distribution is approximally balanced, but in many real applications this is not trurly the case. 
For example, in cancer diagnosis there will be many and many scans of not-cancerous samples and only few cancerous. Furthermore, the cost of 
missclassification is not the same: if a non-cancerous sample is classified as cancerous one could fix the error with more tests but if the 
opposite occurs, the patient could die!
This work try to provide a step-by-step analysis of an application of RF algorithm to the credit card defaultl dataset.
In particular, we will focus on the application of resampling techinques (SMOTE in principle) in order to deal with imbalanced datasets.
