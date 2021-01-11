**Machine Learning Case Study: predicting the rating of a movie**

A Data Science Machine Learning approach to predict which films will be highly rated based on different characteristics.
Dataset Information

The dataset used for the current case study has 4803 samples and 20 inputs.

    tmdb_5000_movies.csv dataset for download here.

**Attribute Information**

The datset contains the following information.

Input variables:

    budget (numeric)
    genres (categoric)
    homepage (categoric)
    id (numeric)
    keywords (categoric)
    original_labguage (categoric)
    original_title (categoric)
    overview (categoric)
    popularity (numeric)
    poduction_companies (categoric)
    production_countries (categoric)
    release_date (categoric)
    revenue (numeric)
    runtime (numeric)
    spoken_languages (categoric)
    status (categoric)
    tagline (categoric)
    title (categoric)
    vote_count (numeric)

Output variable (desired target):

    vote_average (numeric)

**Machine Learning problem and objectives**

Could it be possible to predict the success of a movie before it is released? The answer to this question comes from this supervised regression challenge. The goal is to train the best machine learning model selecting the key-features that can accurately predict the vote_count of each submitted movie.
