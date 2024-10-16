# Rotten Tomatoes Review Analysis

## Overview
This project analyzes movie reviews from Rotten Tomatoes using Python. The goal is to explore patterns in sentiment, analyze ratings distributions, and gain insights into how reviewers perceive different movies. We utilize natural language processing (NLP) techniques for sentiment analysis and data visualization libraries to present our findings.

## Project Structure
- `data/rottentomatoes_reviews.csv`: The dataset containing Rotten Tomatoes reviews.
- `notebooks/analysis.ipynb`: Jupyter Notebook containing data analysis, data cleaning, visualizations, and sentiment analysis.
- `README.md`: Detailed documentation of the project, including methodology, results, and instructions.
- `requirements.txt`: List of Python packages required to run the analysis.
  
## Dataset
The `rottentomatoes_reviews.csv` dataset contains the following columns:
- `review`: The full text of each review.
- `rating`: The numeric rating given by the reviewer (e.g., out of 5 stars).
- `movie_title`: The title of the movie being reviewed.
- `reviewer_name`: The name of the reviewer (optional).
- `date`: The date when the review was posted (optional).

## Analysis Methodology
The project follows a structured approach to analyze the movie reviews:

1. **Data Cleaning**:
   - Removed null values and duplicates from the dataset.
   - Preprocessed the review text by removing special characters, converting text to lowercase, and removing stop words.
   - Tokenization of review text for sentiment analysis.

2. **Exploratory Data Analysis (EDA)**:
   - Visualized the distribution of ratings across movies.
   - Analyzed the most common words in positive and negative reviews.
   - Identified trends in ratings over time (if date data is available).

3. **Sentiment Analysis**:
   - Performed sentiment analysis on the review text using [VADER, TextBlob, or another library].
   - Classified reviews into categories such as Positive, Negative, and Neutral.
   - Calculated average sentiment scores for different movies and genres.

4. **Data Visualization**:
   - Used `matplotlib` and `seaborn` to create charts and graphs.
   - Plotted the distribution of sentiment scores.
   - Visualized the correlation between sentiment and movie ratings.

## Results
Key findings from the analysis include:
- **Sentiment Trends**: The majority of reviews tend to be positive, with sentiment scores clustering around higher ratings.
- **Ratings Distribution**: Most movies have ratings that fall between 3 and 5 stars, indicating a generally favorable reception.
- **Common Words in Positive Reviews**: Words like "great," "amazing," and "excellent" are common in positive reviews, while "disappointing" and "boring" appear frequently in negative reviews.
- **Genre Sentiment**: Comedy movies tend to receive more varied reviews compared to dramas, which have more consistent sentiment.

## Technologies and Libraries Used
- **Python 3.8+**: The main programming language used.
- **Jupyter Notebook**: For analysis and visualization.
- **Pandas**: Data manipulation and analysis.
- **NumPy**: Numerical operations.
- **Matplotlib & Seaborn**: Data visualization.
- **NLTK/Spacy/TextBlob**: Natural language processing for sentiment analysis.

## Future Work
- **Model Improvement**: Explore advanced sentiment analysis models like BERT or custom-trained models.
- **Interactive Visualizations**: Use libraries like Plotly or Dash for interactive charts.
- **Expand Dataset**: Include reviews from other movie review platforms to generalize the findings.

## Getting Started

### Prerequisites
- Python 3.8+
- Jupyter Notebook

### Installation
1. Clone this repository:
   ```bash
   git clone https://github.com/Jkay97/rotten-tomatoes-analysis.git
   cd rotten-tomatoes-analysis



   
Contributing:
Contributions are welcome! If you'd like to improve this project, please fork the repository, create a new feature branch, and submit a pull request.
