# Notetaker
* generated readme from readme generator 
# Table of Contents

* [Description](#description)
* [URL](#url)
* [User Story](#user%story)
* [Contributing](#contributing)
* [Test](#test)
* [Questions](#questions)

# Description:
App allows users to write, save, and delete notes. Uses express backend with save and retrieve note data from a JSON file.

* Application HTML routes:

* The following HTML routes should be created:

  * GET `/notes` - Should return the `notes.html` file.

  * GET `*` - Should return the `index.html` file

* The application has a `db.json` file on the backend that will be used to store and retrieve notes using the `fs` module.

* API routes for application:

  * GET `/api/notes` - Should read the `db.json` file and return all saved notes as JSON.

  * POST `/api/notes` - Should receive a new note to save on the request body, add it to the `db.json` file, and then return the new note to the client.

  * DELETE `/api/notes/:id` - Should receive a query parameter containing the id of a note to delete. This means you'll need to find a way to give each note a unique `id` when it's saved. In order to delete a note, you'll need to read all notes from the `db.json` file, remove the note with the given `id` property, and then rewrite the notes to the `db.json` file.

# URL:
https://guarded-ravine-93517.herokuapp.com/

# User Story:
AS A user, I want to be able to write and save notes

I WANT to be able to delete notes I've written before

SO THAT I can organize my thoughts and keep track of tasks I need to complete

# Business Context:
For users that need to keep track of a lot of information, it's easy to forget or be unable to recall something important. Being able to take persistent notes allows users to have written information available when needed.

# Usage:
for anyone needning to take notes and review those notes in the future.

# Contributing:
contact Shawn Morgan

# Test:
Once installed, issue 'npm run test' in terminal

# Questions:
Please visit my github page or e-mail me directly to contact me about this project
* [Shawn-Morgan](https://github.com/Shawn-Morgan)
* <shawnm74@gmail.com>