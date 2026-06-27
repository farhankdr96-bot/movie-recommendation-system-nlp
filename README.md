# 🎬 NLP-Based Movie Recommendation System

## 📌 Project Overview

Recommendation systems are widely used by streaming platforms to improve user experience by suggesting relevant content. This project implements a Content-Based Movie Recommendation System using Natural Language Processing (NLP) techniques.

The system analyzes movie metadata such as genres, keywords, cast, crew, and overview, then recommends similar movies based on textual similarity.

---

## 🎯 Problem Statement

With thousands of movies available online, users often struggle to find content matching their interests. The objective of this project is to build an intelligent recommendation engine that suggests movies similar to a selected movie using NLP and Machine Learning techniques.

---

## 📊 Dataset

The project uses movie metadata datasets containing:

- Movie Title
- Genres
- Keywords
- Overview
- Cast
- Crew
- Popularity
- Release Date

### Data Sources

- Movies Dataset
- Credits Dataset

---

## 🛠 Technologies Used

- Python
- Pandas
- NumPy
- NLTK
- Scikit-learn
- Jupyter Notebook

---

## 🔄 Project Workflow

### 1. Data Collection
- Loaded movie and credits datasets.
- Merged datasets using movie title.
- Selected relevant attributes.

### 2. Data Preprocessing
- Removed missing values.
- Extracted important metadata.
- Cleaned text data.
- Combined features into a single tag column.

### 3. NLP Processing

Applied Natural Language Processing techniques:

- Tokenization
- Text Cleaning
- Lowercase Conversion
- Stemming
- Feature Engineering

### 4. Feature Extraction

Used:

- Count Vectorizer

to transform movie text data into numerical vectors.

### 5. Similarity Computation

Applied:

- Cosine Similarity

to calculate similarity scores between movies.

### 6. Recommendation Engine

When a movie title is provided, the system retrieves the most similar movies based on content similarity.

---

## 📈 Key Features

✅ Content-Based Filtering

✅ NLP Text Processing

✅ Count Vectorization

✅ Cosine Similarity

✅ Personalized Recommendations

✅ Metadata-Based Similarity Analysis

---

## 📂 Project Structure

Movie-Recommendation-System-NLP/

├── movie_recommendation.ipynb

├── movies.csv

├── credits.csv

├── README.md

├── requirements.txt

└── images/

---

## 🚀 Installation

Clone the repository:

```bash
git clone https://github.com/yourusername/movie-recommendation-system-nlp.git
```

Navigate to the project folder:

```bash
cd movie-recommendation-system-nlp
```

Install required libraries:

```bash
pip install -r requirements.txt
```

Run Jupyter Notebook:

```bash
jupyter notebook
```

---

## 🎯 Example

### Input

```text
Avatar
```

### Recommended Movies

```text
Guardians of the Galaxy
John Carter
Star Trek
Aliens
Titan A.E.
```

---

## 📚 Skills Demonstrated

- Natural Language Processing (NLP)
- Recommendation Systems
- Feature Engineering
- Text Vectorization
- Cosine Similarity
- Data Preprocessing
- Machine Learning
- Python Programming

---

## 🚀 Future Improvements

- Collaborative Filtering
- Hybrid Recommendation System
- Deep Learning Recommendations
- Streamlit Web Application
- User-Based Recommendations
- Real-Time Personalization

---

## 🎓 Learning Outcomes

This project demonstrates:

- NLP-based feature extraction
- Content-based recommendation systems
- Similarity measurement techniques
- Text preprocessing workflows
- Practical machine learning applications

---

## 👨‍💻 Author

Mohd Farhan
