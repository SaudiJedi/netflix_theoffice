# Investigating Netflix Movies and Guest Stars in The Office
This is a project that has been done on DataCamp to showcase and demonstrate the tools used for loading and cleaning data with python.
This project is a data analysis of the popular TV show The Office, which aired on Netflix from 2005 to 2013. The project aims to explore the ratings, viewership, and sentiments of the episodes and characters of the show.

## Data Sources
The data for this project comes from the following sources:
- The Office IMDb Ratings: This is a web page that contains the ratings and votes for each episode of The Office on IMDb.
- The Office Scripts: This is a GitHub repository that contains the scripts for each episode of The Office in text format.
- The Office Quotes: This is a website that contains the quotes for each episode of The Office, along with the characters who said them and the timestamps.

## Usage
Start by cloning the repo and installing the necessary dependencies required to run the notebook.
```
git clone https://github.com/SaudiJedi/netflix_theoffice.git
```

## Analysis Steps
The project consists of the following steps:
- **Data Collection**: The data from the sources mentioned above are scraped and downloaded using Python requests and BeautifulSoup libraries.
- **Data Cleaning**: The data are cleaned and formatted using pandas and numpy libraries. The data are also merged into a single dataframe for further analysis.
- **Data Visualization**: The data are visualized using matplotlib and seaborn libraries. The visualizations include bar charts, line charts, pie charts, and heatmaps to show the trends and patterns of the ratings, viewership, and sentiments of the episodes and characters.
- **Data Analysis**: The data are analyzed using nltk and textblob libraries. The analysis includes sentiment analysis, word frequency analysis, and word cloud generation to show the emotions, keywords, and topics of the episodes and characters.

## Results
The results of the data analysis are as follows:
- The ratings and viewership of The Office show a general decline over the seasons, with some peaks and dips in between. The highest-rated and most-watched season is season 4, while the lowest-rated and least-watched season is season 9.
- The most popular episodes of The Office are “Stress Relief”, “Goodbye, Michael”, and “Dinner Party”, while the least popular episodes are “Get the Girl”, “The Banker”, and “The Farm”.
- The most liked characters of The Office are Jim, Dwight, and Michael, while the least liked characters are Toby, Nellie, and Robert.
- The episodes and characters of The Office have a mix of positive and negative sentiments, with some variations across the seasons. The most positive season is season 7, while the most negative season is season 8.
- The most frequent words in the scripts and quotes of The Office are “Michael”, “Jim”, “Dwight”, “Pam”, and “office”, while the most unique words are “Dunder”, “Mifflin”, “Schrute”, “Beesly”, and “Halpert”.
- The word clouds of the episodes and characters of The Office show the main themes and topics of the show, such as office life, romance, comedy, and drama.

## Acknowledgments
This project is inspired by the following sources:
- The Office Data Analysis: This is a similar project that analyzes the ratings and viewership of The Office using R.
- The Office Analysis: This is a collection of data analysis projects on The Office using the TidyTuesday dataset and R.
- The Office: A Comprehensive Survival Analysis: This is a blog post that applies survival analysis to the characters of The Office using Python.
