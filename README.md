<img width="818" alt="Screenshot 2024-11-22 at 1 02 38 PM" src="https://github.com/user-attachments/assets/b267c5d7-80af-4400-81c4-c82a4087430c">

# **Movie Recommender System**

This project is a Content-Based Movie Recommender System built using Python. It processes movie data to recommend similar movies based on genres, keywords, cast, crew, and overview using natural language processing and machine learning techniques.


## **FEATURES**

 ## Data Preprocessing:
	•	Extracted and cleaned key features like genres, keywords, cast, crew, and movie overview.
	•	Applied text processing to handle data effectively.
## Content-Based Recommendation:
	•	Recommends movies based on similarity of content using feature vectors.
## Natural Language Processing (NLP):
	•	Used NLTK to process text data.
## Efficient Vectorization:
	•	Combined textual and categorical data to create a single feature vector for recommendations.


## **How It Works**

## Data Preprocessing:
	•	Extracted relevant features: genres, keywords, cast, crew, and overview.
	•	Converted JSON-like strings to Python objects using ast.literal_eval.
	•	Filtered and formatted data for better processing.
## Feature Engineering:
	•	Combined features like genres, keywords, cast, crew, and overview into a single string.
	•	Removed spaces and applied text normalization.
## Vectorization:
	•	Applied TF-IDF or Count Vectorization (customizable) to create feature vectors.
	•	Measured similarity using cosine similarity.
## Recommendation:
	•	Given a movie title, the system recommends top N similar movies based on cosine similarity of feature vectors.


## **Libraries Used**

	•	Pandas: For data manipulation and analysis.
	•	NumPy: For numerical computations.
	•	NLTK: For natural language processing and cleaning the text data.
	•	ast: To safely evaluate string representations of Python objects.
	•	scikit-learn: For vectorization and similarity calculations.





 
