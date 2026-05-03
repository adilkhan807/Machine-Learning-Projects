# Machine Learning Projects

This repository contains my machine learning projects.

## Projects

### 1. Movie Recommendation System tmdb dataset 
A content-based movie recommender system built using cosine similarity. It suggests movies based on user preferences.

## Technologies Used
- Python
- Pandas
- Scikit-learn
- NumPy

## Author
Adil 

##  How to Depoly
create 4 file
prock.file
#enter this code and run
web:sh setup.sh && streamlit run app.py
#create setuo.sh file
mkdir -p ~/.streamlit/

echo "\
[server]\n\
port = $PORT\n\
enableCORS = false\n\
headless = true\n\
\n\
" > ~/ . streamlit/config.toml
#gitignore file
streamlit
requests


deploy plateform heroku
