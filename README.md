# Mini Project: Dynamic Data Display

This is a mini project that demonstrates how to use the Axios library to retrieve data from a JSON server and dynamically display it on a web page. 
The project consists of HTML, JavaScript, and a sample JSON database.

## Prerequisites

Ensure you have a JSON server installed. You can use `json-server` or a similar tool to serve the `db.json` file. You can start the JSON server by running the following command:
npx json-server db.json

### Project Components

#### JSON Database

The `db.json` file serves as a simulated database with a list of people. Each person in the database has attributes such as name, surname, sex, age, and a URL to their photo.

#### JavaScript

The `script.js` file contains JavaScript code that listens for a button click. When the button is clicked, it asynchronously fetches data from the JSON server using the Axios, 
processes the data, and dynamically creates HTML elements to display each person's information on the web page.

## Usage

1. Clone or download this repository to your local machine.
2. Start the JSON server using `npx json-server db.json`.
3. Open the `index.html` file in a web browser or use a development environment like Live Server to run the project.
4. Click the "Click" button, and the information of the people from the JSON database will be fetched and displayed on the web page.
