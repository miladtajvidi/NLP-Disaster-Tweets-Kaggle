<p align="center">
  <img src="./nlp.png" alt="Description of image" width="300">
</p>

# NLP-Disaster-Tweets-Kaggle

## Project Overview
This project involves building a machine learning model to classify tweets as related to real disasters or not. The goal is to accurately identify tweets about genuine disasters, helping to filter out noise and surface critical information. This project is based on a Kaggle competition using natural language processing (NLP) techniques.

## Approach
The project progresses through several stages, each building towards a robust classification model:

* Exploratory Data Analysis (EDA):

  * Data preprocessing includes checking for missing values, handling null entries, and filling in missing values in categorical columns.
  * Feature engineering involves adding new features, such as tweet length, and basic text cleaning to remove duplicates and standardize inputs.
* Model Selection and Training:

  * A lightweight DistilBERT model is selected for this project due to its balance of performance and computational efficiency.
  * Different hyperparameters are tested, including batch size, learning rate, and epoch count, to optimize the model’s performance.
* Performance Evaluation:

  * A confusion matrix is used to evaluate the model’s performance on both the training and validation sets.
  * Predictions on test data are outputted to a submission file for scoring, with the F1 score being the primary evaluation metric.
## Results and Future Improvements
* Model Performance: The project achieved F1 scores of around 0.8, indicating reasonable accuracy in distinguishing between disaster and non-disaster tweets.
* Future Work:
  * Implement callbacks and early stopping to prevent overfitting.
  * Use a learning rate scheduler to fine-tune the learning rate during training.
  * Experiment with more advanced text preprocessing techniques, such as handling abbreviations, slang, URLs, and hashtags, which could improve model performance.
## References
[Natural Language Processing with Disaster Tweets](https://www.kaggle.com/c/nlp-getting-started/overview)
