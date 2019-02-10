# React-MyMap

### Project Description
This project is the last project (CAPSTONE project 8) of the Udacity Full Nanodegree Program Front-End Web Development.
MyMap is a Single Page Application (SPA) created in `React` and developed with `create-react-app`. 
It fetches data from `Google Maps API` and `FourSquare API`. 

![neighborhoodmap](https://github.com/dianavile/NeighbourhoodMap/blob/master/Neighbourhoodmap.png)

### Project requirements
The goal of this project is to build a Single Page Application (SPA) created in `React` to show a GoogleMap of your neighbourhood.
Requirements: implement third-party APIs GoogleMap and Foursquare to provide additional information about the location.
Additional functionality: map markers, infowindow, search funcion, list view. 

Setting Up
=================
To  __install__ this project:
```
npm start 
```
To  __clone or download __ this project:
```
    $ git clone https://github.com/dianavile/MyMap.git
```
- To open the folder to  __run the project __:
```
`npm install`
```
 - To  __run the development server__:
 ```
`npm start`
```
  - To  __view the app in the browser__:
- Open [http://localhost:3000](http://localhost:3000).


Project Directory
=================
Inside the __project directory__, it will generate the initial project structure and install the dependencies:
```
mymap
├── README.md
├── package.json (=here all dependencies will be installed.)
├── .gitignore (=file to instruct which files need to be ignored at production).
├── public
│   ├── favicon.ico
│   ├── index.html
│   └── manifest.json
└── src
    ├── App.css
    ├── App.js
    ├── App.test.js
    ├── index.css
    ├── index.js
    ├── logo.svg
    └── serviceWorker.js
```
## React Components
The MyMap app contains the following __components__:
```
└── src
    ├── NavigationBar.js
    ├── Map.js
    ├── MapStyle.json
    ├── Locations.js
    ├── SideBar.js
```

Deploying
=================
To deploy the project, use the following command in your Terminal:

 ## Service Worker
 `Create React App`includes a service worker, by default. 
To enable the service worker, run the application in production build mode:

 ```
npm run build
```
This comment builds the app for production to the `build` folder.<br>
It bundles React in production mode and optimizes the build for the best performance in a minified version.
More information about [deployment](https://facebook.github.io/create-react-app/docs/deployment).

## Browser requirements
The minimum default set of browsers for this project are:
```
"browserslist": [
    ">0.2%",
    "not dead",
    "not ie <= 11",
    "not op_mini all"
  ]
```
This means, the project is available on most default browsers, except on: Internet Explorer < 11 and opera_mini.
More info on [changing default browsers](https://github.com/lukeed/pwa/issues/48)

Dependencies
=================
This project is build with the following dependencies:

 #### Packages (Dev dependencies- npm packages)
To install all development dependencies, check the provided links:
 - [Create-react-app](https://github.com/facebookincubator/create-react-app)
 - [Material IO](https://www.npmjs.com/package/create-react-app)

 #### API
 - [Google Maps API](https://cloud.google.com/maps-platform/)
 - [Foursquare API](https://developer.foursquare.com/)

 #### Design
- [Google Fonts](https://fonts.google.com/)
- [Material IO](https://www.npmjs.com/package/create-react-app)

Version
=================
#### "version": "0.1.0" 
This is the first piece of version information, coded from scratch.

__Know bugs__
working hard to get rid of the bugs.

Contributors
=================
As this project is part of a official FrontEnd Nanodegree curriculum, no contributors are allowed.

License
=================
This project is distributed under the MIT licence.  See ``LICENSE`` for more information.

Code References
=================
- [Create React App documentation](https://facebook.github.io/create-react-app/docs/getting-started).
- [Writing READMEs. Udacity](https://classroom.udacity.com/courses/ud777/)
- [Google Maps Platform Documentation](https://developers.google.com/maps/documentation/)
- [Google Maps JS API v3 - Simple Multiple Marker Example](https://stackoverflow.com/questions/3059044/google-maps-js-api-v3-simple-multiple-marker-example)
- [Foursquare Developers Documentation](https://developer.foursquare.com/docs)
- [React documentation](https://reactjs.org/).
- [W3school- Sidebar](https://www.w3schools.com/w3css/w3css_sidebar.asp)
