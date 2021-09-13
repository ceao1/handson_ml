# handson_ml
Excercises from "Hands-on Machine Learning with Scikit-learn, Keras &amp; Tensorflow" book


Special considerations:
    Split the data in train-test sets. For more accurate results use cross-validation, be carefull with the biased-data
    Use the pipeline class for save the steps used in data wrangling
    Use consistent performance measures 
        In classification (Supervised) you could use:
            * Confusion matrix: you can see in a matrix how the classifier understand the data, showing what is the performance of the classfier "How many times the classfier predict A when it really is B"
                Deeply you can use specific metrics for particular knowledge:
                    *Precision: Accuracy of the positive predictions
                    *Recall: Ratio of positive instances that are correctly detected
        ![Cofusion_matrix][assets/confusion_matrix.PNG]


Binary Classifier:

SGDC Classifier --> Uses randomness, if you want reporducible results use random state.
