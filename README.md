# Weather Dashboard

A web-app for checking the current weather and 5-day forecast for a city.

## Contents
### About

The issue of obtaining data from the API of one application and using it in the context of another is one that developers frequently face. Developers can access third-party APIs' data and functionality by sending queries to a URL with particular parameters. Your task is to create a weather dashboard with dynamically updated HTML and CSS that runs in the browser.
### User Story

    AS A traveler
    I want to view the weather forecast for several cities as a traveler so that I may prepare for my trip appropriately.

### Acceptance Criteria

   GIVEN a weather dashboard with form inputs
WHEN I search for a city
THEN I am presented with current and future conditions for that city and that city is added to the search history
WHEN I view current weather conditions for that city
THEN I am presented with the city name, the date, an icon representation of weather conditions, the temperature, the humidity, and the the wind speed
WHEN I view future weather conditions for that city
THEN I am presented with a 5-day forecast that displays the date, an icon representation of weather conditions, the temperature, the wind speed, and the humidity
WHEN I click on a city in the search history
THEN I am again presented with current and future conditions for that city


### Visuals:
![Live](<IMG/Screenshot 2023-07-26 at 6.48.11 PM.png>)


![Screenshot of load page]

### Build

Semantic tags have been used in HTML to help with accessibility. Utilizing the Bulma CSS framework, the website was created. Utilizing Bulma reduces the requirement for media inquiries. To customize the website using their offered choices, see the [Bulma documentation] (https://bulma.io/docs/).
Based on user input, the dynamic generation of the HTML content is powered by [jQuery](https://api.jquery.com/). When extracting historical data from APIs, [moment.js](https://momentjs.com/) is utilized to alter date values.


## Setup


SSH: git@github.com:brycehadl/weather-dashboard.git


HTTPS: https://github.com/brycehadl/weather-dashboard.git


## License

This application is released under [MIT](assets/LICENSE.txt) license.
