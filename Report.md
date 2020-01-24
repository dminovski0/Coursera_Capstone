# Capstone Project - Data Science
## Number of venues in cities in Switzerland and number of venues per population

###Introduction

If you want to visit Switzerland and go to as many places as you can while you are there, this will help you to see which cities have the most venues, and which cities have the most venues per person.

This project analyses the total number of venues in some of Switzerland's cities, and the number of venues compared to the population of their respective cities.

###Data

First, the needed libraries and modules are imported. Then, the data is downloaded from GitHub, where it has been uploaded from another source, namely https://simplemaps.com/data/ch-cities. The original tables have the columns city, lat, lng, country, iso2, admin, capital, population, population_proper.

###Methodology

Some of the columns are renamed and dropped for easier data manipulation. The geocoders module is tested, and the cities of Switzerlands are mapped after that.

Using FourSquare's API, the number of venues of each city is retrieved. Then, the venues are grouped by cities, and in each city the total number of venues can be seen. The variable is "switzerland_venues_in_city"

A pie chart is created showing the cities, the bigger they are, the more venues they have. But, for better illustration, a bar chart is created where the total number of venues per city is set from the smallest from the largest number. Here, the bigger numbers are better. Geneve, Zug and Zurich are the leaders here, and Zurich has more than one third more venues than the second placed city.

But, the bigger cities can be crowded, and the venues as well. If you want to go somewhere where the distribution of the venues per population is bigger, we can find out where. Dividing the number of population of each city with the number of venues, we can find out which city has the most venues per population.

The smaller numbers are better here, and a pie chart and a bar chart are created. Here, Zug, Appenzel and Arau are the leaders, so you can go there without worry of being left out without reservations.

Other analyes are also done, like the frequency of each venue in a city, and the most popular categories of venues for each city are also there. Based on these recommendations, people can get more ready to visit Switzerland.


###Results

It has been discovered which cities have the most venues, and which cities have the most venues per population. This is important, if you want to go to some quiet place where there are no distractions, noise and pollution.

###Discussion

While the data is conclusive, it doesn't show the natural landscapes and wilderness of Switzerland. Trying less popular cities, according to these rankings, can be a surprise too. But if a person wants to play safe, then these charts are a great guide for them.

### Conclusion

It's recommended that you visit Zurich, if you are inclined towards the German language, or Geneve, if you prefer the French language. Zurich is also the place where Einstein got his PhD, so you will see a lot of cultural events and venues.
