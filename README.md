# General Assembly SEI Project 3 - ‘TripSavvy’


## Technical Brief:
* **5 days, group project**.
* **Build a full-stack application** by making your own backend and your own front-end.
* **Use an Express API** to serve your data from a Mongo database.
* **Consume your API with a separate front-end** built with React
* **Be a complete product** which most likely means multiple relationships and CRUD functionality for at least a couple of models.
* **Implement thoughtful user stories/wireframes** that are significant enough to help you know which features are core MVP and which you can cut.
* **Be deployed online** so it’s publicly accessible.


## Technologies:
* JavaScript (ES6)
* CSS/SASS & Bulma
* React.js
* Node.js
* Express.js
* MongoDB / Mongoose
* Bcrypt & JWT Auth

## Overview:
Working in a group of 3, we decided upon building a travel site to help find users a holiday destination.

The user would pick criteria that they want their destination to include from options on the home page such as ’nightlife’, ‘culture’, ‘nature’, etc. This would find them a destination from a database that had attributes matching all of these choices.

We built our own database of locations and incorporated several API’s to pull in infomation to display along with each one. We used the [OpenCage](https://opencagedata.com/) geolocation API to get their co-ordinates and used that along with Mapbox to add each destination onto a map. Providing a detailed view of the location, as well as being able to see all of your saved favourites pinned onto a european map on your own profile page. We also used the [OpenWeather](https://openweathermap.org/) API to display the current weather conditions for each location.

Users could sign up for an account to be able to save, favourite and comment on destinations, as well as submit new holiday locations to the database, implementing CRUD (create, read, update, delete) functionality into our site.

## Made in collaboration with:
 [Siu Kei Tam](https://github.com/tams2429) & [Eliza Thompson](https://github.com/Elizathompson)

## Resources:

* [Mapbox API](https://www.mapbox.com/)
* [OpenWeather API](https://openweathermap.org/)
* [OpenCage Data API](https://opencagedata.com/)

## Deployed site:

[TripSavvy](https://tripsavvy.herokuapp.com)
