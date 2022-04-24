# Note_Taker


An application that can be used to write, save, and delete notes. This application uses a express, and saves and retrieves note data from a JSON file.

## Badges

Code quality and validation

[![Language grade: JavaScript](https://img.shields.io/lgtm/grade/javascript/g/TBM97/Note_Taker.svg?logo=lgtm&logoWidth=18)](https://lgtm.com/projects/g/TBM97/TeamProfileGen/context:javascript)
![shields.io](https://img.shields.io/github/languages/top/TBM97/Note_Taker)
![shields.io](https://img.shields.io/w3c-validation/html?targetUrl=https%3A%2F%TBM97.github.io%2FNote_Taker%2F)

Repository Status

![shields.io](https://img.shields.io/badge/Repo%20Status-In%20Progress-yellow)
![shields.io](https://img.shields.io/bitbucket/issues/TBM97/Note_Taker)

License

![GitHub](https://img.shields.io/github/license/TBM97/Note_Taker)

## Table of contents

- [Title](#title)
  - [Badges](#badges)
  - [Table of contents](#table-of-contents)
  - [The challenge](#the-challenge)
  - [The development process](#the-development-process)
  - [The Output](#the-output)
  - [Installation and Usage](#installation-and-usage)
  - [Credits, tools and other references](#credits-tools-and-other-references)
  - [Contributing](#contributing)
  - [Questions](#questions)

## The challenge

Main elements:Write, save, and delete notes

 The application should have a db.json file on the backend

 The following API routes should be created:

 - [x] GET /api/notes - Should read the db.json file and return all saved notes as JSON.

 - [x] POST /api/notes - Should receive a new note to save on the request body, add it to the db.json file, and then return the new note to the client.

 - [x] DELETE /api/notes/:id - Should receive a query parameter containing the id of a note to delete. This means you'll need to find a way to give each note a unique id when it's saved. In order to delete a note, you'll need to read all notes from the db.json file, remove the note with the given id property, and then rewrite the notes to the db.json file.




## The development process


In order to accomplish the challenge, the following steps were done:

Understand the purpose, concept and frontend functionality of the application.
Research assets.
Include dependencies.
Develop and test HTML and API routes.
Link frontend with the backend.
Final review and proper documentation.

## The Output


With the described process we were able to create a useful, efficient and responsive application that promts user information from the CLI and creates an HTML file with team's profiles.

**User stories**

1.As a user, I can write and save notes, so that I can organize my thoughts and keep track of tasks I need to complete.
2.As a user I can delete notes I have wirtten before, so that I can keep my notes updated.

**The application**

![screenshot1](./images/screenshot1.png)
![screenshot2](./images/screenshot2.png)
![screenshot3](./images/screenshot3.png)




## Installation and Usage

The project was uploaded to [GitHub](https://github.com/) at the following repository:
[https://github.com/TBM97/Note_Taker](https://github.com/TBM97/Note_Taker)

You can access the deployed application with the Herkou link:
[https://fierce-earth-57501.herokuapp.com/](https://fierce-earth-57501.herokuapp.com/)


To install the project follow these steps:

Clone the application from GitHub with: git clone [clone link from GitHub]
From the root folder, install the dependencies with: npm install
Run the app with: node server.js



## Credits, tools and other references

**Third Party Assets**

[Bootstrap](https://getbootstrap.com/)




## Contributing

- Pull requests are welcome.
- For major changes, please open an issue first to discuss what you would like to change.
- Please make sure to update tests as appropriate.

## Questions

If you have questions or you want to share comments, we will be glad to hear from you. Please contact me at masonurrabas@gmail.com.


