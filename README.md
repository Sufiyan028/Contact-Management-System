A Contact Management App with Charts and Maps of Covid Cases all over the World.
Task Assigned by Taiyo.Ai
Create a Contact Management app with Charts and Maps using ReactJS, TypeScript, TailwindCSS, React Router v6 and React Query aka TanstackQuery
Create a GitHub/GitLab repo and possibly deploy your app on free services like Vercel, Github Pages or Heroku etc
Objectives of Contact Page
The app should have a form for adding new contacts.
The app should display a list of all added contacts
Each contact should have a button to view the contacts details
The app should be able to edit and delete contacts
Make use of Redux to store the contact data
Objectives of Charts and Maps Page
Build a simple dashboard with:
- A line graph showing the cases fluctuations
- A react leaflet map with markers that indicates the country name, total number of active, recovered cases and deaths in that particular country as a popup
APIs Used
World wide data of cases: https://disease.sh/v3/covid-19/all
Country Specific data of cases: https://disease.sh/v3/covid-19/countries
Graph data for cases with date: https://disease.sh/v3/covid-19/historical/all?lastdays=all
Technologies Used
ReactJs
TypeScript
TailwindCSS
React Router v6
React Query
Redux
Development Installation
Follow these instructions to set up your development environment, which you need to do before you start contributing code to this project.

Manual Installation
Note: The installation steps assume you are using a Unix-like shell. If you are using Windows, you will need to use copy instead of cp.

Install Node.js. The recommended way is to Node through nvm. You can also install node.js version 18.2.0 directly from the Node.js website.

Clone your new fork of the repository from GitHub onto your local computer.

$ git clone https://github.com/aayanlobo/CovidConnectPlus.git
Navigate to root directory and implement the following commands :

$ cd CovidConnectPlus
$ npm install
$ npm run start
