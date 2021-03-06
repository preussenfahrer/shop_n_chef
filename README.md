# Shop & Chef
Project #2

Team 1

 + [Nate King](https://github.com/natemking)
 + [Luke Martin](https://github.com/LukeMartin-123)
 + [Greg Leighton](https://github.com/preussenfahrer)
 + [Meredith Jones](https://github.com/meredithajones)  
---

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://github.com/natemking/shop_n_chef/blob/main/LICENSE)

![html5 badge](https://img.shields.io/badge/html5%20-%23E34F26.svg?&style=flat&logo=html5&logoColor=white)
![css3 badge](https://img.shields.io/badge/css3%20-%231572B6.svg?&style=flat&logo=css3&logoColor=white)
![node.js badge](https://img.shields.io/badge/node.js%20-%2343853D.svg?&style=flat&logo=node.js&logoColor=white)
![express badge](https://img.shields.io/badge/express.js%20-%23404d59.svg?&style=flat)
![ejs badge](https://img.shields.io/badge/%20EJS%20-%23B4CA65.svg?&style=flatColor=white%22/)
![sequelize badge](https://img.shields.io/badge/Sequelize-%2304AFEF.svg?&style=flat&logoColor=white)
![heroku badge](https://img.shields.io/badge/heroku%20-%23430098.svg?&style=flat&logo=heroku&logoColor=white)
![bootstrap badge](https://img.shields.io/badge/bootstrap%20-%23563D7C.svg?&style=flat&logo=bootstrap&logoColor=white)

---
## Table of Contents
 - [Links](#links)
 - [Introduction](#introduction)
    + [Description/User Story](#description/user-story)
    + [Scope of Work](#scope-of-work)
 * [Usage/Installation](#usage/installation)
    + [Running the Application](#running-the-application)
    + [Sequelize](#sequelize)
    + [Node.js](#nodejs)
    + [EJS View Engine](#ejs-view-engine)
    + [jQuery](#jquery)
    + [Axios](#axios)
    + [AJAX](#ajax)
    + [CSS](#css)
  * [Screenshots](#screenshots)
  * [Areas for Future App Development](#future-development)
  * [License](#license)
  * [Credits](#credits)

# Links

* [Deployed Link](https://shop-n-chef.herokuapp.com/)

# Introduction
  Shop & Chef is a disposable grocery list application. 

   This application is designed for those who are experienced home chefs, or newcomers to home cooking, combining food shopping with new, exciting, and inspiring recipe suggestions. 

### Description/User Story 
  AS A USER I want an app that will allow me to link my grocery list with potential recipes

  WHEN I use Shop & Chef 
  THEN I will enter my log-in credentials

  WHEN I successfully log-in
  THEN I get a shopping list

  WHEN I add an item to the item list input
  THEN I can save the ITEM

  WHEN I save an item
  THEN I can edit, delete, or cross-off an item

  WHEN I search for a recipe or ingredient 
  THEN I am presented with a list of recipe choices
  
  WHEN I chose a recipe
  THEN it's picture, ingredients, & instructions will appear

  WHEN I click on an ingredient
  THEN it will be saved to my shopping list and checked off on this list

  WHEN I click the favorite button
  THEN the current displayed recipe will be saved to my saved recipe list

  WHEN I input an ingredient
  THEN it will be added to a list

  WHEN I select a specific ingredient on my list
  THEN I am prompted with potential recipes to use this ingredient

  WHEN I have a recipe I like
  THEN I can save this to a list of favorite recipes

  WHEN I return to the site
  THEN I can access all of my items and recipes


### Scope of Work
Users can easily add items of their choosing to their shopping list. If they are looking for recipe inspiration, the app has a feature to search for recipes based on the main ingredient as well. 

To streamline the experience of creating a shopping list based on recipes, Shop & Chef allows users to add ingredients directly from recipes to their shopping list with a click on the ingredient. 

The application also allows users to save and retrieve their favorite recipes. 

## Usage/Installation
### Running the application: 
  In the terminal, run the following commands:
* `npm install express`
* `npm install express-session`
* `npm install --save sequelize`
* `npm install passport`
* `npm install ejs`
* After completing your installations, begin the server in your integrated terminal by running the command: `node server.js`

If the connection is successful, you will see: 

`🌎  Listening on port %s. Visit http://localhost:%s/ in your browser`

### Sequelize
  Sequelize is a promise-based Node.js ORM which we utilized to streamline usage with MySQL. 

  Installation:

`npm install --save sequelize`

### Node.js

Express is the application that we utilized the most through node.js. The servers that we created route to the HTML data and the other to API for the data. 
We are running the GET, POST, PUT, & DELETE methods for the data. We render the necessary data to the front end using EJS.
We also used Passport node js middleware for user authentication.
Passport Installation: 
`npm i passport` 

### EJS View Engine
We use EJS Templating Engine to render our data as HTML Markup to be viewed on the front end. Through using EJS to create templates for our pages we were able to eliminate redundant code and create more streamlined, dry code for the application.  
Installation
` npm install ejs`
 
### jQuery
We use jQuery to handle event listeners and AJAX calls to the backend. Our AJAX calls were responsible for our functions carrying data from user logins, sign ups, recipe retrieval and display. 

### Axios
We utilized Axios to handle all of our third party API are done with Axios to keep them hidden. 

### AJAX
We used AJAX for all of our front end API calls. 

### CSS
Our styling was created using Bootstrap for our navbar, buttons and user input fields. We used Bootswatch for our theme, and quite a bit of custom css written for placing the background image, font styling, custom color schemes and other fine tuning of the application's appearance. Included in our custom css styling is a google font to style all of the text in our application. 

## Screenshots 
  ### Gifs


<br>

 _App Functionality: Create New Account (gif demo)_
<br>
![Creating new user account in app](public/assets/imgs/gifs/s_c_1.gif)

<br>

 _App Functionality: Adding, crossing off as purchased, and deleting items from shopping list (gif demo)_
<br>
![Using the shopping list section of the application to add items, cross them off once procured, or delete individually](public/assets/imgs/gifs/s_c_2.gif)

<br>

<br>

 _App Functionality: Searching for a recipe and adding ingredients to the shopping list (gif demo)_
<br>
![A gif demonstrating searching for a recipe and adding ingredients to the shopping list (gif demo](public/assets/imgs/gifs/s_c_3.gif)

<br>

_App Functionality: Saving favorite recipes (gif demo)_
<br>
![A gif demonstrating saving favorite recipes](public/assets/imgs/gifs/s_c_4.gif)

<br>

## Future Development
We have several ideas for ways to expand and enhance the application in the future:

* Adding the ability to share your shopping list easily through email or with other users of the app.
* Adding a feature also provided through our API for the app to suggest wine pairings with our recipes. 
* Adding a feature to show calories associated with recipes.
* A "Frequently Shopped Items" database. 
* The ability to display estimated cost for each item on a user's shopping list, along with an estimate for the total cost of the list's contents at the bottom. 

## License
Licensed under the MIT License. Copyright © 2021

## Credits

* [Spoontacular API for all recipes](https://spoonacular.com/food-api)

* [Importing and exporting ES6 modules](https://www.digitalocean.com/community/tutorials/js-modules-es6)

* [Using an AJAX call inside and async/await](https://petetasker.com/using-async-await-jquerys-ajax)  

* [NoobCoder YouTube Tutorial NodeJS For Beginners: Getting Started With EJS Templates With Express](https://www.youtube.com/watch?v=VM-2xSaDxJc) 

* [EJS Template methods](https://ejs.co/)

* [EJS Formatting reference](https://github.com/mde/ejs)

* [Badges for Readme](https://github.com/Ileriayo/markdown-badges) 

* [Google Fonts for customization](https://fonts.google.com/)
