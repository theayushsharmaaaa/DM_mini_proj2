# Data Analysis on Movies Dataset (CMU Movie Summary Corpus)

# Abstract:

The movie business, an extensive multi-billion-dollar international industry, has won hearts across the globe thanks to its diversity in language, genre, and local peculiarities. This project delves through the complex ornament of the cinematic landscape, revealing that English language films have been grabbing huge box office revenue, at the same time, concerns are drawn to non-English movies that have highly surpassed language barriers. 
 
In addition, that analysis helps us to understand the revenue specifics and the genre preferences of the top 20 actors-industry which are indicators of their acting level, and also a contributor to their success. Particularly, the project unravels the history of movie production development, box office success, and the dominance of films of selected genres with regard to specific countries and regions over time, shedding more light on the cultural and socioeconomic factors that fueled a particular market. 
 
This project, which does data-driven analysis and visualizations, is the one that provides invaluable insights to movie studios, filmmakers, as well as audiences helping them better understand a complex and intricate tapestry that is global cinema. 

Dataset used: https://www.cs.cmu.edu/~ark/personas/


# Data Analysis Questions I have answered:

## Question 1: 

#### Analyzing language diversity and revenue trends in the top movies: How does the dominance of English-language films compare to non-English counterparts, and what are the top-grossing movies for each language over time? 

## Question 2: 

#### What are the revenue patterns and genre preferences among the top 20 actors in the movie industry, and how do these factors influence their performance and success?

## Question 3: 

#### How have movie production, box office performance, and genre preferences varied across different countries and regions overtime, and what factors contribute to their success in specific markets? Also, analyzing which character name appeared to be the most in all the movies.


# Methods and Results

## Question 1: Analyzing language diversity and revenue trends in the top movies

### Methods:
1. **Data Preparation:**
   - Loaded movie metadata containing information such as movie name, release date, box office revenue, languages, etc.
   - Processed the data to handle missing values and extract relevant information.

2. **Language Analysis:**
   - Analyzed language diversity in movies by counting occurrences of each language.
   - Plotted the top 20 languages in the dataset to visualize language distribution.

3. **Revenue Trends:**
   - Filtered the dataset for movies released between 1962 and 2012.
   - Grouped movies by year and identified the top-grossing movie for each year.
   - Plotted the top movie each year to visualize revenue trends over time.
   - Analyzed the dominance of English-language movies and their revenue compared to non-English counterparts.

4. **Top Movies by Language:**
   - Identified the top movies for each language based on box office revenue.
   - Plotted the top movies for each language over time.

### Results:
- English-language films dominate the dataset, comprising 68.6% of total movies.
- English-language movies consistently outperform non-English counterparts in revenue.
- Top movies for each language generally include high-grossing English-language films, but non-English movies also feature prominently.
- Over time, the dominance of English-language movies has remained stable, with no significant fluctuations.
- There's a noticeable increase in the representation of non-English movies in recent years, indicating a rise in global cinema diversity.

## Question 2: Revenue patterns and genre preferences among the top 20 actors

### Methods:
1. **Data Preparation:**
   - Loaded character metadata containing actor information.
   - Merged character metadata with movie metadata to analyze revenue and genre preferences.

2. **Top Actors Analysis:**
   - Identified the top 20 actors by total revenue generated from movies.
   - Visualized the top actors and their total revenue.

3. **Genre Preferences:**
   - Determined the most profitable genre for each actor among their top-grossing movies.
   - Visualized genre preferences and revenue patterns for each actor.

### Results:
- Warwick Davis emerges as the actor with the highest total revenue.
- Fantasy is the most profitable genre for the majority of top actors.
- Visualizations provide insights into genre preferences and revenue patterns for each actor.

## Question 3: Movie production, box office performance, and genre preferences across different countries and regions

### Methods:
1. **Data Preparation:**
   - Loaded movie metadata containing information about countries, release dates, revenue, etc.
   - Analyzed movie production, box office performance, and genre preferences across different countries and regions.

2. **Country and Region Analysis:**
   - Identified top movie-producing countries and regions.
   - Analyzed box office revenue by country and region.
   - Examined genre revenue trends over time.

### Results:
- USA leads in movie production and box office revenue, followed by other major contributors like France and Japan.
- Genre revenue trends over time highlight audience preferences and market dynamics.
- Regional variations in genre preferences offer insights for filmmakers and studios to tailor content for specific markets.
