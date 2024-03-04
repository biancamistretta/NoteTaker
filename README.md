# NoteTaker

This is a simple note-taking application built with Node.js and Express.js. It allows users to create, read, update, and delete notes.

## Features

- View existing notes
- Add new notes
- Delete existing notes

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/yourusername/note-taking-app.git
Navigate to the project directory:

bash
Copy code
cd note-taking-app
Install dependencies:

bash
Copy code
npm install
Start the server:

bash
Copy code
npm start
The server should now be running on http://localhost:3000.

Usage
Viewing Notes
Navigate to http://localhost:3000/notes in your web browser to view existing notes.
Adding Notes
Click on the "New Note" button or navigate to http://localhost:3000/notes/new to add a new note.
Enter the title and content of the note, then click "Save".
Deleting Notes
To delete a note, click on the delete button next to the note in the list.
API Endpoints
GET /api/notes: Get all saved notes.
POST /api/notes: Create a new note.

Dependencies
Express.js: Fast, unopinionated, minimalist web framework for Node.js.
fs: File system module for Node.js.

License
This project is licensed under the MIT License - see the LICENSE file for details.






