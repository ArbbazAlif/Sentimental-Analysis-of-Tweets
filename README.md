# Sentiment Analysis of Tweets

This project performs sentiment analysis on a dataset of tweets using Natural Language Processing (NLP) techniques. The notebook includes data preprocessing, visualization, feature extraction using TF-IDF, and classification using machine learning algorithms such as Logistic Regression and Naive Bayes.

## 🧪 Features

- Importing and preprocessing Twitter data  
- Data visualization using word clouds and bar plots  
- Tokenization and TF-IDF vectorization  
- Model training and evaluation (Logistic Regression & Naive Bayes)  
- Sentiment prediction on new tweets  

## 📁 Project Structure

```
Sentimental_Analysis_of_Tweets/
│
├── Sentimental_Analysis_of_Tweets.ipynb  # Main Jupyter notebook
├── README.md                             # Project overview and instructions
└── requirements.txt                      # Dependencies (create if needed)
```

## 🛠️ Installation

1. Clone the repository:
```bash
git clone https://github.com/yourusername/Sentimental_Analysis_of_Tweets.git
cd Sentimental_Analysis_of_Tweets
```

2. Create a virtual environment and install dependencies:
```bash
pip install -r requirements.txt
```

## 🧾 Dependencies

You can generate a `requirements.txt` using:
```bash
pip freeze > requirements.txt
```

Main libraries used include:
- pandas
- numpy
- matplotlib
- seaborn
- sklearn
- nltk
- wordcloud

## 🚀 Usage

1. Launch the Jupyter Notebook:
```bash
jupyter notebook
```

2. Open `Sentimental_Analysis_of_Tweets.ipynb` and run the cells step-by-step.

## 📊 Results

- The notebook demonstrates good performance with accuracy and confusion matrix metrics.
- Visualizations show sentiment distributions and most frequent words for each sentiment.

## 📌 To-Do

- Add support for streaming Twitter data using Tweepy
- Extend to multi-class sentiment classification
- Export model for deployment

## 📝 License

This project is open-source under the MIT License.
