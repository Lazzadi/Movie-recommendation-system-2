# Movie Recommendation System

This project implements a movie recommendation system using collaborative filtering techniques. It analyzes user ratings and movie features to suggest similar movies to users as well as make recommendations based on user activity.

## Table of Contents

- [Introduction](#introduction)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Introduction

The Movie Recommendation System is built using Python and relies on the pandas, numpy, and scikit-learn libraries for data manipulation and analysis.

The system works by first analyzing user ratings and movie features. It then identifies similar users based on their preferences and suggests movies that they have enjoyed but the target user has not yet watched. Additionally, it considers genre preferences of the target user to provide more personalized recommendations.

## Installation

To use the Movie Recommendation System, follow these steps:

1. Clone the repository to your local machine.
2. Ensure you have Python installed.
3. Install the required dependencies using pip:
   
   ```bash
   pip install pandas numpy scikit-learn matplotlib
   pip install jupyter

4. Download the full movie dataset https://files.grouplens.org/datasets/movielens/ml-latest.zip
5. Unzip the dataset to the bin folder
6. Open Jupyter Lab
   ```bash
   jupyter lab

Use case 1:
Run the jupyter notebook and write the movie title for which you want recommendations. The system will recommend similar movies by analyzing the movie preferences of users who also liked the target movie.

Use case 2:
Change the variable target_user_id to select the user for which you want to generate recommendations, then run the jupyter notebook. The system will generate recommendations based on simillar users preferences and the target user's favourite genres.

   
