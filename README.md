# 📲 Taiyoo Application Developed by Akhilesh

Welcome to our Contact Management Application, a robust frontend solution designed to streamline your contact organization. With this app, users can effortlessly create, view, edit, and delete contacts.

Additionally, the application features a dedicated Charts and Maps section, providing insightful visualizations of COVID-19 case trends from January 22, 2020, to March 9, 2023.

Our app also includes a comprehensive landing page that serves as your gateway to the contact management features and the interactive charts and maps.


# 🤩 Main Features of this Contacts Page :-

The application should feature a form for creating new contacts.
The application should present a list of all the contacts that have been added.
Each contact should include a button to view its detailed information.
The application should support the ability to modify and remove contacts.
Implement Redux to manage the contact data storage.

###Snapshots of Application :-
## Contact Page 
<img width="919" alt="Screenshot 2024-05-27 125425" src="https://github.com/AkhilWarke/Taiyoo_Akhilesh/assets/139999018/29ad0480-a5c6-4b66-b995-f178e70720fa">

## Charts and Maps 
<img width="914" alt="S2" src="https://github.com/AkhilWarke/Taiyoo_Akhilesh/assets/139999018/ded64775-08b9-407a-a7de-efbb02b314dc">
 


### Objectives for Charts and Maps Page

- The app should have a form for adding new contacts
- The app should display a list of all added contacts
- Each contact should have a button to view the contacts details
- The app should be able to edit and delete contacts
- Make use of Redux to store the contact data

### API Information

The `api` which will contain the API layer of the application. It will have methods that are responsible for performing API request and communicating with an external server. The output file for this folder is the `index.ts` file, which is responsible for exposing all the endpoints to be used by other modules. This project uses `axios` and `react query` as it's base tool for implementing the api layer.

The APIs used in this application include


Endpoints

1.  GET /countries

- Description: Retrieves the list of covid-19 cases by country
- Response Format: JSON
- Example Response:
  ```[{
  "updated": 1690544438268,
  "country": "Afghanistan",
  "countryInfo": {
  "_id": 4,
  "iso2": "AF",
  "iso3": "AFG",
  "lat": 33,
  "long": 65,
  "flag": https://disease.sh/assets/img/flags/af.png
  },
  "cases": 224135,
  "todayCases": 0,
  "deaths": 7939,
  "todayDeaths": 0,
  "recovered": 204028,
  "todayRecovered": 0,
  "active": 12168,
  "critical": 45,
  "casesPerOneMillion": 5500,
  "deathsPerOneMillion": 195,
  "tests": 1282999,
  "testsPerOneMillion": 31481,
  "population": 40754388,
  "continent": "Asia",
  "oneCasePerPeople": 182,
  "oneDeathPerPeople": 5133,
  "oneTestPerPeople": 32,
  "activePerOneMillion": 298.57,
  "recoveredPerOneMillion": 5006.28,
  "criticalPerOneMillion": 1.1
  },
  {
  "updated": 1690544438254,
  "country": "Albania",
  "countryInfo": {
  "_id": 8,
  "iso2": "AL",
  "iso3": "ALB",
  "lat": 41,
  "long": 20,
  "flag": https://disease.sh/assets/img/flags/al.png
  },
  "cases": 334726,
  "todayCases": 0,
  "deaths": 3602,
  "todayDeaths": 0,
  "recovered": 329428,
  "todayRecovered": 0,
  "active": 1696,
  "critical": 0,
  "casesPerOneMillion": 116777,
  "deathsPerOneMillion": 1257,
  "tests": 1941032,
  "testsPerOneMillion": 677173,
  "population": 2866374,
  "continent": "Europe",
  "oneCasePerPeople": 9,
  "oneDeathPerPeople": 796,
  "oneTestPerPeople": 1,
  "activePerOneMillion": 591.69,
  "recoveredPerOneMillion": 114928.48,
  "criticalPerOneMillion": 0
  }]
  ```

2.  GET /historical/all?lastdays=all

- Description: Retrieves the list of historical covid-19 cases by date
- Response Format: JSON
- Example Response:

```"cases": {
"1/22/20": 557,
"1/23/20": 657,
"1/24/20": 944,
"1/25/20": 1437,
"1/26/20": 2120,
"1/27/20": 2929,
"1/28/20": 5580,
"1/29/20": 6169,
"1/30/20": 8237,
"1/31/20": 9927,
"2/1/20": 12038,
"2/2/20": 16787,
"2/3/20": 19887,
"2/4/20": 23899,
"2/5/20": 27644,
"2/6/20": 30806,
"2/7/20": 34400,
```

2.  GET /historical/all?lastdays=all

- Description: Retrieves the list of historical covid-19 cases by date
- Response Format: JSON
- Example Response:

```"cases": {
"1/22/20": 557,
"1/23/20": 657,
"1/24/20": 944,
"1/25/20": 1437,
"1/26/20": 2120,
"1/27/20": 2929,
"1/28/20": 5580,
"1/29/20": 6169,
"1/30/20": 8237,
"1/31/20": 9927,
"2/1/20": 12038,
"2/2/20": 16787,
"2/3/20": 19887,
"2/4/20": 23899,
"2/5/20": 27644,
"2/6/20": 30806,
"2/7/20": 34400,
```

### How to run the app

Below are the instructions on how to set up and run the application locally

#### Prerequisites

Before running the application, make sure you have the following installed on your computer

1.  Node.js and npm (Node Package Manager): You can download and install Node.js from the official website here. https://nodejs.org/en/download

#### Getting Started

1.  Clone the repositiory to your local machine
    `https://github.com/PromiseUdo/contact-mgmt-app.git`
2.  Navigate to the project directory
    `cd contact-mgmt-app`
3.  Install the required dependencies
    `npm install`

### Running the application

To run the application in development mode, use the following command
`npm start`
This command will start the development server and open the application in your default web browser at http://localhost:3000. Any changes you make to the code will be automatically hot-reloaded in the browser.

### Building the Application

To build the application for production, use the following command:
`npm run build`

### Deployment

To deploy the application to a web server, you can use platforms like Netlify, Vercel, GitHub Pages, or any hosting service of your choice. Simply upload the contents of the build directory to your hosting server.

### I hope you enjoy reading this, for any contribution and comments on this, kindly make a pull request!
