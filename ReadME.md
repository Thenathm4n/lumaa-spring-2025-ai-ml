# Content-Based Recommendation System

## Overview
This project implements a simple content-based recommendation system that suggests movies based on a short text description provided by the user. It uses TF-IDF vectorization and cosine similarity to compare the input with movie descriptions.

## Dataset
- **Source:** The dataset is defined inline within the code for simplicity.
- **Content:** Each movie has a title and a description.
- **Customization:** You can replace the inline dataset with a CSV file containing movie data (e.g., 100-500 rows) by modifying the data loading section.

## Setup
- **Python Version:** Python 3.x
- **Virtual Environment:**
  ```bash
  python -m venv env
  source env/bin/activate  # On Windows: env\Scripts\activate
