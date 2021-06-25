# Introduction

A mini project for starting journey in Data Analyics. The data was collected from Udacity. Learned to use SQL to filter the data from the database such as using COALESCE, CTE, etc. Used Excel to build visualizations and view findings about the data.

## Dataset informations

1. [global_data.csv](global_data.csv): Global average temperature from year 1750 to 2015
2. [city_data.csv](city_data.csv): Surat(City in Gujarat) average temperature
3. [indian_cities_temp.csv](indian_cities_temp.csv): Average temperature of Indian cities from either Gujarat state or rest of India
4. [gujarat_temp.csv](gujarat_temp.csv): Gujarat(State in India) cities temperature from year 1750 to 2015
   
   **Columns** 
    |   Name  | Description |
    |---------|-------------|
    |   year  | Year |
    |   gdtemp  | Global average temperature |
    |   srt  | Surat city temperature |
    |   rjt  | Rajkot city temperature |
    |   ahm  | Ahmedabad city temperature |
    |   vad  | Vadodara city temperature |

5. [final_data.csv](final_data.csv): Average global temperature with null values filled with average of temperature



## Insights

[Exploring Weather Trends](Exploring_Weather_Trends.pdf) : Report on how the data was colleced and what observations were found

### Highlights

Few highlights from the report is as follows

1. Surat city have hotter temperature than the global temperature and the difference is almost similar.
2. From 20th century, the temperature has been rising at a consistent rate.
3. Surat and global temperature had a correlation of 0.89
4. Out of the 4 cities in Gujarat in the dataset, Rajkot had the highest temperature.
    
    The trend is as follows: Rajkot > Surat = Vadodara > Ahmadabad