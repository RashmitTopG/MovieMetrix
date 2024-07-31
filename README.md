# MovieMetrix

MovieMetrix is a personalized movie recommendation system built using Streamlit. The application leverages natural language processing (NLP) techniques and machine learning to provide tailored movie recommendations based on user preferences and moods.

## Features

- **Personalized Recommendations**: Input your movie preferences and get a list of recommended movies based on cosine similarity.
- **Mood-Based Recommendations**: Enter your current mood to receive movie recommendations that match your sentiment using TextBlob sentiment analysis.
- **Filter Movies**: Filter movies by director, actor, or genre for more targeted recommendations.

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/RashmitTopG/MovieMetrix.git
   ```
2. Navigate to the project directory:
   ```bash
   cd MovieMetrix
   ```
3. Install the required packages:
   ```bash
   pip install -r requirements.txt
   ```
4. Download the necessary NLTK data:
   ```python
   import nltk
   nltk.download('punkt')
   nltk.download('stopwords')
   nltk.download('wordnet')
   ```

## Technologies Used

- **Streamlit** for building the web application
- **Pandas** for data manipulation
- **scikit-learn** for vectorization and similarity calculations
- **TextBlob** for sentiment analysis
- **NLTK** for text preprocessing

## Screenshots of the project have been uploaded above.
