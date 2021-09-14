## Overview
Fully functional world clock web application featuring a main screen which displays a selected world clock, and a side bar where the user can view smaller world clocks. The user can select from a variety of different timezones to display a clock for by pressing the + button. Responsive design makes this application friendly for displays of all sizes. The mobile view features a list screen for viewing all of the selected timezone’s world clocks, and a main display screen to show a larger view of the selected world clock.

## Implementation
The Electron framework was used to package the world clock application as a desktop application, and Capacitor was used to package the application as an iOS app. The timezone offsets of each clock are represented in the hash. To select/deselect timezones, a modal is offered with a select element with all of the different available timezones. The modal is from materialze.

## Stack Used
[CSS](https://www.w3schools.com/css/default.asp) ,
[HTML](https://www.w3schools.com/html/default.asp),
[JavaScript](https://www.w3schools.com/js/default.asp),
[Electron](https://www.electronjs.org)


## Usage
1. Install Electron.js
    ``npm i -D electron@latest``
2. cd to this folder.
3. `npm start`
