# 🎥 Movie Recommender System

## Overview

This project is a Movie Recommender System that suggests movies to users based on their preferences. Using the cosine similarity algorithm, it identifies and recommends movies similar to a user's selected movie by analyzing their features.

## Project Workflow

1. **Data Exploration**  
   - Examined and visualized key movie attributes such as genres, ratings, and popularity.  
   - Ensured data consistency by handling missing values and duplicates.  

2. **Data Preprocessing**  
   - Transformed text-based features (like genres and descriptions) into numerical representations.  
   - Standardized features for accurate similarity calculations.  

3. **Cosine Similarity Algorithm**  
   - Calculated pairwise similarity scores between movies based on their features.  
   - Ranked movies to recommend the most relevant ones for a user-selected title.  

4. **User Interface**  
   - Developed an interactive system where users input a movie name to get tailored recommendations.  

## Datasets

The dataset includes the following features:  
- **Movie Title**: Title of the movie.  
- **Genres**: Genres associated with the movie.  
- **Description**: A brief synopsis of the movie.  
- **IMDB Rating**: Rating of the movie.  
- **Popularity**: A score indicating the movie's popularity.  

## Installation

1. **Clone the repository**:  
   ```bash
   git clone https://github.com/chandkund/Movie-Recommender-System.git
   ```  
2. **Navigate to the project directory**:  
   ```bash
   cd Movie-Recommender-System
   ```  
3. **Install required packages**:  
   ```bash
   pip install -r requirements.txt
   ```

## Usage

Run the script to get movie recommendations:  
```bash
python movie_recommender.py
```

## Results

The recommender system effectively suggests movies that align with user preferences. Using cosine similarity, it ensures accurate and personalized recommendations, enhancing the overall movie discovery experience.

