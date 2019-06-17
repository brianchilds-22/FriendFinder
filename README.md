# FriendFinder
## How to use the app
Click the go to survey button on the Friend Finder home page.

![Friend Finder Home](https://github.com/brianchilds-22/FriendFinder/blob/master/images/screencapture-obscure-spire-48595-herokuapp-2019-06-16-20_13_38.png?raw=true) 

On the survey page the client enters their name and a link to an image. Then they answer the questions by selecting one of five options.

![Friend Finder Survey](https://github.com/brianchilds-22/FriendFinder/blob/master/images/Screenshot%20(6).png?raw=true)

Upon completion the app calculates the best match

![Friend Finder Match](https://github.com/brianchilds-22/FriendFinder/blob/master/images/Screenshot%20(7).png?raw=true)


[Heroku Link] (https://obscure-spire-48595.herokuapp.com/)

## The Process
   (steps taken to build files)

### server.js
* require node modules and install in terminal
* create server port
* then npm init for package json
* npm install express, path
* api routes included

### home.html
* build home page with Bootstrap - Jumbotron
* link to survey page with button
* footer links to friends api

### survey.html 
* create 10 questions and 5 options and ids for verify.
* require html routes
* create submit button to open Modal
* create modal to show match
* form validation after user submit

### html-routes.js
* include path package
* build routes deliver based on url with modules.exp

### friends.js
* create friends array for data.
* module.exports

### API routes
* require friends.js data
* build rout to view friends
* include in server file
* compare friends and scores to determine match
* push data into friend array
* make JSON and display



