# Movie-Recommendation-System

## Description
Creation of ML and NLP Movie Recommendation System for recommending other related movies using proper Feature Engineering, TF-IDF Vectorization and Cosine Similarity for detecting the similarities between different movies.

## Objectives
- Data Inspection to ensure good data preprocessing
- Feature Engineering
- JSON-like structure extraction
- Recommendation Function Creation
- Testing Recommendation 


## Tools & Library Used
- Python
- Pandas
- Scikit-learn
- Joblib

## ML & NLP Workflow
- Feature Selection
- Feature Engineering & Text Combination
- TF-IDF Vectorization
- Cosine Similarity

## Findings
- TF-IDF combined some important features together because vectorizer can only use one text column rather than two/more
- Cosine Similarity is then used to find similarities between movies categories mathematically before the creation of "recommendation function" that gives us the actual recommendation we need after inputting any movie name

## Conclusion
JSON-like structure was transformed to plain text for effective vectorization. Recommendation system performs accurately(giving us 5 similar movies which was set to default) in recommending related movie content


## Author
Amos Kolawole
