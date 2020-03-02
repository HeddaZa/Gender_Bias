We study here gender biases in the IMDB. We start from the list of titles provided by the IMDB (https://www.imdb.com/interfaces/) and use the gender-guesser (https://pypi.org/project/gender-guesser/) library to infer the gender of a given director.
<br/>
<br/>
<p align="center">
<img src="https://github.com/ecancellieri/Gender_Bias/blob/master/IMDB/votes_distribution.png" width="600">
</p>
<br/>
While the votes distribution is very similar for Male and Female directors, the movies by Female directors tend to have less votes.
<br/>
<br/>
<br/>
<br/>
<img src="https://github.com/ecancellieri/Gender_Bias/blob/master/IMDB/votes_vs_years.png" width="600">
<br/>
The average rating for Female and Male directors appear to be quite similar across years. However, the number of reviews/votes for Female-directed movies is consistenly and considerably lower than for Male-directed movies.
<br/>
<br/>


----------------------------------------------------------------------------
TO DO:
- ratings + number of votes: possibility: filter by genre and then gender
- are synopsis genderised?
- ratings split into stars via beautiful soap
- ratings split by stars: how are they distributed in regards of the gender of the director?


