
# Sentiment Analysis on Twitter Data

## Overview

This project focuses on performing sentiment analysis on Twitter data. The goal is to classify tweets into various sentiment categories such as Positive, Negative, Neutral, and Irrelevant. The analysis involves loading the dataset, performing data visualization, and building a machine learning model to predict sentiments.

## Project Structure

- **Data Loading**: The dataset is loaded and processed for analysis. Proper column names are assigned, and the data is prepared for visualization and modeling.
- **Data Visualization**: Word clouds and other visualizations are generated to understand the distribution of sentiments in the dataset.
- **Modeling**: A logistic regression model is built using `scikit-learn` with TF-IDF features extracted from the text data. The model is trained and evaluated for performance.

## Installation

To run this project, you will need to install the following Python packages:

```bash
pip install pandas matplotlib seaborn scikit-learn textblob wordcloud
```



## Data

The dataset used in this project is a CSV file containing tweets with their corresponding sentiments. The data is loaded and preprocessed to ensure it's ready for visualization and modeling.

## Visualizations

Word clouds and sentiment distribution graphs are generated to provide insights into the data. These visualizations help in understanding the common words associated with each sentiment and the overall sentiment distribution.

## Model

A logistic regression model is built to classify the sentiments of the tweets. The model is trained on a portion of the dataset and evaluated using various metrics such as accuracy, precision, recall, and F1-score.

## Inferences

- **Sentiment Distribution**: The dataset contains a balanced or imbalanced distribution of sentiments, which is visualized through graphs.
- **Model Performance**: The logistic regression model achieves certain accuracy and other metrics, indicating its effectiveness in sentiment classification.
- **Word Clouds**: The word clouds reveal the most common words associated with each sentiment, providing insights into the language used in positive, negative, neutral, and irrelevant tweets.

## Graphs

Graphs and visualizations generated from the notebook can be accessed in the notebook itself. If you prefer to view them separately, you can save the figures using the `matplotlib` library or view them directly in the Jupyter notebook.

## Conclusion

This project demonstrates the process of sentiment analysis on Twitter data, from data loading and visualization to model building and evaluation. The logistic regression model, combined with TF-IDF features, provides a baseline for sentiment classification that can be further improved with more sophisticated models.

## Acknowledgments

Special thanks to the developers of the libraries and tools used in this project, including `pandas`, `matplotlib`, `seaborn`, `scikit-learn`, `TextBlob`, and `WordCloud`.

## License

This project is licensed under the MIT License - see the LICENSE file for details.
