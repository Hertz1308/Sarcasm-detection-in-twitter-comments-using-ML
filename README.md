# Sarcasm-detection-in-twitter-comments-using-ML

In this project, I developed a sentiment analysis model using a dataset of tweets. The initial step involved loading the data and performing exploratory analysis to understand the distribution of sentiments, which included categories like Negative, Positive, Neutral, and Irrelevant. After cleaning the data by removing missing values, I preprocessed the text by converting it to lowercase, removing punctuation and stopwords, and applying stemming.

For feature extraction, I utilized the TF-IDF (Term Frequency-Inverse Document Frequency) method, which transformed the preprocessed text into numerical vectors suitable for machine learning. I then split the dataset into training and testing sets, implementing a Decision Tree Classifier to predict sentiments based on the extracted features.

The model's performance was evaluated using accuracy scores and confusion matrices, achieving an accuracy of approximately 79.58%. Additionally, I calculated error metrics, including Mean Squared Error (MSE), Mean Absolute Error (MAE), and Root Mean Squared Error (RMSE), to further assess the model's predictions. The model was tested with various sample texts, demonstrating its ability to classify sentiments accurately
