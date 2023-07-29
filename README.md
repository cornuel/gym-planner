# Gym Planner is live [HERE](https://cornuel.github.io/gym-planner/)
Please wait a few seconds in order to wake the backend server as I am hosting it using a free plan for now.

#### [Gym Planner](https://cornuel.github.io/gym-planner/) is a workout tracker that aims to help you do your physical activities in a daily basis.

#### **Demo Account**
- Username: demo
- Password: Demo1234$

## Features

- **Sign-up** and **Login** pages
- A **dashboard** with 4 core pages:
	- **[Overview](https://cornuel.github.io/gym-planner/)** : Reminds you if you have exercises to do today - Gives you informations about all the reps you did since you used the app, the maximum weight you did at bench-press and maximum duration you did for the plank exercise for example 😄
	- **[Week Planner](https://cornuel.github.io/gym-planner/)**: Plan you physical activities one week ahead and add your favorite exercises. Keep track of your sets/reps, weight/duration, you can even add comment to your exercises.
	- **[Exercises Library](https://cornuel.github.io/gym-planner/)**: Large library of exercises sorted by body parts, each exercise has an info button on how to do the exercise properly
	- **[History](https://cornuel.github.io/gym-planner/)**: Keeps all your exercises safe filtered by exercises done.
- **Dark mode** enabled, and possibility to change the primary color to a color of your choice from the catppuccin pastel theme.

## Built using

### Backend **Flask** (repo [here](https://github.com/cornuel/workout_tracker_backend))

- **Flask**
- **Bcrypt**: encrypt and decrypt sensitive informations
- **bleach**: helps sanitize some workout fields
- **graphene**: to design Gym Planner GraphQL API
- **pymongo**: to interact with the MongoDB database

### Frontend **Vue.js** (repo [here](https://github.com/cornuel/workout_tracker_frontend))

- **Pinia**: A state management library used to define a user store that contains the user's token, login with getters and setters.
- **Tailwind**: for UI developement productivity and consistency across components.
- **Vuetify**: first time using this UI library, it allowed me to quickly design core components
- **Axios**: for the HTTP requests.
- **Vue Apollo**: allows me to manage GraphQL data within the frontend app
- **Vue Toastification**: provides a simple and flexible notification library to show success, error, warning, and information messages.
- **Swiper**: provides sliders to easily navigate through the exercises library
- **Homemade Animated Place Holder**: to improve user experience when waiting for data to be fetched.
- **Font Awesome**

### MongoDB Database

## What I learned
- [x] Flask development with graphene's schema and models, pagination etc..
- [x] GraphQL queries and mutations
- [x] Structure MongoDB collections
- [x] MongoDB aggregations to efficiently manipulate data
- [x] The Apollo Library to do CRUD operations on the DB
- [x] Frontend designing, ease of use and practicallity
- [x] Backend hosting
