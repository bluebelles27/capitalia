# Capitalia

So Angular 2.0 has dropped a really early alpha... That probably has a LARGE amount of bugs... But those that know anything about me know that I live for development on the edge. **SO** let's get leaning over the cliff and see if we can't build an app in Angular 2!

This application will provide integration with [geonames.org](http://geonames.org) to provide an interface that allows users to explore difference countries and their capitals.

The application will consist of 3 views.

**Index**
![Index](wireframes/country-capital-index.png)

This view will show some text explaining to users what the application will do.

**Countries**
![Countries](wireframes/country-capital-countries.png)

* This view will show a list of countries displaying their names, country codes, capitals, area in square kilometers, population, and continent code.
* This data will be pulled from the API.
* Clicking on a row will take you to the detail view of that country

**Detail**
![Detail](wireframes/country-capital-country-detail.png)

* This view will show detailed information about the country. Items include country name, population of country, area, capital, population of capital, continent, timezone and number, and names of neighbors.