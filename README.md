# Metis Module 3: Linear Regression and Web Scraping

The goal of this project was to investigate the features that contribute to higher revenues for science fiction films. I scraped data from various websites, ending up with information about the revenues, actors, directors, runtime, MPAA ratings, release dates, and plot keywords for 1700 films. I originally wanted to see if there was a relationship between the number of ‘tropes’ (which I extracted from plot keywords in IMDb) in the film and revenue. I was hoping to see more defined linear relationships between the features and the target (revenue), but I was still able to identify some of the important features using random forest regression. I started with pretty low R squared scores, and after some engineering, cleaning, and scaling, ended up with a score up to 0.76. Overall, my data indicated that the actors and directors are the most important features when considering higher revenues for sci-fi films. 

