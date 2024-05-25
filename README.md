# BERT-Based-Sentiment-Analysis-for-Web-Scrapped-Movie-Reviews

**Repository Description:**

This repository contains two tasks related to sentiment analysis of movie reviews utilizing Python and machine learning techniques.

**Task 1: Web Scraping and Data Preparation**

Using the Beautiful Soup Python library, this project scrapes reviews for the movie "Lalsinghchadda" from IMDb's website. The scraped reviews are then organized and stored in a Pandas DataFrame, providing a structured format for further analysis.

**Task 2: Sentiment Analysis with BERT**

In the second task, a pre-trained BERT model for sentiment analysis is employed. Specifically, the `nlptown/bert-base-multilingual-uncased-sentiment` model from Hugging Face's model hub is utilized. This model is loaded and fine-tuned on the collected movie reviews data. The sentiment of each review is calculated using this retrained model.

**Key Components:**

- **Web Scraping**: Utilizes Beautiful Soup for efficient scraping of IMDb movie reviews.
- **Data Manipulation**: Pandas DataFrame is used to organize and manage the scraped reviews.
- **BERT Sentiment Analysis**: Leverages the `nlptown/bert-base-multilingual-uncased-sentiment` model from Hugging Face to perform sentiment analysis on the collected movie reviews.
- **Visualization**: Generates visualizations such as sentiment score count plots to provide insights into the sentiment distribution of the movie reviews.

**Resources:**

- **Hugging Face Model Hub Link**: [nlptown/bert-base-multilingual-uncased-sentiment](https://huggingface.co/nlptown/bert-base-multilingual-uncased-sentiment)

**Usage:**

1. Clone the repository.
2. Execute the provided Python scripts to perform web scraping and sentiment analysis.
3. Explore the generated Pandas DataFrame and visualizations to gain insights into the sentiment of the movie reviews.

**Contributions:**

Contributions and feedback are welcome! Feel free to open issues or pull requests to improve the functionality or documentation of this project.

**Disclaimer:**

This project is for educational and research purposes only. IMDb's terms of service should be respected when scraping data from their website.
