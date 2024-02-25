# Movies-Dataset-analysis-EDA-in-Python
## Introduction 
The Chief Financial Officer (CFO) of Amazing Movie Studio seeks to secure $100 Billion in funding from an investor to finance their upcoming movie project slated for release in 2025. To ensure optimal return on investment, the CFO aims to strategically allocate resources towards movie genres, production countries, and budget allocation that are most likely to yield substantial revenue.

In order to make informed decisions, the CFO plans to conduct a comprehensive data analysis of the studio's historical movie data. By leveraging insights from past performances, the CFO aims to identify lucrative opportunities and mitigate risks associated with the new project.

The analysis will focus on exploring correlations and trends within the dataset.

## Problem Statement
Is there a correlation between factors like budget and ratings? Do higher-budget productions tend to receive higher ratings?

How does budget allocation impact revenue generation?

How does Rate score allocation impact revenue generation?

What are the top 10 countries that generate the highest revenue?

Which language generates the highest revenue?

What genre is most popular among viewers?

## Data Dictionary
• names: The names of the movies (titles).

• date_x: The date associated with the movie (release date or another relevant date).

• rate_ score: The IMDb rating of the movie.The Metascore rating of the movie.

• genre: The genre(s) of the movie (e.g., Drama, Action, Comedy, etc.).

• overview: A brief overview or summary of the movie's plot.

• crew: Information about the movie's crew (directors, writers, producers, etc.).

• orig_title: The original title of the movie (if different from the title).

• status: The current status of the movie (e.g., released, in production, canceled).

• orig_lang: The original language of the movie.

• budget_x: The estimated budget of the movie.

• revenue: The revenue earned by the movie.

• country: The country where the movie was produced or originated from.

### Importing Libraries:
![](loading_libreries.png)
## Data Cleaning
### Missing Values Check 
![](Missing_values.png)

### Check Duplicates 
![](Duplicates.png)

### Split Genre Column 
![](Split_co.png)

### Drop Missing Values 
![](drop_Missing.png)

### Checking Null Values 
![](Null_demostration.png)

### Date Converting and Extracting 
![](Date.png)

## Exploratory Data Analysis
### Correlation Matrix Heatmap
![](Correlation_Matrix.png)
  ![](Corr_Vis.png)
### Is there a correlation between factors like budget and ratings? Do higher-budget productions tend to receive higher ratings?
![](Budeget_and_rating.png)
![](BudegtandRate_Visu.png)

1 indicates a perfect positive linear relationship

0 indicates no linear relationship

-1 indicates a perfect negative linear relationship

**Insight**: Since the correlation coefficient is negative and relatively close to 0, it suggests a weak negative correlation between the two factors being analyzed. Specifically, a correlation of approximately -0.21 implies that as one variable (in this case, budget) increases, the other variable (ratings) tends to decrease slightly, but the relationship is not very strong.

### How does budget allocation impact revenue generation?
![](Budegtand_revenue.png)
![](Budetandrevenu_Vis.png)

**Insight**: It seems that there is a correlation between budget spent and revenue generated.

### How does Rate score allocation impact revenue generation?
![](Ratingand_revenu.png)
![](RatingandRevenu_Vis.png)

**Insight**: We can`t seem to pinpoint if there is any correlation between revenue and rate_score from the scatter chart. We will have to use a barchart to measure if there is any relationship.

### Are there any notable trends in revenue generation over time?

![](Revenueovertime.png)
![](Rovertime_visual.png)

**Insight**: We can note that there has been an increase in movie/TV_Shows production over the years.

### What are the top 10 countries that generate the highest revenue?

![](topcountries.png)
![](topcounties_visual.png)

**Insight**: The country that generates the highest total revenue is Austrailia followed by United States.

### Which language generates the highest revenue?
![](Lanaguge.png)
![](Lanageug_visual.png)

**Insight**: English language seems to bring in the highest total revenue across all languages.

### What genre is most popular among viewers?
![](popular.png)
![](lanagu_visual.png)

**Insight**: Most rated by viewers is the Drama genre.

## Conclusions

When working with the data from Amazing Movie Studio, we've uncovered fascinating insights that shed light on the studio's past performance and offer guidance for future endeavors.

As we assesed the rate scores given by movie watchers, the analysis shows a positively skewed distribution. It's clear the studio's movies are hitting the right notes with the audience, making it a compelling destination for investment.

As regards to finance, revenue and budget has a positive correlation of 0.68 suggesting that when the studio pumps more money into its productions, the revenue tends to follow suit. It's a promising sign that investing in high-budget projects could yield substantial returns.

Despite revenue and budget having a positive relationship, ratings doesn`t seem to follow the same relationship, as the studio splurges more on a project, the ratings might take a slight dip. However, it's not a deal-breaker quality content still reigns supreme, and audiences are willing to overlook a few bumps in the budget road if the storytelling hits home.

Concerning the genres, Drama steals the spotlight, captivating audiences and dominating the scene for the past decade. But amidst the drama, documentaries seem to be taking a backseat viewership numbers suggest they're not getting the love they deserve.

## Recommendations

In our analysis of the past decade's data, we've distilled three essential strategies for maximizing Amazing Movie Studio's success:

Focus on Top Genres: Drama, Action, and Comedy consistently draw in audiences and drive revenue. Prioritizing productions in these genres will capitalize on existing audience preferences and ensure strong financial returns.

Leverage Top Production Locations: Australia, the US, and Korea have emerged as hotspots for successful productions. Investing in partnerships and projects in these countries can tap into established talent pools and production infrastructures, increasing the likelihood of box office success.

Target Top Languages: English, Japanese, and Korean have been the primary languages driving revenue growth. Tailoring productions to these languages will help the studio reach broader international audiences and maximize revenue potential.

Conclusively, investing in quality productions will lead to high returns.


