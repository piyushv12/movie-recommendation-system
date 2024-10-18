# Movie Recommendation System

This project is a **Movie Recommendation System** that uses collaborative filtering and content-based filtering algorithms to suggest personalized movie recommendations for users.The recommendation system is powered by data from the provided datasets (movies.csv and credits.csv), which include information about movies such as genres, cast, and crew. Users can search for movies and get personalized recommendations based on genres or cast similarities.

## Table of Contents
- [Project Overview](#project-overview)
- [Datasets](#datasets)
- [Algorithms](#algorithms)
- [Installation](#installation)
- [Usage](#usage)
- [Technologies](#technologies)
- [Contributing](#contributing)
- [License](#license)

## Project Overview
The Movie Recommendation System suggests movies based on user preferences and similarities. It uses:
- **Collaborative Filtering**: Recommends movies based on what similar users have liked.
- **Content-Based Filtering**: Recommends movies based on attributes like genre, cast, etc.

## Datasets
The project uses two main datasets:
- `movies.csv`: Contains movie details like title, genre, etc.
- `credits.csv`: Contains information about the cast and crew of each movie.

## Algorithms
- **Collaborative Filtering**: Analyzes the relationships between users and items (movies) to recommend movies to users who have not interacted with them.
- **Content-Based Filtering**: Recommends movies similar to those the user has interacted with, based on metadata.

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/piyushv12/movie-recommendation-system.git
2. Install the necessary dependencies:
   pip install -r requirements.txt
## Usage

Open the project.ipynb notebook in Jupyter or any compatible environment.
Run the cells to load the data and generate movie recommendations based on user inputs.

## Technologies

1. Python: Programming language used for data processing and model building.<br>
2. Jupyter Notebook: Development environment.<br>
3. Pandas: Data manipulation.<br>
4. scikit-learn: Machine learning algorithms.<br>

## Contributing

Contributions are welcome! Please fork this repository and submit a pull request for review.

## License

This project is licensed under the MIT License.
