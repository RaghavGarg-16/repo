# <Xenon❤️Raghav> (Delployment Link)

## Description

It is a user-friendly web application designed to help both instructors and learners connect in a seamless educational environment. With a clean and intuitive interface, Learnify offers a straightforward platform for instructors to showcase their courses and for learners to discover and enroll in their preferred subjects.

## Technologies Used

### Frontend:

- React.js
- CSS for styling
  
### Backend:

- Node.js
- Express.js
- MongoDB

### Additional Libraries:

- Axios for HTTP requests
- React Router for client-side routing

- What was your motivation?
- Why did you build this project? (Note: the answer is not "Because it was a homework assignment.")
- What problem does it solve?
- What did you learn?

## Table of Contents

- [File Structure](#file-structure)
- [Installation](#installation)
- [Usage](#usage)
- [Features](#features)
- [Deployment](#deployment)
- [License](#license)

## File structure
- client - Holds the client application
- public - This holds all of our static files
- src
- assets - This folder holds assets such as images, docs, and fonts
- components - This folder holds all of the different components that will make up our views
- views - These represent a unique page on the website i.e. Home or About. These are still normal react components.
- App.js - This is what renders all of our browser routes and different views
- index.js - This is what renders the react app by rendering App.js, should not change
- package.json - Defines npm behaviors and packages for the client
- server - Holds the server application
- config - This holds our configuration files, like mongoDB uri
- controllers - These hold all of the callback functions that each route will call
- models - This holds all of our data models
- routes - This holds all of our HTTP to URL path associations for each unique url
- tests - This holds all of our server tests that we have defined
- server.js - Defines npm behaviors and packages for the client
- package.json - Defines npm behaviors like the scripts defined in the next section of the README
- .gitignore - Tells git which files to ignore
- README - This file!

## Installation

What are the steps required to install your project? Provide a step-by-step description of how to get the development environment running.

## Usage

- Create an account or log in as a learner.
- Browse the course catalog and enroll in courses of interest.
- 
Provide instructions and examples for use. Include screenshots as needed.

To add a screenshot, create an `assets/images` folder in your repository and upload your screenshot to it. Then, using the relative filepath, add it to your README using the following syntax:

    ```md
    ![alt text](assets/images/screenshot.png)
    ```
## Features

### 1. User Authentication and Registration:

- User accounts with unique usernames and passwords.
- Options for users to register using email, social media accounts, or other authentication methods.

### 2. Course Catalog:

- A searchable and categorized list of available courses presented with clear titles, descriptions, and instructor details.
- Filter options for sorting by subject, level, duration, etc.
- Engage with comprehensive course overviews, including curriculum, prerequisites, and user reviews

### 3. Content Recommendations:

- Personalized course recommendations based on user preferences, browsing history, and behavior.

### 4. Admin Dashboard:

- Backend interface for administrators to manage users, courses, content, and settings.

## Deployment

## License

This project is licensed under the [MIT License](#mit-license).
