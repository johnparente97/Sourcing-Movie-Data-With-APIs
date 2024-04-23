# data-sourcing-challenge

This project aims to build a recommendation system to help users find movie reviews and related movies. The system uses data extracted from two different sources: The New York Times API and The Movie Database (TMDb). The text extracted from these APIs is used with natural language processing methods.

## Project Overview

1. **Data Extraction**: Data was extracted from The New York Times API and The Movie Database. The New York Times API was used to retrieve movie reviews, while The Movie Database was used to get related movie data.

2. **Data Cleaning**: The data from both sources was merged and cleaned for further processing.

3. **Recommendation System**: A recommendation system was built using the cleaned data. The system recommends movie reviews and related movies based on user preferences.

4. **Dependencies**: The project requires Python and the following libraries: pandas, numpy, requests, and dotenv. API keys for The New York Times and The Movie Database are also required.

## Instructions

The project is divided into three parts:

- **Part 1: Access the New York Times API**: This part involves setting up the API, defining the search parameters, and retrieving the data.

- **Part 2: Access The Movie Database API**: This part involves setting up the API and retrieving the data.

- **Part 3: Merge and Clean the Data for Export**: This part involves merging the data from both APIs, cleaning the data, and exporting it for further use.

Please refer to the `retrieve_movie_data.ipynb` notebook for detailed steps and code.

## Results

- **New York Times API**: The data extraction from the New York Times API was successful. We were able to retrieve movie reviews as expected.

- **The Movie Database API**: Unfortunately, the data extraction from The Movie Database API did not work as expected. We encountered issues while trying to access this API. Further investigation is needed to resolve these issues.
