![IMDB_movie](https://lh3.googleusercontent.com/R5x56X7xOHZenDcDjP9q9qwWGg3iB7KKEz1KUMHbEurjDRXY4VLb3LBjOZ4u1_XiXzC-)

# Opportunities for Microsoft in the Movie Production Industry 

## Business problem:

Microsoft sees all the big companies creating original video content, and they want to get in on the fun. They have decided to create a new movie studio, but the problem is they don’t know anything about creating movies. They have hired you to help them better understand the movie industry.

We approach this problem by doing data analysis that explores the film production industry landscape on the high level, then deep dives to see what type of films have been doing well at the box office and which directors Microsoft should approach to produce similar types of movies. 

#### Questions of interest:

1. Movie industry landscape
   - Which are some of the major studios ? Gross bookings per each player ?
   - How concentrated is the industry ? 
   
2. What kinds of movies Microsoft should produce ?
   - What genres have been doing well in terms of popularity over the last 5 years?
   - What genres have been doing well in terms of ratings over the last 5 years?  
   - Any correlation between runtime and ratings of movies ? 


## Data

The analysis is based on database from IMDB  


## Findings & Recommendations

Please refer to the [narrative Jupyter Notebook](./Mark_Movie_Analysis.ipynb) in this repository for a walkthrough and more explanation of these findings.

- Largest players since 2013 are Buena Vista , Universal, and Warner Bros with annual gross bookings of around 5-6 billion USD. 
- The industry is concentrated among top 10 players. Top 10 players generates nearly 90% of total gross bookings annually. 
- MSFT needs to achieve around 300M annually minimum in gross bookings to become top 10 players (based on 2017 data).
- Top 5 popular genres are Drama, Comedy, Action, Thriller, and Crime (based on top 10% of movies ranked by number of votes on IMDB)
- Drama, Comedy, and Documentary genres generate highest ratings among top 10% popular movies ranked by number of votes on IMDB
- There is a positive correlation between runtime and ratings of movies among the top 10% of most popular movies.


## Limitations & Next Steps

- Not include data from other database such as Rotton Tomatoes and The Movie Database (TMDb)

### Contact

For any additional questions, please reach out to the [Flatiron School's Data Science Program](https://flatironschool.com/career-courses/data-science-bootcamp): [LinkedIn](https://www.linkedin.com/school/the-flatiron-school/)

