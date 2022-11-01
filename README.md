# MERN GraphQL Book App

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://choosealicense.com/licenses/mit/)

## Description
An app that allows a user to search, save, and remove from a favorites list to purchase.

## Table of Contents
  - [Usage](#usage)
  - [User Story](#userstory)  
  - [Tests](#tests)
  - [Installation](#installation)
  - [Screenshots and Video](#screenshots)
  - [Contributing](#contributing)
  - [Questions](#questions)
  - [License](#license)
      


## Usage
Using MERN stack and GraphQL, users query books and add/remove from list. The book list persists on the server-side with user login authentication, so they can come back at a later time to continue editing their list. 

## UserStory
  AS AN avid reader
  I WANT to search for new books to read
  SO THAT I can keep a list of books to purchase

  GIVEN a book search engine
  WHEN I load the search engine
  THEN I am presented with a menu with the options Search for Books and Login/Signup and an input field to search for books and a submit button
  WHEN I click on the Search for Books menu option
  THEN I am presented with an input field to search for books and a submit button
  WHEN I am not logged in and enter a search term in the input field and click the submit button
  THEN I am presented with several search results, each featuring a book’s title, author, description, image, and a link to that book on the Google Books site
  WHEN I click on the Login/Signup menu option
  THEN a modal appears on the screen with a toggle between the option to log in or sign up
  WHEN the toggle is set to Signup
  THEN I am presented with three inputs for a username, an email address, and a password, and a signup button
  WHEN the toggle is set to Login
  THEN I am presented with two inputs for an email address and a password and login button
  WHEN I enter a valid email address and create a password and click on the signup button
  THEN my user account is created and I am logged in to the site
  WHEN I enter my account’s email address and password and click on the login button
  THEN I the modal closes and I am logged in to the site
  WHEN I am logged in to the site
  THEN the menu options change to Search for Books, an option to see my saved books, and Logout
  WHEN I am logged in and enter a search term in the input field and click the submit button
  THEN I am presented with several search results, each featuring a book’s title, author, description, image, and a link to that book on the Google Books site and a button to save a book to my account
  WHEN I click on the Save button on a book
  THEN that book’s information is saved to my account
  WHEN I click on the option to see my saved books
  THEN I am presented with all of the books I have saved to my account, each featuring the book’s title, author, description, image, and a link to that book on the Google Books site and a button to remove a book from my account
  WHEN I click on the Remove button on a book
  THEN that book is deleted from my saved books list
  WHEN I click on the Logout button
  THEN I am logged out of the site and presented with a menu with the options Search for Books and Login/Signup and an input field to search for books and a submit button




## Tests
Apollo for query and mutation testing



## Installation
Set up in Server-Client Model. package.json "main": "server/server.js", "scripts": { "start": "node/server.js", "develop": "concurrently \"cd server && npm run watch\" \"cd client && npm start\"", "install": "cd server && npm i && cd ../client && npm i", "build": "cd client && npm run build"


## Screenshots

![Alt Text](./images/screenshot.png)



## Questions

Have questions?
You can find me on GitHub:
https://github.com/BeKind-Rewind

Or email me at:
challenge641@gmail.com


## License

Licensed under the [MIT](https://choosealicense.com/licenses/mit/) license.
    