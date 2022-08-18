# History of Tornadoes in Tennessee 1979-2021
### Table of Contents
- Motivation
- Questions
- Technology
- Process
- Challenges
- Data Sources
- Link to Project

### Motivation
I've always been interested in weather and curious about climate change. When my family and I moved to Middle Tennessee from Virginia a little more than a year ago, we quickly learned about Tennessee heat and humidity. We live just East of Nashville and, as we got to know the area and our neighbors, we also learned about tornadoes in Tennessee.

While exploring our new home in Middle Tennessee, we would often come across the damage caused in MT. Juliet when multiple tornadoes ripped through their community in March, 2020. That left me feeling vulnerable and unprepared for the next round of tornadoes that will likely come through again. Not only do I want to learn more about tornado activity in Tennessee, my hope is that the data would help my family determine if we should have a backup generator installed for our home. The idea of spending a week in the Tennessee heat and humidity without power is a scary thought.

### Questions
- Are tornado occurrences in TN increasing each year?
- Where do the majority of tornadoes hit in TN?
- Should my family buy a backup generator for our home?

### Technology
- Python (Jupyter Notebooks, pandas)
- Excel
- Tableau

### Process
There is a lot of weather data available. I decided to focus on the history of tornadoes that caused measurable damage. While sources like NOAA and Weather.gov provide excellent data on everything tornadoes, I found that FEMA provides more specific data for tornadoes that caused damage, with the ability to narrow the data down to the county/city level and even month. I did most of my data cleaning in Excel, then explored the data in Python (Jupyter Notebooks). By using Python to create smaller chunks of data to review, I was able to find my path and inspiration for what I wanted my presentation to convey. After that, I used Tableau to create my vision.

### Challenges
The data from FEMA shows counties in columns, but I wasn't able to convert the file into a geospatial environment. I found data in TN.gov that provided the geometry I needed. I merged my cleaned data from FEMA with the county data from TN.gov using Python. This allowed me to dig deeper into the data, as well as the opportunity to create a more informative overall presentation.

### Data Sources
- https://www.fema.gov/about/openfema/data-sets
- https://tn-tnmap.opendata.arcgis.com/

### Link to Project
