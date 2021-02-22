# PHD
Here our objective is to build a NLP model should classify review as Positive, Negative or Neutral of various medical companies and each review is associated with a medicine name. But the reviews provided by the users are complex in nature and some reviews contain information about multiple medicines as well,so It should generate sentiment scores based on overall data i.e. incorporating the complex reviews information. Approach to the problem :

Collect and extract train and test data given in the dataset
Perform Visualizations & EDA on the data gathered.
Build a robust local validation strategy
Perform Classification using a NLP pipeline to predict sentiment
Plot the learning curves for your model and pick the best model by considering the bias-variance trade off.

Brief about the project : Collecting the train and test data and perform Text pre-processing and NLP PIPE LINE BUILDING (TOKENIZATION,CONVERING TO LOWER CASE,LEMMATIZATION) 
Visualized the text like what are the top words (considered N-GRAMS also) in the document, top words for the medicines where there is negative and positive growth respectively (Word cloud has been used in this). 
Then built NLP pipe line (Cleaning the text, Tokenization, lemmatization,etc.), in order to build TFIDF matrix .
STRATEGY: Counted all the positive , negative ,neutral words and multiplied them with their corresponding MODAL values.
Based on the positive, negative,neutral word domination. 
Also built classification models like Logistic regression, Linear SVM,RBF kernel SVM, Naïve Bayes, XGBOOST, Gradient Boosting, Random Forest, Decision Trees, KNN .

To check the model stability calculated the F1 score and accuracy of all the models on train data . 
Used Generate sentiment scores based on overall data i.e. incorporating the complex reviews information.
VADER (Valence Aware Dictionary and sEntiment Reasoner) is a lexicon and rule-based sentiment analysis tool that is specifically attuned to sentiments expressed in social media.
