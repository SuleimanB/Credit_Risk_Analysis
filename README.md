# Credit_Risk_Analysis

Overview of the analysis:
The purpose of this analysis is to use a credit card dataset from LendingClub to assess Credit Card Risk using Machine Learning as a way to automatically factor in whether lenders/credit card holders are dealing with a riskier loans. Using the imbalanced-learn and scikit-learn libraries will help assess the riskier loans despite their lack of data and gives us the ability to calculate the risk involved using a variety of models and assessments.

Results:
Oversampling

image-20210630190701195

image-20210630190951145

Starting with our Oversampling algorithms. The Naive Random Oversampling (First Image) model compared to the SMOTE Oversampling (Second Image) model showcases that both have similar balanced accuracy scores and results from their confusion matrixes and classification report as they are merely separated by a couple of decimal points. Both models have similar balanced accuracy scores but SMOTE has a slightly higher balanced accuracy score and scored higher in the classification report for both Low Risk and more importantly High Risk Credit Loans but the confusion matrix results lean towards Naive Random Sampling as it seemed to detect and assign a lot more cases. Again with both models being very close to one another either is acceptable and merely splitting hairs based on the tiny gap between the results.

Undersampling

image-20210630191757562

Unironically with undersampling their is lower balanced accuracy scores than the previous Oversampling models that were observed before but observed more cases according to the confusion matrix findings sees higher amounts of assigned cases when compared to one another. The classification report shows some increases compared to the oversampling models and some decreases depending on the value that is showcased but it seems as if this model did a better job in some cases in recognizing a lot more cases compared to the Oversampling model.

Combination (Over and Under) Sampling

image-20210630191838644

Now a combination of both Over and Undersampling shows no outstanding results when compared to each other but did showcase more admirable figures across the board as it has a higher accuracy score, comparable confusion matrix to the Oversampling model but not as high as the Undersampling model and all around higher values in the imbalanced classification report.

Balanced Random Forest Classifier

image-20210630191933973

This model gives us a higher accuracy score when compared to the previous models as of now but the confusion matrix skewed a lot more compared to the other models as well as we can see. The one mitigating factor that shows how this model and the next might be more applicable to use is the spread of the imbalanced classification report as it shows a more higher figures across the board compared to the previous models.

Easy Ensemble AdaBoost Classifier

image-20210630192004243

Last but not least, the Ensemble AdaBoost Classifier model has the highest balanced accuracy score out of all the models that we glanced through with the confusion matrix being comparable to the Balanced Random Forest Classifier and the highest figures of the classification report that we have seen. Overall out of all the models that we have went through, this is the model that performs well across all the reports and scores that were conducted.

Summary:
As we can see, these models for the most part had their pros and cons based on the scores and reports that were generated but overall it is easy to recommend to Jill that a great model to start with is the Easy Ensemble AdaBoost Classifier one and see how it performs with more data available and applied to it.
