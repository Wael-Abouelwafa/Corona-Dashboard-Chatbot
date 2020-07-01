# CoronaDashboard-Chatbot

dashboard to monitor and analysis the evolution of covid19 in the world
 and chatbot to answer the questions about Covid-19
 
 Heroku link : https://corona-d.herokuapp.com/ 
 2.1.	Software Architecture

1.	Import needed libraries (NUMPY & Pandas and Dash

•	Dash Core Components :The Dash Core Component library contains a set of higher-level components like sliders, graphs, dropdowns, tables, and more.
•	Dash HTML Components :Dash provides all of the available HTML tags as user-friendly Python classes


2.	Dashboard Setup

•	By default, Dash is un styled ,The Codepen is a work-in-progress CSS style guide, CSS stylesheets is added to the dash apps by URL

3.	Dashboard Layout
•	Create Dash board Server
•	Title the Dash board ('Covid-19 Dashboard')
•	Read the COVID data file from Europe CDC web site
•	cleans COVID data. Countries with population 
•	get last update date
•	delete weird cases
•	sort by country and date
•	reset data frame index
•	rename columns
•	Drop un used columns
•	remove countries under population threshold
•	remove leading zeros by country
•	ADD day counts
•	removes the initial date points where cases and deaths are zero

4. MATH FUNCTIONS

•	Fits linearly the log(y) - natural log
•	remove points where log does not exist
•	Calculates the relative growth starting from a daily series
•	suppress warnings as you might have division by zero
•	centered moving average with window reduction at the extremities.

5.	SIGNAL EXTRACTION

•	Extracts signal for given country considering signal type (cases ,deaths) and optional flags like population normalization, moving average and extrapolation"""
•	moving average
•	extrapolation
•	 extract last data points
•	Interpolation
•	extrapolate only if fit exists and has negative slope
•	total values at collection date

6.	APP callback

 
 Chatbot still under update it will be available soon
 
 thanks :)
