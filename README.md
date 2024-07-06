# Movie Recommender System

Welcome to the Movie Recommender System! This project leverages vectorization and cosine similarity to suggest the top five movies based on user input. The application is built using Streamlit for a user-friendly and interactive interface.

## How It Works

The recommender system works in the following way:

1. **Data Loading**: The movie dataset is loaded from a CSV file, which contains information about various movies.
2. **Text Vectorization**: The descriptions of the movies are vectorized using the TF-IDF (Term Frequency-Inverse Document Frequency) method to convert text data into numerical vectors.
3. **Cosine Similarity Calculation**: Cosine similarity is computed between the vectorized descriptions to measure the similarity between movies.
4. **Recommendation Engine**: Based on the cosine similarity scores, the system identifies and recommends the top five movies that are most similar to the user’s input movie.
5. **Interactive User Interface**: The application is powered by Streamlit, providing a simple and interactive interface where users can enter a movie they like and get recommendations instantly.


