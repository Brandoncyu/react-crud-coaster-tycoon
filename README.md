# React CRUD Coaster Tycoon

This repository is an opportunity to practice managing state with API calls.

## Dependencies

This project assumes you have the [related API](https://github.com/bwreid/react-crud-coaster-tycoon-api) up and running.

## Setup Instructions

1. Fork/clone

1. `npm install`

1. `npm start`

## Guiding Questions

* Describe the [models/Park.js](https://github.com/bwreid/react-crud-coaster-tycoon/blob/master/src/models/Park.js) file. What is it responsible for?
> These are our CRUD routes.

* Describe [these methods](https://github.com/bwreid/react-crud-coaster-tycoon/blob/master/src/App.js#L16-L27) inside of the `App.js` file. When will each method be called?
> ComponentsWillreceiveProps

* Why must we pass the `selectPark` function [from App.js to the ParksList.js](https://github.com/bwreid/react-crud-coaster-tycoon/blob/master/src/components/ParksList.js) file?
> Some of the CRUD routes require id to access the info in the backend.

* What is [this line](https://github.com/bwreid/react-crud-coaster-tycoon/blob/master/src/components/ParksList.js#L5) doing inside of the `ParksList.js` file?
> It lets you know which one is active.

* Take a look at how state is declared [in the Park.js file](https://github.com/bwreid/react-crud-coaster-tycoon/blob/master/src/components/Park.js#L6-L8). Why do we need to specify `rides` as an empty array?
> Because this is what will be updated. 

* What is [this line](https://github.com/bwreid/react-crud-coaster-tycoon/blob/master/src/components/Park.js#L23) doing in the `Park.js` file?
> To guide the user to the next step.

* What is the [onChange method](https://github.com/bwreid/react-crud-coaster-tycoon/blob/master/src/components/ParkForm.js#L15-L19) doing in the `ParkForm.js` file?
> Changing the state.

* How does [this line](https://github.com/bwreid/react-crud-coaster-tycoon/blob/master/src/components/ParkForm.js#L49) work in the `ParkForm.js` file? What happens if you do _not_ use the double bang?
> Error Handling.
