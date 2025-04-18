# Classification-and-Clustering-of-News-Articles
📰 Machine Learning project on Classification and Clustering of Indian News Articles using TF-IDF and Word2Vec Representations
News Article Text Classification using Machine Learning
This project demonstrates a multi-class text classification system built to categorise Indian news articles into various categories like sports, business, entertainment, education, and technology. It involves comprehensive data cleaning, feature extraction using TF-IDF, and applying machine learning models to classify news content.

📂 Dataset
The dataset includes multiple CSV files (business_data.csv, entertainment_data.csv, education_data.csv, sports_data.csv, and technology_data.csv) extracted from a zipped folder Indian_News_Data.zip. Each file contains:

headlines

description

content

category

These are combined and processed for model training.

🔧 Project Workflow
Data Loading & Merging

Multiple CSVs are read and concatenated into a single DataFrame.

Data Preprocessing

Combined headlines, description, and content into a single Content column.

Converted category labels to numeric values (0 to 4).

Removed unwanted columns like URLs and index.

Applied text cleaning:

Lowercasing

Removing punctuation, digits, stopwords

Lemmatisation using SpaCy and NLTK

Removing named entities

Feature Extraction

Used TF-IDF Vectorizer for converting text into numerical features.

Model Training & Evaluation

Split the dataset into training and testing sets.

Trained classification models (e.g., Logistic Regression, Multinomial Naive Bayes).

Evaluated models using metrics like accuracy, precision, recall, F1-score.

Model Performance

Displayed confusion matrix and classification report.

🛠️ Technologies Used
Python

Pandas, NumPy

Scikit-learn

NLTK, SpaCy

Matplotlib, Seaborn

📈 Sample Results
The classification model achieved good accuracy on the test set and provided clear classification metrics across all categories.
