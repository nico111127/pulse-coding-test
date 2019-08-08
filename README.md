# Task 1: Data Processing  

In this task, we will look into the [Spotify's Worldwide Daily Song Ranking](https://www.kaggle.com/edumucelli/spotifys-worldwide-daily-song-ranking) dataset.

You are required to use [Jupyter Notebook](https://jupyter.org/index.html) ([How to install?](https://jupyter.org/install.html)) and the Python library [Pandas](https://pandas.pydata.org/) to do an analysis on these music streaming data.

In your notebook, you need to provide answers for the following questions:

1. List the top 10 tracks in the global throughout year 2017 with their total stream counts.

2. List the top 10 artists (or groups) those has the most stream counts for all their tracks combined, with the stream counts of each of their tracks.

3. List the top 10 tracks in December, 2017 for each continent (North America, Europe, Asia, South America, Oceania).

   - You may need [this extra data](./countries.json) for mapping countries to continents.

4. Plot the ranking changes of the Ed Sheeran's "Shape of You" alongside with the stream count changes.  

# Tasks 2: Data Visualization - Year/Month Heatmap

In this task, you need to draw a **Matrix View** to visualize the **Monthly Temperature** of Hong Kong, where the color of each matrix cell encodes the temperature. You can find the data in [temperature_daily.csv](./temperature_daily.csv).

Here are the basic requirements:

1. In the matrix, x direction indicates the year and y direction indicates the month (you can switch them if you like). Each cell indicates the corresponding month of a specific year.

2. You need to visualize the maximum and minimum temperature by month in some way (e.g. you can use click to switch max or min temperature).

3. When hovering mouse on each cell, a tip should appear to show the date and the temperature value.

4. A legend is needed to show the mapping between colors and values.

  An example is like this:

  ![task2](./task2.png)
