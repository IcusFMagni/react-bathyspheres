# Express/Passport with React
This version uses React to control the login requests and redirection in coordination with client-side routing.

## Setup Directions:
* Run `npm install`,
* Start mongo if not running already by using `mongod`
* Run `npm run start:server` in an open tab of terminal to start the server
* Run `npm run start` in an open tab of terminal to start the web site

## Production Build:
* Start mongo if not running already by using `mongod`
* Run `npm run build` in an open tab of terminal to build the react application to /build
* Run `npm run start:server` to start the server
* Navigate to `localhost:5000` to view the site


### Lay of the Land
* `src/` contains the React application
* `server/` contains the Express App
* `public/` contains static assets for the client-side
