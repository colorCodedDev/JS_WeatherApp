# Weathery - A Project For AnnieCannons' Returning Students

Weathery is a project for returning students to AnnieCannons. The finished app allows users to search for locations and get the matching weather forecasts.

## Goal
demonstrate skills in:

- manipulating a user interface with the vanilla JS DOM API
- making API calls with `fetch`
- laying out a user interface with CSS Grid and CSS Flexbox

The code should:

- Use vanilla JS DOM manipulation and no other UI framework.
- Use `fetch` for an API call to the Weather API.
- Use CSS Grid to lay out the overall interface.
- Use CSS Flexbox to lay out at least one individual section.

## Rubric

#### Functionality

The app meets all of the following user stories:

- The user can enter a city name in an input box and press a submit button to see the following information for the searched city:
  - the name of the city
  - the country for the city
  - the current temperature
  - the high temperature
  - the low temperature
  - the chance of precipitation
  - the high, low, and chance of precipitation for each of the following 2 days
- The app have the following conditional features:
  - The app will display "It's Hot Today!" if it is above 75 degrees.
  - The app will display "It's Moderate Today!" if it is between 45 - 74 degrees.
  - The app will display "It's Cold Today!" if it is below 45 degrees.

###### Extra Functionality 

These are _not_ a requirement, but are given so that you have a way to push yourself and practice more should you want to do so.

- Add a background image or emojis to represent the current weather.
- Add a drop-down for the user to choose Celsius or Fahrenheit temperatures, updating the display to match.


#### User Interface Design

The app should:

- Have an intuitive and easy-to-use interface.
- Be responsive to different screen sizes.
- Have an input box for users to type their searches in with a submit button.
- Please refer to the wireframe [here](https://www.figma.com/file/9C3tbvQrT2EmKElg6ySJEF/Weathery-Website?type=design&node-id=0-1&mode=design).

## A Note On Using The API

Here is the link to sign up for the API service. This is free, but you will need to sign up to get an API Key: https://www.weatherapi.com/signup.aspx
Here is the documentation: https://www.weatherapi.com/docs/
Here is a sample API call: http://api.weatherapi.com/v1/current.json?key="YOUR_API_KEY"&q=London

## Getting Started

1. Fork this repository.
2. Clone your forked repository.
3. Create an HTML file named `index.html`.
4. Link your CSS file using a `link` tag in your HTML file.
5. Link your JavaScript file using a `script` tag in your HTML file.

## Suggested Tools

We suggest using Visual Studio Code as your editor. You can download it here: https://code.visualstudio.com/download

We also suggest using Visual Studio Code's Live Server extension to render your project in the browser. You can download it here: https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer

# JS_WeatherApp
