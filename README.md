# Twitter Sentiment Analysis App

## Overview

This Streamlit application performs sentiment analysis on a Twitter dataset, visualizing the results through interactive charts. The analysis includes sentiment distribution and the top 10 most frequent words in the dataset. The sentiment analysis is conducted using the TextBlob library, and visualizations are created using Matplotlib.

## Project Structure

1. **`sentiment_analysis.py`:**
   - The main script implementing sentiment analysis and creating visualizations using Streamlit.

2. **`twitter_data.csv`:**
   - The dataset containing Twitter data. Replace this file with your own dataset as needed.

3. **`requirements.txt`:**
   - Lists the required dependencies, including `streamlit`, `pandas`, `matplotlib`, `wordcloud`, and `textblob`.

4. **`README.md`:**
   - The README file providing an overview of the project and instructions on how to run the Streamlit app.

## Getting Started

Follow these steps to set up and run the Twitter Sentiment Analysis app:

1. Clone the repository to your local machine:
   ```bash
   git clone https://github.com/your-username/twitter-sentiment-analysis.git
   cd twitter-sentiment-analysis
   ```

2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Ensure you have a CSV file named `twitter_data.csv` with the appropriate Twitter dataset.

4. Run the Streamlit app:
   ```bash
   streamlit run sentiment_analysis.py
   ```

   Open your browser and navigate to the provided link to access the app.

## Sentiment Analysis

The app performs sentiment analysis on the Twitter dataset using the TextBlob library, which assigns a polarity score to each tweet.

## Visualizations

### Sentiment Distribution

The app displays a histogram illustrating the distribution of sentiment polarity in the dataset.

### Top 10 Most Frequent Words

The app generates a bar chart showcasing the top 10 most frequent words in the dataset, providing insights into common themes.



## Contributing

Contributions are welcome! If you have suggestions, find issues, or want to enhance the app, please feel free to open issues or submit pull requests.

