# Exploratory Data Analysis on Spotify 2023 Dataset
Name: Miko Ksyle B. Cruz <br>
Section 2ECE-D <br>
Date 11/9/2024 <br>
# Documentation
<h3>GUIDE QUESTIONS:</h3>

<h4>Overview of Dataset</h4>
1. How many rows and columns does the dataset contain?<
2. What are the data types of each column? Are there any missing values?<br><br>

<h4>Basic Descriptive Statistics</h4>
1. What are the mean, median, and standard deviation of the streams column?
2. What is the distribution of released_year and artist_count? Are there any noticeable trends or outliers? <br><br>

<h4>Top Performers</h4>
1. Analyze the trends in the number of tracks released over time. Plot the number of tracks released per year. 
2. Does the number of tracks released per month follow any noticeable patterns? Which month sees the most releases? <br><br>

<h4> Temporal Trends</h4>
1. Analyze the trends in the number of tracks released over time. Plot the number of tracks released per year.
2. Does the number of tracks released per month follow any noticeable patterns? Which month sees the most releases?<br><br>

<h4>Genre and Music Characteristics</h4>
1. Examine the correlation between streams and musical attributes like bpm, danceability_%, and energy_%. Which attributes seem to influence streams the most? 
2. Is there a correlation between danceability_% and energy_%? How about valence_% and acousticness_%?<br><br>

<h4>Platform Popularity</h4>
1.How do the numbers of tracks in spotify_playlists, spotify_charts, and apple_playlists compare? Which platform seems to favor the most popular tracks? <br><br>

<h4>Advanced Analysis</h4>
1. Based on the streams data, can you identify any patterns among tracks with the same key or mode (Major vs. Minor)?
2. Do certain genres or artists consistently appear in more playlists or charts? Perform an analysis to compare the most frequently appearing artists in playlists or charts. <br><br>

# Summary
<h3>Overview of Dataset</h3>
The overview can be done using a few of the built-in functions in Python such as .describe and() and .info().<br>

<h3>Basic Descriptive Statistics</h3>
Cleaning was required to gather the data for streams for the rest .info() solved it. Histograms, boxplots, and score are used to determine trends and outliers for distribution.<br><br>

<h3>Top Performers</h3>
The top performers were quite straightforward, just sort of gathering the five largest<br><br>

<h3> Temporal Trends</h3>
A line graph and bar plot are used to see the distribution of year and month. <br><br>

<h3>Genre and Music Characteristicss</h3>
the .corr function and the heat map were heavily utilized to visually see correlations. <br><br>

<h3>Platform Popularity</h3>
Once again, the .corr function and the heat map were heavily utilized to visually see correlations and manual solving was also used.<br><br>

<h3>Advanced Analysis</h3>
This part was the most challenging as it combined different learning to fully get the required output. Pie charts and bar graphs were used to visualize major vs. minor questions and the most frequent artist.<br><br>

# Analysis and Insight
<h3>Please see the notebook file as it is places their along with the data.





