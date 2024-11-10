**Movie Recommended System**

This repository contains a Movie Recommendation System, built using machine learning and natural language processing techniques. The system analyzes user preferences and movie attributes to suggest personalized recommendations. By identifying patterns in user ratings and movie features, this model enhances the viewing experience and helps users discover new movies.

![Alt text](https://repository-images.githubusercontent.com/687484722/18f7170c-be7c-45d5-92c6-e6a31483f6a1)
**Project Overview**

This project aims to develop a movie recommendation system using machine learning and natural language processing techniques. The system will analyze user preferences and movie attributes to suggest personalized recommendations.

**Objective**

1. Develop a recommendation model using collaborative filtering and content-based filtering
2. Analyze user ratings and movie features to identify patterns
3. Evaluate model performance using relevant metrics
4. Implement model deployment strategy

**Dataset Overview**

1. id: Unique identifier for each movie.
2. title: Movie title.
3. original_title: Original title of the movie (before translation).
4. homepage: Official website of the movie.
5. tagline: Catchphrase or slogan for the movie.
6. status: Current status of the movie (e.g., released, upcoming).
7. genres: List of genres associated with the movie (e.g., action, comedy).
8. keywords: List of relevant keywords for the movie (e.g., space, adventure).
9. overview: Brief summary of the movie.
10. cast: List of main cast members.
11. crew: List of key crew members (e.g., director, screenwriter).
12. director: Name of the movie director.

**Modeling Approach**

Data Preprocessing:
Handle missing values and outliers.
1. Tokenization: Split text into individual words.
2. Stopword removal: Remove common words (e.g., "the", "and").
3. Stemming: Reduce words to base form.
4. Removing special characters and punctuation.


Model Selection:
To recommend movies, we employed a content-based filtering approach using Cosine Similarity and TfidfVectorizer.

Methodology:

1. Data Preprocessing: We preprocessed the movie metadata by converting the text features (overview, genres, keywords) into numerical representations using TfidfVectorizer.

2. Similarity Measurement: We calculated the cosine similarity between the user's preferred movies and the entire movie dataset.

3. Recommendation Generation: We ranked movies based on their similarity scores and recommended the top-N movies.


[code](https://github.com/Aakash1379/movie_recommended_system/blob/main/Movie%20Recommended.ipynb)

**Usage**

Data Loading: Load your movies dataset in the notebook.
Data Preprocessing: Follow the preprocessing steps to clean and transform the data.
Feature Engineering: Apply feature engineering methods as defined in the notebook.
Model Training and Evaluation: Train and evaluate the model using the chosen techniques and metrics.

**Technologies Used**

Natural Language Processing:

Cosine Similarity: Measure of similarity between vectors (text documents)

TfidfVectorizer: Converted text features into numerical representations.

Python: Programming language for model development and data manipulation.

Jupyter Notebook: Interactive environment for data analysis and modeling.




**Benefits**

User Benefits:

1. Personalized Experience: Receive tailored movie recommendations based on individual preferences.
2. Discovery of New Movies: Explore new genres, directors, and actors.
3. Time-Saving: Quickly find relevant movies, reducing browsing time.
4. Improved Engagement: Enhanced viewing experience through relevant suggestions.
5. Increased Satisfaction: Watch movies that align with interests and tastes.

Business Benefits:

1. Increased Revenue: Boost sales through targeted recommendations.
2. Customer Retention: Enhance user loyalty through personalized experiences.
3. Competitive Advantage: Differentiate from competitors with advanced recommendation capabilities.
4. Improved User Data: Collect valuable insights on user preferences and behavior.
5. Targeted Advertising: Deliver relevant ads to specific user segments.

**Contributor**

Aakash Prathipati
