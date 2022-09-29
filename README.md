# Artemis Map

This is a mapping tool for [*EVE ONLINE*](https://www.eveonline.com). It helps players track connections between locactions in game, as well as where their friends are on the map and a host of other useful information.

This project was insipred by Pathfinder (https://github.com/exodus4d/pathfinder/), and as an attempt to re-create the best features of Pathfinder while utilizing the advantages of a newer technology stack.

The main function is to track players using the EVE API, found here: https://esi.evetech.net/ui/. The location data is used to automatically determine and add new connections to the map, track their status, and allow for storing additional metadata to help players scan for other connections and content within the game.

## Technologies

This project uses VueJS as for the frontend, with Bootstrap for styling. The backend uses NodeJS with Express and self-hosted MongoDB as the database.
The backend can be found in ths repository: https://github.com/BlueSky-Development/EVEMapper-Service

There is also a helper tool for preloading the database with data from the EVE API

## Project setup
```
npm install
```

### Compiles and hot-reloads for development
```
npm run serve
```

### Compiles and minifies for production
```
npm run build
```

### Customize configuration
See [Configuration Reference](https://cli.vuejs.org/config/).
