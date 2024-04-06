# Movie_Recommendation_Project

## Introduction
- The main intention of this project is to generate the top 5 matching movie names based on user input using similarity search. As the data is textual-based, implementing this requires text vectorization techniques and similarity metrics. Here, I used a text_vectorization (bag-of-words) approach with cosine similarity to find similarities between movies based on their textual features.

## Implementation Steps
### Feature Selection:
- Identified important features relevant to the project's objective.
### Feature Engineering:
- Transformed the dataset to extract only relevant information for the recommendation system.
### Text Vectorization:
- Used bag-of-words technique to represent movie descriptions.
- Selected top 5000 common words from all the movie descriptions.
- Implemented stop words removal and lemmatization techniques to preprocess the text data.
### Cosine Similarity:
- By creating the vectors calculated cosine similarity between movie vectors to determine their similarity.
- Utilized cosine similarity as a distance metric, as it provides a measure of similarity proportional to the angle between vectors.
### Top 5 Recommendations:
- Selects the top 5 movies with the highest cosine similarity scores as recommendations.
  
## Conclusion
- Implementing a movie recommendation system using text vectorization and cosine similarity enables generating relevant movie recommendations based on user preferences. This approach considers textual features of movies, allowing for effective recommendation even with large datasets. This project demonstrates practical application of natural language processing in recommendation systems, offering insights into text-based similarity analysis and recommendation generation.
