# ToDo
### Research
- NASA (Mai) https://data.nasa.gov/
- Business (Lev) https://???.com/
- Alejandro, por confirmar (Salud/Mixed dataset)

## Scope
    - Extraction (SQL, NoSQL) - (SQLite, PostgreSQL or Apache Cassandra)
    - Load (Memory/File -> DB (cloud?))
    - Transform (EDA, Clean)
    - Visualization (PowerBI, Tableau, Frontend)
    - Task automation (Airflow, ???)
    - Cloud (ELT integration, Visualization, Automation)

## Public Datasets
    - Movies (imDB)
    - NASA

SQL
    - Migration
SQL/Pandas for data manipulation

### Visualization
    -PowerBI (PQuery/DAX)
    -Frontend (flask)?

### Cloud
-dbt (cloud)? (free version)
-Databricks ?

### Example of mixed sql/nosql
Movies (NoSQL)
    - Director
    - Genre
    - Assistant Director
    - Cast
        - Character: Actor/Actress
        -
Box office (SQL)
    - MovieID: $$$
    - MovieID, Country, $$$, Genre

https://datasetsearch.research.google.com/

https://www.wqu.edu/ai-lab-computer-vision-apply
https://www.wqu.edu/adsl-apply

https://www.linkedin.com/posts/anyone-ai_final-projects-activity-7274770359952822272-rBSw

https://www.reddit.com/r/dataengineering/comments/133qlow/datasets_for_data_engineering_projects/

https://www.projectpro.io/article/real-world-data-engineering-projects-/472

https://github.com/alejandromz2/LLM_para_gesti-n_documentaria_

# Post Meeting Notes
(Lev)
Found information about weather and movie datasets and api's

### Reverse ETL :O
https://hightouch.com/pricing - Plans for teams looking to quickly get data to their tools with the Reverse ETL Platform.

https://www.kaggle.com/datasets/harshitshankhdhar/imdb-dataset-of-top-1000-movies-and-tv-shows
https://www.kaggle.com/datasets/lakshmi25npathi/imdb-dataset-of-50k-movie-reviews

### Possible datasets
#### SQL
1. Movie Ratings Analysis
	* Use a dataset like IMDB's or MovieLens (available on Kaggle)
	* Create tables for movies, ratings, users
	* Write queries to find interesting patterns like highest-rated genres by decade, most prolific directors, etc.
	* Scope: 3-4 tables, 8-10 meaningful queries
2. E-commerce Data Analysis
	* Use sample order/customer data
	* Practice joins, aggregations, and window functions
	* Find insights like customer purchasing patterns, popular product combinations
	* Scope: 4-5 tables, 8-10 analytical queries

####  For Pandas (as a separate project):
1. COVID Data Analysis
	* Use public COVID datasets from Kaggle
	* Focus on time series analysis
	* Create visualizations of trends
	* Scope: Data cleaning, 5-6 specific analyses
2. Stock Market Analysis
	* Use Yahoo Finance data for a few selected companies
	* Calculate moving averages, daily returns
	* Basic technical indicators
	* Scope: Data manipulation, basic financial calculations

### Should You Use Databricks?
    • If your dataset is small (fits in memory): Stick with SQLite and Pandas.
    • If your team wants an interactive environment for SQL and Pandas: Databricks is a good choice.
    • If you plan to work with large datasets later, Databricks makes scaling easy.

### API's
* #### NASA
    https://api.nasa.gov/
* #### Weather
    https://openweathermap.org/api
    https://openweathermap.org/api/one-call-3
        * Current weather and forecasts: minute forecast for 1 hour, hourly forecast for 48 hours, daily forecast for 8 days, long-term forecast for 1,5 years
        * Government weather alerts
        * Historical data for 46+ years back
        * All weather parameters plus UV index, Dew point, etc.
        Get essential weather data, short-term and long-term forecasts and aggregated weather data
            minute forecast for 1 hour
            hourly forecast for 48 hours
            daily forecast for 8 days
            Daily aggregation of weather data for 46+ years archive and 1.5 years ahead forecast
* #### Movies
    * https://www.the-numbers.com/data-services
	* https://www.opusdata.com/ (Lev sent form for free account)
	* https://www.the-numbers.com/movies/report-builder
	* The Numbers Bankability Index
	* https://developer.imdb.com/
	* https://developer.imdb.com/documentation/api-documentation/getting-access/
	* https://aws.amazon.com/marketplace/pp/prodview-3n67c76ppu2yy
	* https://www.statista.com/outlook/amo/media/cinema/box-office/worldwide (nice visualizations)

* #### Daily Box Office
	* ##### Scraping
	    * https://www.boxofficemojo.com/date/2025-01-31/ (latest are estimated)
	    * https://www.the-numbers.com/daily-box-office-chart
	    * https://www.the-numbers.com/box-office-chart/daily/2025/01/31
	* Package
    	* https://pypi.org/project/boxoffice-api/
	    * https://github.com/Stink-Po/boxoffice_api (https://medium.com/@fresh.pourya/unofficial-python-api-for-box-office-mojo-access-box-office-data-with-ease-3bf1dd7fd5d9)


* #### Movie API
    * https://www.omdbapi.com/ (Free API key creation)
