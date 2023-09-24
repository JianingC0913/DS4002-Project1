# DS4002-Project1
## SRC section
### Installing/building:
· **(year)_topic_modeling.ipynb**: All ipynb files are wrote in Python and can run in vscode or jupyter notebook with anacoda environment. You need to run each cell in order to make sure packages and variables are existed in your local environment before they are used.  
· **4002_data_explore.rmd**: This Rmd file are wrote in R and can run in Rstudio. ou need to run each cell in order to make sure packages and variables are existed in your local environment before they are used.  
· **web-scraping.ipynb**: This ipynb file is wrote in Python and can run in vscode or jupyter notebook with anacoda environment. You need to run each cell in order to make sure packages and variables are existed in your local environment before they are used.  
· **genre_spread_viz.twb**: This file is created in Tableau and must run in Tableau. Once open the file, you should be able to see all the plot that already created.

### Usage
· **(year)_topic_modeling.ipynb**: These files of code are used to conduct topic modeling on the top 10 movie scripts from the corresponding year.  
· **4002_data_explore.rmd**: This file is used to draw all the figures in the FIGURES folder. We used in in our EDA procedure and created exploratory plots.  
· **web-scraping.ipynb**: This file is used to web scrap annual top 10 movies from 2000 to 2023 on the Box Office Mojo website. The result is saved as annually_top_10.csv in the DATA folder.  
· **genre_spread_viz.twb**: This file is used to visualize the trend of both economy recession indicator and each movie genre throughout the year.

## DATA section
· **(year).txt**: These text file do not have any variables or columns, they only contain the top 10 movie script in plain text format for the corresponding year.  
· **annually_top_10.csv**:  
| Column Number | Description |
|---------------|-------------|
|  0  |  Specific year  |
|  1-10  |  Movie name, and the column number represents its ranking in the corresponding year |  

· **combined_data.csv**:  
| Variable Name | Description |
|---------------|-------------|
| Year | Specific year |
| Spread | The economy recession indicator of a specific year |
| Rank | How the moive ranked in a specific year |
| Name | The movie name |
| Genre | A list of genre that associate with the movie |
| Genre1 - Genre8 | Split out the genres from Genre column |
| *Rest of the Columns* | The number of the corresponding genre that existed in the top 10 movie corresponding year |  

· **Data Compilation-all years.csv**:  
| Variable Name | Description |
|---------------|-------------|
| Year | Specific year |
| Spread | The economy recession indicator of a specific year |
| Rank | How the moive ranked in a specific year |
| Name | The movie name |
| Genre | A list of genre that associate with the movie |
| Genre1 - Genre8 | Split out the genres from Genre column |  

· **total gross by genre by years.xlsx**:  
  | Variable Name | Description | 
  |---------------|-------------| 
  | Year | Specific year | 
  | Spread | The economy recession indicator of a specific year | 
  | Action | Box office revenue in dollars adjusted by inflation | 
  | Thriller | Box office revenue in dollars adjusted by inflation | 
  | Comedy | Box office revenue in dollars adjusted by inflation | 
  | A | Box office revenue in 10^9 dollars adjusted by inflation |  
  | T | Box office revenue in 10^9 dollars adjusted by inflation |  
  | C | Box office revenue in 10^9 dollars adjusted by inflation |  



## FIGURES section
| Figure Name | Description | Takeaways |
|---------------|-------------|--------|
|genre_occurrence_plots.pdf| This file contains plots of how many time a certain genre appeared throughout the years. Each plot represent one unique genre.| Adventure and Action, and Sci-fi (after 2013) seem to be the highest-grossing movie genres throughout 2000-2023.|
|genre_plots_grid.pdf|This file contains plots of the distribution of genres within a certain year. Each plot represent one unique year.| After 2007, movies within the genre of Family appeared to rise. Genres related to Mystery, Musical, and Romance are stagnantly low.|
|genre_occurrence_by_year.png<br>genre_occurrence_by_year2.jpg| These two graphs are stacked bar graph that represent the distribution of genre within each year. Each bar is a unique year, and each color is a unique genre. These two plots are essentially the same, the only difference is the color palette that is being used.|According to the graph above, the majority of the movies released from 2000 to 2023 fell into the category of Action and Adventure.|  


## REFERENCES section
[1]“Domestic Box Office For 2006,” Box Office Mojo. https://www.boxofficemojo.com/year/2006/?grossesOption=calendarGrosses (accessed Sep. 17, 2023).  
[2]“Movies: List of All American Movies (2008-2021),” www.kaggle.com. https://www.kaggle.com/datasets/paritosh712/movies-list-of-all-american-movies-20082021  
[3]“What Is the Probability of a Recession? The Message from Yield Spreads,” www.stlouisfed.org. https://www.stlouisfed.org/on-the-economy/2023/sep/what-probability-recession-message-yield-spreads#:~:text=10%2DYear%2DThree%2DMonth%20Yield%20Spread (accessed Sep. 17, 2023).  
[4]Board of Governors of the Federal Reserve System (US), “10-Year Treasury Constant Maturity Rate,” FRED, Federal Reserve Bank of St. Louis, Jan. 02, 1962. https://fred.stlouisfed.org/series/DGS10#0  

Milestone 1: https://docs.google.com/document/d/1bD_SmjDqFXryMQaFdDJc0TetDrjuSKgjMCCFr_pSokI/edit?usp=drive_link  
Milestone 2: https://docs.google.com/document/d/1y1DW8-972_-OMUzzbV57p-HqqTyybpA8hSUemH7mwLo/edit?usp=drive_link  

