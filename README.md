# UFO Sightings-Weather Analysis-Alcohol Consumption
## Project Overview
Over the next few months, I’ll be diving deep into UFO sightings and weather data to uncover correlations between atmospheric conditions and how often unidentified flying objects are reported. My goal is to understand the weather conditions under which UFOs are most commonly identified and what factors might influence these sightings. (see PS)
## Motivation
I've always been skeptical about extraterrestrial life. Therefore, I want to analyze UFO sighting patterns to determine whether their occurrences follow a foreseeable pattern or are purely random and coincidental. This analysis may lead to intriguing insights or even unwise conclusions regarding whether alleged alien activity is predictable—thus suggesting its plausibility—or entirely fictional.
## Data Sources
I will collect ufo sightings data from kaggle and weather data from local weather forum.
* Weather Data : https://www.wunderground.com/history/daily/us/va/arlington/KDCA/date/2011-3-14
* UFO Sightings Data : https://www.kaggle.com/datasets/NUFORC/ufo-sightings 
* Alcohol Consumption: https://www.niaaa.nih.gov/sites/default/files/surveillance-report121.pdf (year 2013)
* USA population in 2013: https://www.factmonster.com/us/fifty-states/state-population-rank-2013
  
UFO sighting data is quite substantial in size; however, I will focus only on USA to reduce the dataset. This will allow me to work with a smaller, more manageable dataset, making the analysis more efficient.

## Tools and Technologies
* Python: For data cleaning and statistical analysis
* Pandas: To manipulate and preprocess data
* Matplotlib and Seaborn: For creating visualizations (scatter plots, heatmaps, time series)
* Potential usage of web scraper (for creating manual data from weather sites)

## Hypotheses
1. UFO Sightings-Weather Conditions.
* Null Hypothesis (H₀): Weather conditions have no significant effect on the frequency of UFO sightings.
* Alternative Hypothesis (H₁): UFO sightings occur more frequently under specific weather conditions than would be expected by chance.
2. UFO Sightings-Alcohol Consumption
* Null Hypothesis (H₀): There is no relationship between alcohol consumption per capita and the number of UFO sightings per state.
* Alternative Hypothesis (H₁): There is a relationship between alcohol consumption per capita and the number of UFO sightings per state.



## PS
I originally intended to investigate the effect of weather conditions on UFO sightings. Although I managed to find a large dataset of historical weather information, I realized that matching each UFO sighting to the specific weather conditions of its exact day, month, year, and time would be extremely time-consuming. As a result, I decided to explore alternative relationships for my analysis. However, I am keeping the first hypothesis regarding weather conditions because I would still like to find a way to match the two datasets in the future.
