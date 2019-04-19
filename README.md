# Weather Scanner
This is a ReactJS project built to look further into stateless functional components in React.

This project is a weather application that calls the OpenWeatherMap API to render the conditions of supplied cities and countries.


## Installation

Run in command line: 
* `git clone`
* `npm install`
* `npm start`

## File Structure
* `/public`
    * `/index.html`
    * `/favicon.ico` - small icon in tab title

* `/src`
    * `/index.js` - renders App as root in ReactDOM 
    * `/App.js` - exports overall App component that pulls together all components on render()
    * `/App.css` - implements styling
    * `/components` - definitions for all components that are used elsewhere
        * `/Weather.js` - exports Weather component
        * `/Titles.js` - exports Titles component
        * `/Form.js` - exports Form component
    * `/img` - assets for background image
* `/extras`
    * `/hello_react.html` - hello world in react tutorial
* `/node_modules` - no need to ever go in here, stores all the dependencies installed with `npm install`
* `/registerServiceWorker.js` - no need to ever edit, serves assets from local cache to speed up subsequent visits
* `/package.json` - declares dependencies to be installed with `npm install`