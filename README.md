# Node CRUD DB CLI App


A CLI app created with Node.js that allows the user to run CRUD functions on a db.json file, and if it doesn't exist, creates the database file using the `fs` module of Node.js. The example used for this specific application asks for the users name, phone number, and if they are an adult and generates a random `uuid` and stores it in the database. You can then update the entry with the id number, retrieve all entries, or delete the entry using the id number.

This app was planned using the `README.md` and created entirely in the terminal using the Vim Editor. I plan on creating a video tutorial showing developers how to create this application entirely in the terminal, using the README project planning method, and how to run the app and store data that you want entirely from the command line interface. 

This project was fun and is a great practice in creating CLI applications, using Node.js, and a great practice in using the VIM editor. It also provided practice in planning an application using the `README.md` file and creating it from the command line interface.

## File Structure

Here is the file structure and what each file does in the app:

- `addData.js`: adds data to the database. It also fabricates the database file if it doesn't exist.
- `removeData.js`: removes selected data
- `retrieveData.js`: fetches all data
- `updateData.js`: edits data
- `queryDB.js`: checks if a database exists and executes a function passed to it- `dbFileCheck.js`: confirms if the database file has been created

## To Do

- [x] Initialize project with NPM
- [x] Create necessary files
- [x] Plan project with `README.md`
- [x] Check if a database exists
- [x] Function to retrieve data from a database
- [x] Add new data to the database
- [x] Update database with new data
- [x] Remove data form the database
- [x] Push to GitHub and publish repository
- [ ] Create a YouTube tutorial for a similar application

## Resources

- [Node.js File System - fs](https://nodejs.org/api/fs.html)
- [Inquirer NPM Documentation](https://www.npmjs.com/package/inquirer)
- [MDN `async` Function Docs](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/async_function)
- [MDN `try...catch` Docs](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/try...catch)
- [uuid NPM Documentation](https://www.npmjs.com/package/uuid)

