The Objective of this problem is to predict the bike rental count on daily basis on environmental and seasonal settings on the basis of 15 features given in the original dataset.
The data consists of 15 Independent Variables and 1 dependent variable. The Independent Variables are:
I. Instant: It is a continuous variable. This feature depicts the record index.
II. dteday: It is a date-time variable. This feature has the date on which bikes are rented.
III. Season: It is a categorical variable. This feature contains information about the season during which the bike was rented. It is categorised into 4 categories each depicts a separate season. The number 1 refers to Spring, 2 refers to Summer, 3 refers to Fall and 4 refers to Winter.
IV. Yr: It is a categorical variable. This feature tells us about the year in which the bike has been rented. Here 0 refers to 2011 and 1 refers to 2012.
V. Mnth: It is a categorical variable. This feature tells us about the month in which the bike has been rented. It has numbers from 1 to 12 where each number refers to the respective month of the year.
VI. Holiday: It is a categorical variable. This feature tells us whether it is a holiday or not on any particular day on which the bike has been rented. The holidays are extracted from holiday schedule.
VII. Weekday: It is a categorical variable. It tells about the day of the week on which bike was rented. It has values from 0 to 6.
5 | P a g e
VIII. Working day: It is a categorical variable. It refers to the day which is neither weekend nor holiday. If the day is working day then it is 1 otherwise 0.
IX. Weathersit: It is a categorical variable. It tells about the weather condition on the day the bike was rented. 1 refers to Clear, Few clouds, Partly cloudy, Partly cloudy, 2 refers to Mist + Cloudy, Mist + Broken clouds, Mist + Few clouds, Mist, 3 refers to Light Snow, Light Rain + Thunderstorm + Scattered clouds, Light Rain + Scattered clouds, 4 refers to Heavy Rain + Ice Pallets + Thunderstorm + Mist, Snow + Fog.
X. Temp: This is a continuous variable. It depicts the normalized temperature of the day on which the bike was rented. It is calculated using the formula (t-tmin)/(tmax -tmin).
XI. Atemp: This is a continuous variable. It depicts the normal feeling temperature of the day on which the bike was rented. It is calculated using the formula (t-tmin)/(tmax -tmin).
XII. Hum: It is a continuous variable. It depicts the normalized humidity of the day on which bike was rented. The absolute humidity value is divided by 100 (max humidity).
XIII. Windspeed: It is a continuous variable. It represents the normalized wind speed. The absolute wind speed value is divided by 67 (max wind speed).
XIV. Casual: It is a continuous variable. It represents the count of casual users out of total bikes rented.
XV. Registered: It is a continuous variable. It represents the count of registered users out of total bikes rented.
XVI. Cnt: It is a continuous variable. It represents the total count of bikes rented.

After performing extensive exploratory data analysis the data is given to multiple models like Linear Regression, Decesion Tree Regressor, Random Forest Regressor, 
Gradient Boosting Regressor with and without hyperparameter tuning, the fineal results are obtained and cpmpared on metrics like Mean Squared Error, R2 Score and 
Mean Absolute Percentage Error.
