First, the needed libraries and modules are imported. Then, the data is downloaded from GitHub, where it has been uploaded from another source. Some of the columns are renamed and dropped for easier data manipulation. The geocoders module is tested, and the cities of Switzerlands are mapped after that.

Using FourSquare's API, the number of venues of each city is retrieved. Then, the venues are grouped by cities, and in each city the total number of venues can be seen. The variable is "switzerland_venues_in_city"

A pie chart is created showing the cities, the bigger they are, the more venues they have. But, for better illustration, a bar chart is created where the total number of venues per city is set from the smallest from the largest number. Here, the bigger numbers are better. Geneve, Zug and Zurich are the leaders here, and Zurich has more than one third more venues than the second placed city.

But, the bigger cities can be crowded, and the venues as well. If you want to go somewhere where the distribution of the venues per population is bigger, we can find out where. Dividing the number of population of each city with the number of venues, we can find out which city has the most venues per population.

The smaller numbers are better here, and a pie chart and a bar chart are created. Here, Zug, Appenzel and Arau are the leaders, so you can go there without worry of being left out without reservations.

Other analyes are also done, and the most popular categories of venues for each city are also there. Based on these recommendations, people can get more ready to visit Switzerland.
