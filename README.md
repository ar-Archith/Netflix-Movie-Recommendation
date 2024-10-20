# Netflix Movie Recommendation

## Project Description:

This repository implements a collaborative filtering approach to recommend movies based on user ratings. It utilizes the Apriori algorithm to discover frequent patterns of movie co-occurrences and suggests movies that similar users have enjoyed.

## Features:

- Implements the Apriori algorithm from the apyori library.
- Analyzes movie co-occurrences from user ratings.
- Generates personalized movie recommendations based on user preferences.
- Visualizes the top 20 most frequent movies and association rules.

## Requirements:

* Python 3.x
* Libraries: numpy, pandas, matplotlib, seaborn, apyori

## How to Use:

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/ar-archith/Netflix-Movie-Recommendation.git
2. **Install Libraries:**
   ```bash
   pip install numpy pandas matplotlib seaborn apyori
3. **Run the Notebook:**
   Open the `Netflix_Movie_Recommendation.ipynb` file in your preferred Jupyter Notebook environment and execute the code cells.

## Data:

The script assumes a CSV file named `Netflix_Movie_Recommendation.csv` exists in the same directory. This file should contain user-movie ratings in a format where each row represents a user's movie ratings (movie IDs or titles).

## Note:

This implementation provides a more advanced approach to movie recommendation by incorporating collaborative filtering. You can explore other recommendation algorithms and techniques to further enhance the system's performance.

Feel free to explore the code, modify it, and experiment with different functionalities!
