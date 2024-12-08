# Netflix Dataset - Exploratory Data Analysis (EDA)  

This project involves analyzing the Netflix dataset to uncover insights about the platform's content library, including movies and TV shows. The analysis focuses on trends, ratings, genres, and other attributes, using Python and various data visualization techniques.

## Table of Contents  
- [Dataset Overview](#dataset-overview)  
- [Project Objective](#project-objective)  
- [Steps Performed](#steps-performed)  
- [Technologies Used](#technologies-used)  
- [Visualizations](#visualizations)  
- [Insights](#insights)  

## Dataset Overview  
The dataset contains information about movies and TV shows available on Netflix, with the following columns:  
- **Show_Id**: Unique identifier for each content item.  
- **Category**: Indicates whether the content is a "Movie" or "TV Show."  
- **Title**: Name of the movie or TV show.  
- **Director**: Director of the content (if available).  
- **Cast**: List of actors starring in the content.  
- **Country**: Country of origin or production.  
- **Release_Date**: Date when the content was released.  
- **Rating**: Content rating (e.g., "PG," "R," "TV-MA").  
- **Duration**: Duration of the movie (in minutes) or number of seasons (for TV shows).  
- **Type**: Genre or category (e.g., "Drama," "Comedy").  
- **Description**: Brief summary of the content.  

## Project Objective  
To explore and analyze Netflix's dataset to identify patterns, trends, and relationships among various attributes, such as content type, ratings, and country of production.  

## Steps Performed  
1. **Data Loading**  
   - Importing the Netflix dataset into a pandas DataFrame.  

2. **Data Cleaning**  
   - Handling missing values in columns such as `Director` and `Cast`.  
   - Removing duplicate rows (if any).  

3. **Univariate Analysis**  
   - Examining individual attributes like `Category`, `Rating`, and `Type` using visualizations such as bar charts and histograms.  

4. **Bivariate Analysis**  
   - Investigating relationships between attributes, e.g., `Country` vs. `Category` or `Release_Date` vs. `Type`.  

5. **Visualization**  
   - Using seaborn and matplotlib to create informative charts and graphs for better understanding.  

## Technologies Used  
- Python  
- Pandas  
- Matplotlib  
- Seaborn  
- Jupyter Notebook  

## Visualizations  
Key visualizations include:  
- Distribution of content ratings.  
- Trends in content production over the years.  
- Analysis of popular genres by country.  

## Insights  
Some key findings from the analysis include:  
- The most common genres across movies and TV shows.  
- Trends in content release by year and country.  
- Distribution of ratings for movies and TV shows.  

## Contributing  
Contributions are welcome! Feel free to open a pull request or raise an issue to improve this project.  

## License  
This project is licensed under the MIT License.  
