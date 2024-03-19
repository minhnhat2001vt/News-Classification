# News-Classification
The goal of this project is to build a Supervised Learning Model that can classify online Vietnamese news by different topics.
## Project overview
### 1. Dataset
- The data set includes 41,276 electronic articles collected from online newspapers, including: VnExpress, Thanh Nien Newspaper, Nhan Dan Newspaper, Tien Phong Electronic Newspaper, ...
- Divided into 10 different topics: Music, Travel, Technology, Culture, Education, Life, Law, Business, Entertainment, Sports.
### 2. Data Preprocessing
- Data Cleaning: Stopwords removal, ppercase letters normalization, puctuations and special characters removal.
- Text tokenizing: using Word-based tokenizer for both single words and compound words.
- Splitting data into Train and Test set.
- Text Representation: Bag of Words, TF-IDF, Word Embedding
- Dimesional Reduction
### 3. Model Training and Evaluating
- Build Machine Learning models (Multinomial Naive Bayes, Logistic Regression, Random Forest, SVM) and Deep Learning models (MLP, CNN, Bi-LSTM).
- Evaluate the model performance with test set using Precision, Recall, F1 Score and Accuracy Percent. This  project achieved 90% accuracy on the Test set for the Machine Learing model (SVM) and 85% for the Deep Learning Model (BiLSTM)
- Optimize the Hyper-parameters of the models to increase model performanc
