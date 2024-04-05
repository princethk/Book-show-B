# Book my show..
Book My Show is a web application that allows users to book movie tickets. It provides a user-friendly interface for selecting movies, slots, and seat types, and facilitates the booking process with a simple and intuitive design.

## Features
Display a list of available movies, slots, and seat types.
Select movies and slots by clicking on the respective div containing the data.
Set the number of seats for each seat type by typing into the corresponding input field.
Update the class names of the selected divs to indicate the selection.
Make a booking with a single POST request upon clicking the submit button.
Display last booking details, including the movie name, slot, and ticket types, in a separate section.
Use localStorage to store temporary user selections to maintain state across reloads.

## Link to website -> [BookMyShow](https://book-my-showf.netlify.app/)


## Technologies that are used.

- #### React  
    This app is fully built on top of react library.
- #### Axios / Fetch
    Used for making api calls.

## Installation
# To run the application locally, follow these steps:
## Clone this repository: git clone https://github.com/princethk/Book-Show-F.git
## Navigate to the project directory: cd Book-Show-F
## Install dependencies: npm install 
## Start the development server: npm start
The application will be running at http://localhost:3000

## The documentation for the backend - [Documentation](https://github.com/princethk/Book-show-B)

# Bookmyshow - Backend

This backend it built on top of Node.js where the user data is being stored and retrived flexibly from MongoDB and shown on the UI.

## Link to website -> [BookMyShow](https://book-my-showf.netlify.app/)

## Database Server
## Connection
To connect to the database server, use the provided connection.js file. This file contains the code to establish a connection with the localhost server.

## Data Schema
Store your data according to the schema provided in Schema.js. Ensure that your database follows this schema for consistent data storage.
## Technologies used
- Express.- The backend server is built using Express and listens on port 8080.
   
  To Create Server.
- MongoDB.

    To store and retrive the data of the user.


### End points
1. `Post` [url](https://bookmyshow-backend-main.onrender.com/api/booking) 

   This is a post request endpoint which is used to store the booking details of the user.

2. `Get` [url](https://bookmyshow-backend-main.onrender.com/api/booking)

   This is a get request endpoint which is used to get the last booking deatils of user.

#### Contributions are always welcome!
Contributions are welcome! If you find any bugs or have suggestions for improvements, please open an issue or submit a pull request.


Thank You !

