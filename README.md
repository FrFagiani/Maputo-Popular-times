# Maputo-Popular-times
Map developed by Google's popular time function. It shows users activities broken down hour-by-hour for every day of the week.

Further information here:
https://github.com/m-wrzr/populartimes

> - The values are derived from a combination of google searches, google maps app location data, and local traffic data. This data is then used on a per location basis and gives a weekly (by hour and by day) reading for how busy that particular location is on a scale of 1-100. (1 being the least busy, 100 being the busiest a particular location gets, 0 indicating a time that a location is closed).
> - The data is represented as a list of dictionaries, with responses according to the example above
> - The populartimes data for each day is an array of length 24, with populartimes data starting from hour 0 to 23, the wait data is formatted similarly, popularity, current_popularity, rating, rating_n, time_wait, time_spent and phone are optional return parameters and only present if available.

![](/gif/Maputo_google-density-crop.gif)
[Bars-Gif](/gif/Maputo_google-density-crop.gif "Maputo popular places")
