# Match and Catch
## Project Description

Match and Catch is a React website for used car buying and auctions.
The App utilizes  React built-in and custom hooks and allows users to add, edit and delete auctions in real time.
Data is persisted by the API server using a PostgreSQL database. The client application communicates with an API server over HTTP, using the JSON format.

## Project Features
- A user can put the car on the website to auction, or buy a car auctioned by other users
- A user needs to fill in car-related information during the auction process, including manufacturer, model, color, state, year of manufacture, etc.
- A user can view information about cars that are being auctioned and the bid prices of other users
- A user can view auction history including price, progress and other information
- A user can view the top five most popular car brands and models in auctions

### Home page
!['home-page'](hhttps://github.com/JunqiDu/matchandCatch/blob/main/docs/localhost_3000_.png)
_ The home page of Match and Catch._

### Past auction page
!['past-auction-page'](https://github.com/JunqiDu/matchandCatch/blob/main/docs/localhost_3000_pastAuction.png)
_ User can check the auctions history here. The successful auction in green, unsuccessful auction in red and in auction in yellow._

### Inventory page
!['inventory-page'](https://github.com/JunqiDu/matchandCatch/blob/main/docs/localhost_3000_inventory.png)
_ User can check the car in auction and the price of the car._

### Inventory item page
!['inventory-item-page'](https://github.com/JunqiDu/matchandCatch/blob/main/docs/localhost_3000_inventory_1.png)
_ The detail of each car in auction shown here._

### Leaderboard page
!['leaderboard-page'](https://github.com/JunqiDu/matchandCatch/blob/main/docs/localhost_3000_leaderboard.png)
_ The top 5 popular car shown here._

 **Note** : _For full functionality both must run concurrently: the client and the API server applications (see database* setup below)._

## Installation

```npm install```

If you face some error of Babel icon, you can use the following command to fix them.

```npm install babel-plugin-macros```

```npm i --save @fortawesome/fontawesome-svg-core```

```npm i --save @fortawesome/free-brands-svg-icons```

```npm install --save @fortawesome/free-solid-svg-icons```

```npm install --save @fortawesome/react-fontawesome```

## Running Webpack Development Server

```npm start```

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

The page will reload when you make changes.\
You may also see any lint errors in the console.

### `npm test`

Launches the test runner in the interactive watch mode.\
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

## API server/*Database Setup

For full functionality both must run concurrently: the client and the API server applications.
- Start by forking and cloning the scheduler-api server [here](https://github.com/JunqiDu/matchandcatch-api)
- Follow the steps outlined in README to install and setup the database
- Fork and clone this repo
- Navigate to the root directory and install dependencies with `npm install`
- Once you have the database setup and the scheduler-api server running, run the following command from the root directory of the project `npm start`

## Project Stack

__Front-End:__ React, Axios, JSX, HTML, CSS, JavaScript

__Back-End:__ Express, Node.js, PostgreSQL

## Dependencies
- Axios
- Classnames
- Normalize.css
- React
- React-dom
- React-scripts
- Babel/core
- Babel-loader
- Babel-icon
- Node-sass
- Prop-types
- PostgreSQL