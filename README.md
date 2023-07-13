# Python-B-Project
Your GitHub username:
laylaelna

# Name of the partner and their GitHub username:
Vir Kapoor/VirKap

# Research Question:
Is there a correlation between the walkability of a city and the happiness of its residents?

# Expected coding work to be done:
In order to compare the walkability of cities to the happiness of their residents, first we must import files from large data sets indicating walkability and emotional happiness for approximately 100 heavily populated cities around the United States. We will use the emotional happiness metric instead of the overall metric because it does not factor walkability into its calculation. We will also utilize the income metric to see how it correlates with emotional happiness as well as walkability access. Then, we will design a for loop appending the values from both data files to a dictionary. We will use an if statement within the loop that appends the walkability of a city to the dictionary, if that city is found in one of the 100 cities in the emotional happiness data set. Then, we will use matplotlib and PyPlot in order to plot the emotional happiness of a city (y-axis) against it’s walkability (x-axis), as well as income (x-axis) against walkability (y-axis). We could see if there is a correlation by calculating a linear regression and analyzing the r^2 value to see how closely linked walkability and emotional happiness are. Our hypothesis is that more walkable cities will have higher happiness. However, for cities where this does not apply, we can have a for loop that searches for outliers in the data, and prints those cities. 

# Possible Packages to be used:
PyPlot, numpy, pandas, matplotlib

# Possible Datasets to be used (at least 2):
https://www.walkscore.com/cities-and-neighborhoods/

https://wallethub.com/edu/happiest-places-to-live/32619

# Any considerations that need to be taken into account:
The happiness index is calculated based on the mean of 3 happiness parameters (community, income, emotional factors). It is important to analyze these metrics individually to get more specific results. Any cities that will be analyzed must be within both data sets.

# Expected results (Consult instructor if you don’t have an idea):
We expect for the correlation between walkability and happiness to be positive. We also expect that locations with higher incomes will have more walkability as a result of better resources. However, a strong correlation is not necessarily likely as there are bound to be outliers.

# GitHub repository link
https://github.com/VirKap/Python-B-Project
