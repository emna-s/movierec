# 🎬 Movie Recommendation System
## Goal
Develop an intelligent movie recommendation system using collaborative and content-based machine learning algorithms
## Technical Approach
We use a content-based filtering technique based on cosine similarity.
- Each movie is represented as a vector (using features like genre, description, rating, etc.).
- Cosine similarity measures how close two movies are in terms of their vector representation.
- The model ranks and recommends the top N most similar movies.
## Dataset
For this project, we used the MovieLens dataset. We chose it because it is clean, well-structured, and contains only the relevant information needed for building an effective movie recommendation system. 

Unlike other datasets, it doesn’t include unnecessary or redundant data, which makes it easier to preprocess and work with for collaborative and content-based filtering.
### NOTE
Please download the dataset from the following link: https://files.grouplens.org/datasets/movielens/ml-25m.zip and put it in the same folder as the movie recommendation app
## Expected Input
A movie title
## Expected Output
A list of Top-N recommended movies, ranked by similarity score.
Each recommendation includes:
- Movie title
- Similarity score
- Genre
## UI Features (WIP)
- Simple search bar for entering a movie title
- Display of recommendations with movie posters and similarity scores
- Option to select how many recommendations to display (e.g., Top-5, Top-10)
## Tools and Technologies
- Python (main language)
- Pandas (data manipulation)
- Scikit-learn (cosine similarity computation, model building)
- Streamlit (interactive web interface)
- NumPy (mathematical operations)
- Regex (searching, validating, and manipulating text patterns)
## Team Members
- Isra Abessi
- Emna Salah
- Yasmine Bouziri
