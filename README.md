# Chicago, Bike Grid Now Bike Bus Tracker

## Overview
This project was created to provide live tracking for bike buses hosted by Chicago, Bike Grid Now!

## Bike Bus Drivers 
Drivers of the bike bus will use a special link (bike-bus.bmcfadden.me/beacon/:route/:beacon_code) that will capture their location using the browser and stream it live to the front end platform accessed from the home page allowing anyone to view where the bike bus is along it's route. Please sync up with a CBGN organizer if you don't have the beacon code that allows you to actually broadcast location. 

### Adding a Route to the Tracker
If you want to self-service and have a bike bus route added to the tracker, you can do so by creating a pull request and manually editing the routes.json and mirroring the structure of one of the other routes. If you want to cheat slightly, you can use [this python script](https://github.com/brandonmcfadd/gpx-to-bike-route) to convert a GPX file (downloaded from virtually any route planning service) to quickly convert the GPX file to the json structure that can be copied/appended to the existing routes. Otherwise, please open an issue in GitHub and attach your existing GPX file and any requirements and I can work to get it added as time permits. 