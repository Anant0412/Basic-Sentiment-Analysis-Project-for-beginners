The project is a Streamlit-based web application for sentiment analysis, employing both TextBlob and VADER (Valence Aware Dictionary and sEntiment Reasoner) to classify user-inputted text into positive, neutral, or negative sentiments. The application uses natural language processing (NLP) techniques to analyze text and present insights about overall sentiment and individual token-level sentiment.


Features

//Polarity and Subjectivity Analysis: Utilizes TextBlob to calculate the overall polarity and subjectivity of the input text. Polarity indicates whether the sentiment is positive, neutral, or negative, while subjectivity measures how subjective or objective the content is.
// Token-Level Sentiment Analysis: Uses VADER to analyze the sentiment of individual words within the text. Each word is classified as positive, neutral, or negative, based on its compound sentiment score.
// Interactive UI: Provides an easy-to-use Streamlit interface where users can input text, select polarity thresholds, and visualize results with data tables and charts.
//Sentiment Range Slider: Allows users to customize polarity thresholds, defining specific ranges for classifying sentiments as negative, neutral, or positive.
// Data Visualization: Displays results in an interactive bar chart, providing a clear view of polarity and subjectivity metrics.

Code Overview

// convert_to_df: This function converts the sentiment scores from TextBlob into a DataFrame for visualization.
//  analyze_token_sentiment: This function tokenizes the input text and classifies each token (word) based on its VADER compound sentiment score. Tokens are categorized as positive, negative, or neutral.
//  main: This function sets up the Streamlit app, including a sidebar, input form, and result display. It manages user interactions, such as text input and sentiment analysis, and handles the display of sentiment results, token analysis, and visualizations.

Libraries Used

i) Streamlit: For building an interactive web app
ii)TextBlob: For calculating text polarity and subjectivity.
iii)VADER (vaderSentiment): For token-level sentiment analysis.
iv)Pandas: For data manipulation.
v)Altair: For creating visualizations.


Usage

//Enter text in the input area and click "Analyze" to perform sentiment analysis.
//Use the slider to adjust polarity thresholds, affecting sentiment classification.
//View overall sentiment scores and token-level sentiments, along with visualizations.

    Enter text in the input area and click "Analyze" to perform sentiment analysis.
    Use the slider to adjust polarity thresholds, affecting sentiment classification.
    View overall sentiment scores and token-level sentiments, along with visualizations.

This README provides a comprehensive overview of the project, its features, and instructions on usage.
