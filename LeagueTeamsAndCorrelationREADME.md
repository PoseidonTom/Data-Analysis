# Correlation between League Teams and the cities
The following project finds the correlation of the win/loss ration of various League Teams (NFL, MLB, NBA, MLB) with the population of the respective host cities. <br><br>
[**Pearson Correlation**](https://docs.scipy.org/doc/scipy/reference/generated/scipy.stats.pearsonr.html) is used to calculate the correlation. Manual cleansing of data was done to ensure uniformity. Splitting up text was done to find the respecting cities of the teams while [**merging**](https://pandas.pydata.org/docs/reference/api/pandas.merge.html) the datasets.
