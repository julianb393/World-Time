# World Time

A Flutter project that allows users to view the local time of various cities.

## Getting Started

On startup, the app loads the world time of the current default city of Berlin. This project makes use of the [Wolrd Time API](https://worldtimeapi.org/api) to accurately fetch it's data.

![Home](screenshots/Home.PNG?raw=true "Home Screen")

## Changing The Time

The user can click on the Edit location button, which will open a new view. This view provides a wide variety of cities. 
![Edit Location](screenshots/EditLocation.PNG?raw=true "Edit Location")
When an option is clicked on, will return the user to the Home view with the selected city's local time. Additionally, the background of the Home screen changes depending on whether the locale time is in the day or at night.

![Home Updated](screenshots/UpdatedHome.PNG?raw=true "Home Updated")
