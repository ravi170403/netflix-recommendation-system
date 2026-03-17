#  Netflix Recommendation System


##  Example Output

Toy Story (1995) → Recommended Movies:
- Craft, The (1996)
- Beauty and the Beast (1991)
- G.I. Jane (1997)

##  Overview

This project builds a movie recommendation system using collaborative filtering on the MovieLens dataset.

##  Features

* Item-based collaborative filtering
* Movie similarity using Pearson correlation
* Filters recommendations based on popularity
* Generates top-N movie recommendations

##  How It Works

* Created a user-movie rating matrix
* Computed similarity between movies using correlation
* Removed low-rated movies for better accuracy
* Recommended movies similar to input movie

##  Dataset

* MovieLens 100K dataset
* 100,000 ratings from 1000 users on 1700 movies

## Tech Stack

* Python
* Pandas
* NumPy
* Matplotlib

##  Example

Input:
Toy Story (1995)

Output:
List of similar recommended movies

##  Future Improvements

* Add user-based filtering
* Build web app using Streamlit
* Deploy on AWS

##  Author

Ravi Teja Kasa
