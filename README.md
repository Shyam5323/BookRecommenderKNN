# Book Recommendation System

This project is a book recommendation system built using Python. It utilizes a collaborative filtering approach with k-Nearest Neighbors (k-NN) to recommend books based on user ratings.

## Overview

The Book Recommendation System uses data from the [Book-Crossing Dataset](https://cdn.freecodecamp.org/project-data/books/book-crossings.zip) to recommend books to users. The system leverages the k-NN algorithm to find similar books based on user preferences.

## Features

- **Book Recommendations**: Given a book title, the system provides a list of similar books based on cosine similarity.
- **Data Processing**: Clean and preprocess book ratings and book details data.
- **k-NN Model**: Uses k-Nearest Neighbors with cosine distance to find similar books.

## Getting Started

### Prerequisites

Ensure you have the following Python packages installed:

- `numpy`
- `pandas`
- `scipy`
- `scikit-learn`
- `matplotlib`

You can install these packages using pip:

```bash
pip install numpy pandas scipy scikit-learn matplotlib
```
### Data
Books Data: Contains information about books, including ISBN, title, and author.
Ratings Data: Contains user ratings for books.
### Testing
The test_book_recommendation function validates the recommendation system by comparing the output to expected results. Run this function to verify that the system works as expected.
