# Recommendation Engines

This project implements an article recommendation system using collaborative filtering techniques and Singular Value Decomposition (SVD). The goal of the system is to provide personalized article recommendations to users based on their interactions and similarities with other users.

## Installation

To run this project locally, please follow these steps:

(1) Clone the repository

(2) Install the required dependencies: 

#### Dependencies
- Python 3.5+
- Pandas
- Numpy
- Matplotlib

## Files

Jupyter Notebook:
- Recommendations_with_IBM.ipynb

Data includes 2 csv files:
- `data/articles_community.csv`: Articles information.
- `data/user-item-interactions.csv`: User interactions.

## Notebook Contents

(1) Exploratory Data Analysis

During the exploratory data analysis phase, the project involved investigating and understanding the structure and content of the dataset. This included tasks such as cleaning the data, handling missing values, and exploring the distribution of variables. Visualizations were created to uncover patterns, trends, or insights within the data.


(2) Rank-Based Recommendations

The project implemented a rank-based recommendation system, where items were recommended based on their popularity. The system suggested the top-rated or most frequently interacted articles based on similar users.

(3) User-User Based Collaborative Filtering

The project utilized a user-user collaborative filtering approach to make recommendations. This method involved identifying similar users based on their interactions with articles. Recommendations were made by suggesting items that similar users had liked or interacted with, leveraging the idea that users with similar preferences tend to have similar tastes in items.

(4) Content Based Recommendations (Not Completed)

Empty.

(5) Matrix Factorization

Matrix factorization, a dimensionality reduction technique, was employed in the project. It involved decomposing the user-item interaction matrix into lower-dimensional matrices, capturing latent features or preferences of users and items. This approach aimed to generate personalized recommendations by identifying hidden patterns and similarities in the data, providing more accurate and tailored suggestions to users.

## Results:
Open notebook to view results.

## License:
This project is licensed under the MIT License - see the LICENSE file for details.



