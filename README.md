# SNLP_OLIDv1.0
I tried out several machine learning approaches with different features and several types of BERT models in order to find the best solution for predicting offensive speech in tweets. The OffensEval 2019 Dataset of SemEval 2019 - Task 6 was used for this purpose. 
 Four machine learning models including Logistic Regression, Random Forest, Neural Network and K-Neighbours Classifier were used based on features from ‘word’-Tf-Idf Vectorizer, and ‘char’-Tf-Idf vectorizer. Comparisons between models and hyperparameters were done. The best model using features of ‘char’-Tf-Idf Method was Random Forest, giving almost 0.75 accuracy and 0.71 F1 score; all models within ‘word’-Tf-Idf method showed rather equal results (≈ 0.68) with a maximum difference of 1.5 %.
 
The results show that the approach implemented using the BERT architectures, produced a model with the best results on both the training as well as the test sets. The best BERT model outperforms the best machine learning model by 7% in accuracy and 8% in macro avereged F-Score.

The code for machine learning models is to be find in a file called olidTask_snlp(ML_models).ipynb, the code for models using Simple Transformers is in the file olidTask_snlp(SimpleTransformer_models).ipynb.
