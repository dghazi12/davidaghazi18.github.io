# Unit 18 PWA Homework: Online/Offline Budget Trackers

## Description

Add functionality to our existing Budget Tracker application to allow for offline access and functionality. The user will be able to add expenses and deposits to their budget with or without a connection. When entering transactions offline, they should populate the total when brought back online.

## User Story

    AS AN avid traveller
    I WANT to be able to track my withdrawals and deposits with or without a data/internet connection
    SO THAT my account balance is accurate when I am traveling

## Criteria

    GIVEN a user is on Budget App without an internet connection

    WHEN the user inputs a withdrawal or deposit
    THEN that will be shown on the page, and added to their transaction history when their connection is back online.
    
## Heroku Link

The link below will give you access to the web application via the Heroku web service:

https://ghazi-workout-tracker.herokuapp.com/

## Requirements

Offline Functionality:

- Enter deposits offline
- Enter expenses offline

When brought back online:

- Offline entries should be added to tracker.

## Local Environment Installation

To run the application locally, first clone this repository with the following command: 

    https://github.com/dghazi12/davidaghazi17.github.io.git

Next, install the application dependencies:

    npm install

Lastly, start the application server using the command line below:

    node server.js or nodemon server.js

## Preview

![](images/WorkoutTracker.gif)