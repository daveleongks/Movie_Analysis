# Movie_Analysis Project

## Objective
The primary objective is to conduct in-depth exploratory data analysis (EDA) and feature engineering to uncover insights into movie ratings. By leveraging feature engineering techniques, I aim to identify key features that influence the ratings of the movies.

## Analysis Tasks:

### 1. Create Master Dataset
Create a new dataset named Master_Data, which includes the following columns: MovieID, Title, UserID, Age, Gender, Occupation, and Rating. This consolidated dataset will facilitate comprehensive analysis.

### 2. Exploratory Data Analysis (EDA) not limited to below areas:
- **User Age Distribution**: Visualize the distribution of user ages to understand the demographics of the user base.
- **User Rating of "Toy Story"**: Analyze and visualize user ratings specifically for the movie "Toy Story" to gauge its popularity and reception.
- **Top 25 Movies by Viewership Rating**: Identify and visualize the top 25 movies based on viewership ratings to understand the most popular movies among users.
- **Ratings for Movies Reviewed by a Specific User**: Find and visualize the ratings for all movies reviewed by a particular user with user ID = 2696.

### 3. Feature Engineering
- **Unique Genres**: Find all the unique genres present in the dataset.
- **One-Hot Encoding**: Create a separate column for each genre category with one-hot encoding (1 and 0) to indicate whether or not the movie belongs to that genre.
   
### 4. Determine Features Affecting Ratings
Utilize feature engineering results to determine the features that significantly affect the ratings of any particular movie.

## 5. Overview of the folder structure

```
├── Data
│   └── movies.dat
│   └── ratings.dat
│   └── users.dat
├── README.md
├── EDA.ipynb
```

