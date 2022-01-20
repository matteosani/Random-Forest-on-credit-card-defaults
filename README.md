# Random Forest on credit card default

Many classification algorithms assumes that the class distribution is approximally balanced, but in many real applications this is not trurly the case. 
For example, in cancer diagnosis there will be many and many scans of not-cancerous samples and only few cancerous. Furthermore, the cost of 
missclassification is not the same: if a non-cancerous sample is classified as cancerous one could fix the error with more tests but if the 
opposite occurs, the patient could die!
This work try to provide a step-by-step analysis of an application of RF algorithm to a less letal dataset: credit card default.
In particular, we will focus on the **correct** application of resampling techinques (SMOTE in principle) in order to deal with imbalanced datasets.

I would like to emphasize **correct** since during this experience i've read lot of works on the same application (or similar) and not all of them 
were correctly applied: good performances does not mean that is correct!
Nice, but now you may ask: how can i trust you? who are you? Thank you for asking, but the good news is that you don't trust me (neither i do) 
since all the theoretical aspects are documented and all the references can be found on the bottom of *Underlying Theory.ipynb* file.

I hope you will enjoy my work!
