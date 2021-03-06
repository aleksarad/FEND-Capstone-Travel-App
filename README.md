# Overview #

This app takes a location and date input from the user, and returns weather data, country data, and an image using 4 APIs.

![app home page](https://i.ibb.co/27gLLcV/Screen-Shot-2020-02-11-at-11-44-19-PM.png)
![app showing data from APIs after user enters input](https://i.ibb.co/MhK9SgQ/Screen-Shot-2020-02-11-at-11-54-17-PM.png)


## About ##

API data is stored in an object that is then used to update the UI of the app. 
APIs used: http://www.geonames.org/export/web-services.html, https://darksky.net/dev/docs, https://pixabay.com/api/docs/, https://restcountries.eu/
All API calls are made from the client side - besides DarkSkyAPI, which is made on the server side due to DarkSky disabling CORS.


## Dependencies ##

A full list of dependencies can be found in package.json. This project was made primarily with:

* HTML, CSS, JS
* Nodejs
* SASS
* Webpack
* Service Workers
* Jest

## Running the Project ##

1. Download zip and cd into the project.
2. `npm install`
3. `npm run build-prod`
4. `npm start` and go to http://localhost:8000/

