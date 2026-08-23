# Fake News Classifier

## About the Project

Fake News Classifier is a machine learning project that identifies whether a news article is fake or real.

The project uses Natural Language Processing (NLP) and machine learning techniques to process news text, extract useful features, train a classification model, and predict the category of new articles.

The complete project is implemented using Python and Jupyter Notebook.

## Objectives

* Identify fake and real news articles
* Clean and preprocess text data
* Apply Natural Language Processing techniques
* Convert text into numerical features
* Train a machine learning classification model
* Evaluate model performance

## Technologies Used

* Python
* Jupyter Notebook
* Pandas
* NumPy
* Scikit-learn
* Matplotlib
* Seaborn
* Natural Language Processing

## Project Workflow

1. Load the true and fake news datasets
2. Explore the data
3. Clean and preprocess the text
4. Extract text features
5. Split the data into training and testing sets
6. Train the machine learning model
7. Evaluate the model
8. Predict whether news is fake or real

## Project Structure

```text
fake_news_classifier/
│
├── FakeNewsClassifier.ipynb
├── true.csv
├── fake.csv
├── README.md
└── .gitignore
```

The `true.csv` and `fake.csv` files are the datasets used for training and testing the model.

Because the dataset files are larger than 25 MB, they may need to be stored using Git LFS.

## Data Preprocessing

The text data is cleaned before training the model. The preprocessing process may include:

* Converting text to lowercase
* Removing punctuation
* Removing unnecessary characters
* Removing stop words
* Cleaning unwanted text
* Preparing the text for feature extraction

## Feature Extraction

The text data is converted into numerical features so that it can be used by the machine learning model.

TF-IDF (Term Frequency-Inverse Document Frequency) can be used to represent the importance of words in the news articles.

## Model Training

The true and fake news datasets are combined and prepared for model training.

The data is divided into training and testing sets. The training data is used to build the machine learning model, while the testing data is used to evaluate its performance.

The model predicts whether a given news article is fake or real.

## Model Evaluation

The model can be evaluated using the following metrics:

* Accuracy
* Precision
* Recall
* F1 Score
* Confusion Matrix

## Installation

Clone the repository:

```bash
git clone https://github.com/nisargdesai2036-ui/fake_news_classifier.git
```

Move into the project directory:

```bash
cd fake_news_classifier
```

Install the required libraries:

```bash
pip install pandas numpy scikit-learn matplotlib seaborn jupyter
```

## Running the Project

Start Jupyter Notebook:

```bash
jupyter notebook
```

Open the following notebook:

```text
FakeNewsClassifier.ipynb
```

Run the notebook cells in order to load the `true.csv` and `fake.csv` files, preprocess the data, train the model, evaluate the results, and make predictions.

## Future Improvements

* Improve model accuracy
* Compare different machine learning algorithms
* Use advanced NLP techniques
* Implement deep learning models
* Create a web application
* Deploy the model online
* Add real-time fake news detection

## Author

Nisarg Desai

GitHub: https://github.com/nisargdesai2036-ui

## License

This project is created for educational and learning purposes.

