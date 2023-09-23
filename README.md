# Online-Sexism-Detection


This repository is dedicated to the task of online sexism detection using machine learning and deep learning techniques. The dataset contains the following columns: `rewire_id`, `text`, `label_sexist`, `label_category`, and `label_vector`. The project focuses on classifying online content as either sexist or non-sexist.

## Data Preprocessing

The data preprocessing steps involve cleaning and preparing the text data for classification:

- **HTML Tag Removal**: HTML tags are removed from the text data using regular expressions.
- **Lowercasing**: Text is converted to lowercase.
- **Punctuation and Number Removal**: Punctuation and numbers are replaced with spaces.
- **Single Character Removal**: Single characters are removed.
- **Stopword Removal**: Common English stopwords are removed from the text.

## Model Training and Evaluation

### Machine Learning Models
- Text data is tokenized and vectorized using the CountVectorizer.
- The dataset is split into training and testing sets.
- Machine learning models like Logistic Regression, K-Nearest Neighbors (KNN), Bernoulli Naive Bayes (BernoulliNB), Multinomial Naive Bayes (MultinomialNB), Support Vector Machine (SVM), and Random Forest are trained and evaluated using F1 scores.

### Deep Learning Models
- Word tokenization and sequence padding are applied to the text data.
- Pre-trained word embeddings from GloVe are used for word representation.
- Several deep learning models, including Long Short-Term Memory (LSTM), Gated Recurrent Unit (GRU), and Bidirectional LSTM, are constructed for classification.
