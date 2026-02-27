# Netflix Movies & TV Shows Clustering Project

## Problem Statement

This dataset consists of TV Shows and Movies available on Netflix as of 2019.  
The dataset is collected from Flixable, a third-party Netflix search engine.

The objective of this project is to:

- Perform Exploratory Data Analysis (EDA)
- Analyze content growth trends
- Compare TV Shows vs Movies production trends
- Identify country-wise production insights
- Cluster similar content using NLP techniques

---

## Dataset Information

- Total Records: 7,787
- Features: 12
- Content Types: Movies & TV Shows
- Dataset: `netflix_titles.csv`

---

## Project Workflow

### Data Cleaning
- Handled missing values (director, cast, country, rating)
- Dropped irrelevant columns
- Treated outliers in release_year
- Converted duration (Seasons → Minutes)

### Exploratory Data Analysis
- Production growth analysis by year
- Country-wise content distribution
- Rating distribution (TV-MA, TV-14, etc.)
- Month-wise content upload trends
- Category-wise frequency analysis
- Movie vs TV Show comparison

### Feature Engineering
- Created new features:
  - `no_of_category`
  - `date_added_month`
- Converted textual data for NLP processing

### NLP & Clustering
- Removed punctuation
- Removed stopwords using NLTK
- Text vectorization using TF-IDF / CountVectorizer
- Applied KMeans Clustering
- Evaluated clusters using Silhouette Score

---

## Key Insights

- Netflix significantly increased TV Shows after 2015.
- United States produces the highest content.
- December has the highest content upload.
- Most common rating: TV-MA.
- Most frequent categories:
  - International Movies
  - Dramas
  - Comedies

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- NLTK
- WordCloud

---

## How to Run the Project

1. Clone the repository
```
git clone https://github.com/yourusername/Netflix-Movies-TVShows-Clustering.git
```

2. Install required libraries
```
pip install -r requirements.txt
```

3. Open the Jupyter Notebook
```
jupyter notebook
```

4. Run all cells in:
```
Netflix_Movies_And_Tv_Shows_Clustering.ipynb
```

---

## Future Improvements

- Integrate IMDB ratings dataset
- Use advanced NLP embeddings (Word2Vec / BERT)
- Deploy interactive dashboard using Streamlit

---

## 👩‍💻 Author

**Sayali Shinde** 
🔗 LinkedIn: https://www.linkedin.com/in/sayali-shinde-b8b519261/

---
