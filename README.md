# Movie Gross Revenue Correlation - Python
In this project, I extracted [Movie Industry](https://www.kaggle.com/danielgrijalvas/movies "Kaggle") data and used Python to find correlations between variables.
## Content:
There are 6820 movies in the dataset (220 movies per year, 1986-2016). Each movie has the following attributes:

* budget: the budget of a movie. Some movies don't have this, so it appears as 0
* company: the production company
* country: country of origin
* director: the director
* genre: main genre of the movie.
* gross: revenue of the movie
* name: name of the movie
* rating: rating of the movie (R, PG, etc.)
* released: release date (YYYY-MM-DD)
* runtime: duration of the movie
* score: IMDb user rating
* votes: number of user votes
* star: main actor/actress
* writer: writer of the movie
* year: year of release

First, I assumed that the Budget of a film would be highly correlated to its Gross Revenue. The greater the budget, the more resources a company has access to for making a quality film that will likely generate a vast amount of gross revenue.  

Although these two variables shared the highest correlation compared to other pairs of variables, Votes and Gross were also highly correlated with one another. Since votes in the data relate to how consumers rate the film, I can see this being either benefical or detriamntal to the popularity and gross revenue earned. 
## Objective:
* Extract, Clean, and Sort Data 
* Visualize and Analyze Correlations in the Dataframe
### [View my project](https://github.com/Apappas97/Correlation-in-Python---Movie-Dataset/blob/main/Movie%20Correlation%20Project.ipynb) in python to see a step-by-step process for how I completed these objectives 
## Skills Demonstrated: 
* Import Packages Used for Data Manipulation, Analysis, and Visualizations 
* Find and Remove NULL Values 
* Convert Datatypes 
* Split Strings
* Scatter and Regression Plots 
* Correlation Matrices
