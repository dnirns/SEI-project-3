# General Assembly SEI Project 3 - ‘TripSavvy’

### View the deployed site here:

[TripSavvy](https://tripsavvy.herokuapp.com)

## The Team:

This project was a group effort with [Siu Kei Tam](https://github.com/tams2429) & [Eliza Thompson](https://github.com/Elizathompson).

## Overview:

Working in a group of 3, we decided upon building a travel site to help users find a holiday destination.

The user would pick criteria that they want their destination to include from options on the homepage such as ’nightlife’, ‘culture’, ‘nature’, etc. This would find them a destination from a database that had attributes matching all of these choices.

We built our own database of locations and incorporated several API’s to pull in information to display along with each one. We used the [OpenCage](~https://opencagedata.com/~) geolocation API to get their co-ordinates and used that along with Mapbox to add each destination onto a map, providing a detailed view of the location, as well as being able to see all of your saved favourites pinned onto a European map on your own profile page. We also used the [OpenWeather](~https://openweathermap.org/~) API to display the current weather conditions for each location.

Users could sign up for an account to be able to save, favourite and comment on destinations, as well as submit new holiday locations to the database, implementing CRUD (create, read, update, delete) functionality into our site.


## Technical Requirements:
* ****5 days, group project****.
* ****Build a full-stack application**** by making the back-end and front-end.
* ****Use an Express API**** to serve data from a Mongo database.
* ****Consume your API with a separate front-end**** built with React
* ****Be a complete product**** which most likely means multiple relationships and CRUD functionality for at least a couple of models.
* ****Implement thoughtful user stories/wireframes**** that are significant enough to help you know which features are core MVP and which can be cut.
* ****Be deployed online**** so it’s publicly accessible.

## Technical Process:
* Being a group project of three working remotely and with a lot to get done in a relatively short space of time, we planned to work on a rotation of pair coding and working solo. Two of us would pair for a day, then switch to solo so that another pair could work together. This allowed us to maximise everyones involvement in different areas of the project, whilst being able to share our different ideas and perspectives.
* Working in a team remotely, it was important that we continuously shared ideas and communicated our thoughts, so we had regular stand-up and group chats throughout the days.

## Challenges:
As this was the first time implementing a complete back-end database into an app, it presented a lot of challenging new concepts to work with.

In particular the users creation of new entries into the database and their commenting on existing ones, whilst being able to display *which* user had done so in the front-end was quite difficult to begin with.

Working with authentication and conditional rendering in order to only display specific things when logged in / logged out was a new concept that also thew up some complex new problems.

## Win:

Completing the app and realising quite how much we managed to accomplish was a great feeling. We were able to create a complete app with a fully functioning database, authentication, good use of various API’s and some fun front-end logic, which was incredibly satisfying.

It was also a great exercise in team working, and that in itself taught me a lot and was highly rewarding.

I learnt a lot from my team-mates by being able to share ideas and see peoples different approaches to logic and problem solving.

## Technologies:
* JavaScript (ES6)
* CSS/SASS & Bulma
* React.js
* Node.js
* Express.js
* MongoDB / Mongoose
* Bcrypt & JWT Auth

## Possible Future Features:

A few things that we would liked to have added if we had more time:

* A private chat system between users.
* Linking a few more API’s in for the destinations, possibly currency conversions and current flight prices from your nearest airport etc.

## Demo:

Home page and finding a destination:

![home](./frontend/assets/readme-gifs/project-3-demo-1.gif)

Commenting on a destination:

![comment](./frontend/assets/readme-gifs/project-3-demo-comment.gif)

Create a destination:

![create](./frontend/assets/readme-gifs/project-3-demo-create-city.gif)

Profile page:

![comment](./frontend/assets/readme-gifs/project-3-demo-profile.gif)






## Resources:

* [Mapbox API](https://www.mapbox.com/)
* [OpenWeather API](https://openweathermap.org/)
* [OpenCage Data API](https://opencagedata.com/)
