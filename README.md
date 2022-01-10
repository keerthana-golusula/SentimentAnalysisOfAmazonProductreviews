# Sentiment Analysis Of Amazon Product Reviews

The overall project is about the classification of data (reviewdata) into three labels Positive, Negative and Neutral. Comparison between different machine learning models with our proposed BERT model to perform the sentiment analysis on our primary dataset that is different reviews of customers of the amazon products and other datasets like IMDB, etc...

The models we will be considering are given below:
        BERT Model (Proposed Model)
        Pretrained Models that we are comparing with our proposed model:
                1. Random Forest Classifier
                2. Multinomial Naive Bayes Classifier
                3. Complement Naive Bayes Classifier
                4. Bernoulli Naive Bayes Classifier
                5. Stochastic Gradient Descent Classifier

DATASET-SOURCE

Amazon Product Customer Reviews:

Complete Data: https://nijianmo.github.io/amazon/index.html
50K Data: https://drive.google.com/file/d/1sU8u5PgM5X80Tmw89poJ2CujPzvwG5ox/view
IMDB Reviews: https://drive.google.com/file/d/1qcjhAIwMFvycLatXN6B04- 8xyqPs0MiA/view?usp=sharing


USEFUL-LINKS
Project Report: https://drive.google.com/file/d/1aSiNB1AY9DX-Nlwi9FL-bZSrvulVE- Bv/view?usp=sharing
Our trained BERT Model : https://drive.google.com/file/d/1OYEmZHlm55ZcEdus8dkcyKII7yr- pft0/view?usp=sharing


RUNNING-THE-CODE
We have done this project in Google Collab and accessed files from Google drive
As the original dataset is huge, take the subset of data and upload it to google drive, it can be easily accessed from Collab while running the project.
Steps:
        1. Run the DataCleaning_AmazonDS.ipynb , here data cleaning is done for amazon dataset.
        2. Run the BERTMODEL_AmazonReviewDS.ipynb,
        Here we are using the above cleaned data, training the model, validating the test data and
        evaluating the results
        3. Run the Sentiment_Analysis_other_models.ipynb
 
 
Here we are performing amazon 50k data, fitting and prediction on different pretrained
models, with combination of different vectorization and learning rates. 4. Run the BERTMODEL_IMDB.ipynb, (corpora)
Here we are testing our proposed model with different dataset to understand the working with different inputs
Evaluation and Error Analysis:
After performing the above steps, we can observe that BERT model gives more accurate results compared to other models and all the evidence with proper tables, figures and Error Analysis are provided in the project report mentioned above.
