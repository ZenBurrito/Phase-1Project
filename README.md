# Film Industry EDA

**Authors**: Colin Pelzer, Emiko Naomasa, Daniel Burdeno, Piotr Czolpik

## Overview

  Using Python libraries such as; pandas, matplotlib, NumPy, and seaborn we conducted an EDA on the film industry.
We used our findings to create recommendations for the Microsoft Studio team, including the relationship of genre
and return on investment (ROI), how the season changing affects consumer habits, and which directors have had the
most overall success in the market.

## Business Problem

  Microsoft has expressed interest in going into the original video creation by creating a new movie studio. 
The Microsoft Studio team has tasked us to explore which types of films are dominating the market, 
and translate them into actionable intel that can help the head of Microsofts new studio make
an informed decision on which films they would like to start to produce.

## Data

  The data for this project has been scraped from IMDb.com and The-Numbers.com, both of which contain
raw data that pertains to the film industry as a whole. They include data points such as; worldwide gross,
director name, genres, runtimes, etc. The main variable we want to compare the datapoints to is
ROI, we want to know how efficient each data point is for a new original content creation studio.

## Methods

  The main library used for cleaning and organizing the data was pandas. We created several data frames
from the datasets provided and did basic cleaning operations. We dropped null values because we deemed that
not only was the data only a fraction, but the rest of the data in the columns were irrelevant. We then made
sure there were no obscene outliers or duplicate data. After we had cleaned and prepared data frames we used
the matplotlib and seaborn libraries to visualize the data. After a few graphs we prepared three seperate
recommendations. We found this approach appropriate since the overall business question was how to carve out
a place in the film market, so finding the types of films, who should be in charge of them, and when to release
the films was all relevant.

## Recommendation 1

  The first recommendation that we made to Microsoft is to pay close attention to the relationship between
genre and ROI. There is a clear correlation between a few genres and a very positive ROI, the biggest suprise
was finding out how profitable horror movies are. The average budget on a horror film is considerably lower than
a cgi filled action movie like The Avengers. Despite the low budget horror films still succeed in the market over
the past ten years. Even if more movie titles were added and we had more data to parse through, the statement of
"horror films cost less to make, and return a very positive ROI" would still be true, making our data not only relevant
to just our datasets, but the overall market as well.

How do you interpret the results?
How confident are you that your results would generalize beyond the data you have?
Present your key results. For Phase 1, this will be findings from your descriptive analysis.

## Visual 1
![graph1](./Images/boxplot_roi_genre.png)

## Recommendation 2
  The second recommendation that we gave was how the seasons affect consumer habits when it comes to viewership.
We took the release month of movies and compared them to the average ROI of movies released in those months. 
took actual month name, sorted by order or months, plotted month name vs ROI, July, Jan highest roi,
## Visual 2
![graph1](./images/viz1.png)

## Recommendation 3
recommendation

## Visual 3
![graph1](./images/viz1.png)


## Conclusions

Provide your conclusions about the work you've done, including any limitations or next steps.

***
Questions to consider:
* What would you recommend the business do as a result of this work?
* What are some reasons why your analysis might not fully solve the business problem?
* What else could you do in the future to improve this project?
***

## For More Information

Please review our full analysis in [our Jupyter Notebook](./dsc-phase1-project-template.ipynb) or our [presentation](./DS_Project_Presentation.pdf).

For any additional questions, please contact **Colin Pelzer - pelzercolin@gmail.com, Daniel Burdeno -email, Emiko Naomasa -email, Piotr Czolpik -email**

## Repository Structure

Describe the structure of your repository and its contents, for example:

```
├── README.md                           <- The top-level README for reviewers of this project
├── dsc-phase1-project-template.ipynb   <- Narrative documentation of analysis in Jupyter notebook
├── Film_Industry_EDA_Presentation.pdf  <- PDF version of project presentation
├── data                                <- Both sourced externally and generated from code
└── images                              <- Both sourced externally and generated from code
```
