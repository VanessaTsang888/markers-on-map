# Markers on Map Website Application

This website application will generate and plot multiple markers on a map (the number of markets will be defined on the Settings the user has set). The idea is for the user (investigators and police officers) to efficiently located a person details/data such as their name, age and location. Also, the person company they work for. This is a real time and dynamic application as simply tapping on a marker will display critical data for the user.

This dynamic application will be a part of a larger application used to investigations and intelligence work.

## Instructions

Once application is launched, the user can use the hand-curser to move around the map just as they can on Google Maps application as this application uses the Google Maps API. This is true for the Zoom-in, Zoom-out buttons on the bottom right of the screen.

This website application is for users to track a person (or user) name and location. Also, the persons company they work for - name and location.
Once the user has arrive on the application first page, they will see two markers generated and plotted on the map. Then user will click or tap on the user marker to display a persons name and their current location. Then user will click on the second marker to display the person's componey that they work for. User can display data from both markers at the same time.

## Extra Features

In the futre some new featurs and functionality will be developed such as a button called: Report A Problem which will allow user to log a problem with the Tech Support Team. This will be an important security feature in minimise any future [security vulnerbilites](https://owasp.org/www-community/vulnerabilities/).

## The tech stack

- TypeScript.js # JavaScript patterns for reusable code (components) to adhere to the DRY (do not repeat yourself) software development best practice.
- Faker module # A popular library that generates test data that can be used for things such as unit testing, performance testing, building demos, working without a complete backend.

## Requirements

- [Node.js](https://nodejs.org/)
- [npm](https://docs.npmjs.com/downloading-and-installing-node-js-and-npm)
- [Google Map API](https://developers.google.com/maps/documentation/javascript)
- [Faker module](https://fakerjs.dev/guide/)

## Getting started

- $ git clone # clone down the repository from GitHub.
- Navigate to the directory or project on your local machine.
- $ npx parcel index.html # Compile and execute the application. Server running at http://localhost:1234
