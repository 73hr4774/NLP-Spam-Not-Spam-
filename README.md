# SMS Spam Collection Dataset

This dataset contains a collection of SMS messages that have been classified as either spam or ham (not spam). It is a popular dataset for training and evaluating machine learning models for spam detection.

**Data Source:**

The dataset was originally collected by Tiago Almeida and José María Gómez Hidalgo and is publicly available on the UCI Machine Learning Repository. 

**Dataset Features:**

- **Category:** Indicates whether the message is spam or ham.
- **Message:** The text content of the SMS message.

**Dataset Size:**

The dataset contains 5,574 SMS messages.

**Data Preprocessing:**

- The `Category` column was converted to a numerical representation, with 1 representing spam and 0 representing ham.
- The `Message` column was used as input for training a machine learning model.
- The data was split into training and testing sets using `train_test_split` from scikit-learn.

**Model Training:**

- A Multinomial Naive Bayes model was trained on the training data using `MultinomialNB` from scikit-learn.
- The model was evaluated on the testing data using `classification_report` from scikit-learn.

**Results:**

- The model achieved high accuracy in classifying spam and ham messages.
- You can find the detailed classification report in the notebook.

**Usage:**

This dataset can be used for a variety of tasks, including:

- Training and evaluating machine learning models for spam detection.
- Exploring the characteristics of spam and ham messages.
- Developing new spam filtering techniques.
