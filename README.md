***Sentiment Analysis on Airline Tweets***

**Problem Definition:**
Given tweets about six US airlines, the task is to predict whether a tweet contains positive, negative, or neutral sentiment about the airline. This is a supervised learning task, categorizing text strings into predefined sentiment categories.

**Solution Overview:**
The project follows a standard machine learning pipeline, covering data exploration, text preprocessing, and model training.

**Libraries Used:**
- NumPy
- Pandas
- Regular Expressions (re)
- NLTK (Natural Language Toolkit)
- Matplotlib
- Scikit-Learn
- Seaborn

**Dataset:**
The dataset consists of tweets about US airlines, publicly available on [GitHub](https://raw.githubusercontent.com/kolaveridi/kaggle-Twitter-US-Airline-Sentiment-/master/Tweets.csv) or the folder with all the data is also uploaded.

**Exploratory Data Analysis (EDA):**
- Analyzed the distribution of tweets among different airlines.
- Explored the overall sentiment distribution across all tweets.
- Examined sentiment distribution for each individual airline.

**Data Cleaning and Preprocessing:**
- Removed special characters, single characters, and extra whitespaces.
- Converted text to lowercase for consistency.
- Represented text in numeric form using TF-IDF (Term Frequency-Inverse Document Frequency).

**Machine Learning Model:**
- Utilized RandomForestClassifier from Scikit-Learn.
- Trained the model on the processed data.

**Evaluation:**
- Split the data into training and testing sets.
- Utilized confusion matrix, classification report, and accuracy score for evaluation.
- Achieved an accuracy of approximately 75.30%.

**Conclusion:**
This sentiment analysis project successfully categorizes tweets about US airlines into positive, negative, or neutral sentiments. The accuracy achieved demonstrates the effectiveness of the RandomForestClassifier in handling such classification tasks. Consider exploring other machine learning algorithms to potentially improve accuracy. The project provides insights into public sentiment, essential for understanding customer opinions and feedback.
