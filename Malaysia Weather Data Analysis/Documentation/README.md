# ADS1001_Project

## DATASET: Weather
### TOPIC QUESTION:"How do wind speed, gust patterns, and wind chill vary across different regions in Malaysia and what are their implications for the renewable energy sector?"

### Sub-Questions:
##### **MEDELLIN:**
1. "How do wind speed and gust intensity vary across different regions of Malaysia?"
##### Variables used: 
- `wind_speed`
- `gust`
- `place`
- `state`
##### POSSIBLE CHART TYPES: 
- Bar chart (mean per region)
Penang > KL
Penang is more suitable ……
Top 3: Batu Maung, Sungai Puyu, Sepang
- Box plot (distribution)
Penang > KL
Some areas display extreme wind conditions (>25 m/s)
Batu Maung looking to be top candidate
- Heatmap (regional comparisons)

##### **JUN SIANG:**
2. "What is the daily and monthly variability of wind speed and gust intensity, and how consistent are these patterns across regions?"
##### Variables used: 
- `wind_speed`
- `gust`
- `year`
- `month`
- `day`
- `state`
- `place`
##### POSSIBLE CHART TYPES: 
- Line plot (trend over time)
	Some missing months for certain regions
	Batu Maung seems most consistent out of the 3
- Stacked bar chart (by region/month) 
Penang shows more variance over the months, likely due to it being a coastal region, affected by monsoons and sea breeze
- Histogram (wind variability)


##### **QI ZHI:**
3. "How does wind chill vary by region and time of day, and what does this imply about perceived temperature extremes?"
##### Variables used: 
- `wind_chill`
- `hour`
- `place`
- `state`
- `wind_speed`
- `temperature`
##### POSSIBLE CHART TYPES: 
- Box plot (wind chill distribution by region)
- Line plot (wind chill across hours)
- Scatter plot (wind speed vs wind chill)

##### **SHARON:**
4. "What is the relationship between wind speed, gust, and other weather variables like humidity, temperature, and pressure?"
##### Variables used: 
- `wind_speed`
- `gust`
- `temperature`
- `humidity`
- `pressure`
- `dew_point`
##### POSSIBLE CHART TYPES: 
- Scatter plots
- Heatmap (correlation matrix)
- Density plots

##### **ANUSHA:**
5. "Which regions exhibit the most extreme wind events (high gusts or wind speed) and how often do these occur?"
##### Variables used: 
- `wind_speed`
- `gust`
- `place`
- `year`
- `month`
- `day`
##### POSSIBLE CHART TYPES: 
- Histogram (frequency of high gusts)
- Bar chart (extreme events per region)
- Line plot (Trends over time)

##### **JIA YI:**
6. "At what times of day do peak wind speeds and gusts typically occur across regions?"
##### VARIABLES USED: 
- `wind_speed`
- `gust`
- `hour`
- `place`
##### POSSIBLE CHART TYPES: 
- Line plot (average wind speed by hour)
- Heatmap (region vs hour)
- Stacked bar chart (hourly gust occurrences by region)
