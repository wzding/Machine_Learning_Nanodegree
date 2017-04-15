Intercom Analytics Take-Home Exercise

Thanks for taking the Intercom data challenge!
We’re interested in seeing how you work with a small data set in order to generate a recommendation based on your analytics. We’re asking people to return this within a few business days to keep the process moving, but please don’t spend the entire time working on this (we expect it to take 1 hour or less).

When writing up your results, please limit your response to a few pages/slides (including graphs, if necessary), and make sure to submit any files or code to Greenhouse along with the write-up so we can see how you worked through the problem.

If you have any questions, please e-mail justin.berka@intercom.io

Question
Imagine you are an executive producer at a movie studio, and are tasked with picking the genre of your studio’s next movie. Using the data in the included file, which genre would you recommend, and why?

Data
For this exercise, we’ll be looking at a dataset of IMDB movie ratings (movies_data.csv).

The data contains the following fields:
title: Title of the movie
year: Year of release
budget: Total budget in US Dollars (if known)
length: Length (minutes)
rating: Average IMDB user rating
votes: Number of IMDB users who rated this movie
r1-r10: Distribution of votes for each rating, to midpoint of nearest decile: 0 = no votes, 4.5 =1-9% votes, 14.5 = 11-19% of votes, etc. Due to rounding errors these may not sum to 100.
mpaa: MPAA rating
action, animation, comedy, drama, documentary, romance, short: Binary variables representing if movie was classified as belonging to that genre
