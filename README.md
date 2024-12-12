# Lyrics Analysis using LDA and Sentiment Analysis

This project investigates how the themes, sentiments, and topics in popular music lyrics have evolved over time. By applying Latent Dirichlet Allocation (LDA) for topic modeling and sentiment analysis, I aim to analyze shifts in emotional tones, genre trends, and thematic content across different decades of music.

## Research Questions

1. **How have the themes and sentiments expressed in popular music lyrics changed over time?**
   - Analyze the evolution of lyrical themes and sentiments by decade.
   
2. **What trends can be observed in the popularity of different genres and the emotional tone of lyrics across various decades?**
   - Identify trends in genre popularity and correlate them with the sentiment and emotional tones of lyrics.
   
3. **What are the dominant topics in song lyrics over different decades, and how do these topics evolve over time?**
   - Use topic modeling (LDA) to identify key topics in lyrics across decades and explore how these topics have changed.

## Project Stages

1. **Exploratory Data Analysis (EDA) of Numerical Data**
   - Analyze the distribution of numerical data 
   - Explore trends in the data across decades and artists, and rank
   - Visualize and summarize key numerical features to identify patterns before further analysis.

2. **Data Collection and Preprocessing**
   - Isolate song lyrics from the dataset.
   - Clean and preprocess the lyrics (e.g., tokenization, removing stop words, stemming/lemmatization).

3. **Topic Modeling with LDA**
   - Apply Latent Dirichlet Allocation (LDA) to identify topics within the lyrics.
   - Coherence score

4. **Model Comparison**
   - Compare three different machine learning models (Logistic Regression, Random Forest, and Support Vector Machine) in classifying the dominant topic of song lyrics
   - Evaluate performance metrics (e.g., coherence score for topics, accuracy, and F1-score)

4. **Sentiment Analysis**
   - Perform sentiment analysis on the lyrics to explore emotional tones (positive, negative, neutral).
   - Analyze sentiment trends across decades.

6. **Visualization and Results**
   - Visualize the topics and sentiment trends over time.
   - Explore how topics and emotional tones have evolved in popular music.


## Repository Contents

-data was retreived from: https://www.kaggle.com/datasets/brianblakely/top-100-songs-and-lyrics-from-1959-to-2019 
- `README.md`: Project overview and instructions for setting up and running the analysis.
- `top100.ipynb': First iteration of code
- `top100V2.ipynb': Updated iteration of code with initial results
- 'top100V2.ipynb - Colab.pdf' PDF of technical report
- `top100V3(2).ipynb': Final iteration of code with complete results
- 'top100V3.ipynb - Colab.pdf' final PDF of technical report
