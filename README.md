# Unit 12 Homework: Mission to Mars

## Part  1: Scrape Mars News

Jupyter Notebook, Splinter, and BeautifulSoup were used for the initial scraping.

* The Jupyter Notebook file called `mars_data_challenge_part_1.ipynb` shows all your scraping and analysis tasks.

## Part 2: Scrape and Analyse Mars Weather Data
- - -

An HTML table of Mars weather data was extracted. Pandas and Matplotlib were used to clean, visualise, and analyse the data.

* The Jupyter notebook `mars_data_challenge_part_2.ipynb` shows part 2 tasks done.

1. Answer the following question: how many months are there on Mars?
* There are 12 months on Mars.

2. Answer the following question: how many Martian (not Earth) days' worth of data are there in the scraped dataset?
* There are 1867 Martian days' worth of data in the scraped dataset.

3. Answer the following question: what are the coldest and warmest months on Mars (at the location of Curiosity)? Obtain the answer by averaging the minimum daily temperature of each month. Plot the results as a bar plot.
* The coldest month on Mars is month 3 with an average of -83.3°C while the warmest month is month 8 with an average of -68.4°C.

4. Answer the following question: which months have the lowest and highest atmospheric pressure on Mars? Obtain the answer by averaging the daily atmospheric pressure of each month. Plot the results as a bar plot.
* Month 9 has the highest average pressure on Mars with 913.3 while Month 6 has the lowest with an average of 745.0

5. Answer the following question: approximately how many terrestrial (earth) days are there in a Martian year? In other words, in the time that Mars circles the Sun once, how many days elapse on the Earth? Estimate the result visually by plotting the daily minimum temperature.
* It can be observed that the pattern of the Minimum Temperature repeats around every two years on Earth. It is possible to say that a Mars's Year is around 2 Years on Earth.

* The DataFrame was exported to a CSV file.