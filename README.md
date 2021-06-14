[![Netlify Status](https://api.netlify.com/api/v1/badges/0fd1425b-cf4d-4784-a1de-16f485ceefaa/deploy-status)](https://app.netlify.com/sites/minith-myreads/deploys)

# MyReads Project

Bookshelf app that allows you to select and categorise books you have read, are currently reading, or want to read.

The project emphasises using React to build the application and provides an API server and client library that you will use to persist information as you interact with the application.

App link: https://minith-myreads.netlify.app/

## Getting Started

- Fork or directly clone this repository to your local machine
- In the project folder, use the `yarn` command to install dependencies
- Once the dependencies are finished installing, use the `yarn start` command to open the app in your local browser of choice
- In case you don't have `yarn` installed
    - instead of `yarn` use `npm install`
    - instead of `yarn start` use `npm start`

## App Functionality

### Main Page
The main page will show a list of shelves which contain a number of books.
The shelves are:
- Currently Reading
- Want to Read
- Read

Each book has a control which allows the user to change it between shelves.

### Search Page
The search page has a text input that may be used to find books. The books will be filtered as the user introduces characters.

Once filtered the user may manage each book, adjusting the shelve where it should go.
