NodeJS Basics
This project contains tasks for learning to the basics of NodeJS.

Tasks To Complete
 0. Executing basic javascript with Node JS
0-console.js contains a module that exports a function named displayMessage that prints in STDOUT the string argument.

 1. Using Process stdin
1-stdin.js contains a script that will be executed through the command line with the following requirements:

It should display the message Welcome to Holberton School, what is your name? (followed by a new line).

 2. Reading a file synchronously with Node JS
2-read_file.js contains a module that exports a function countStudents with the following requirements:

Create a function named countStudents. It should accept a path in argument.
The script should attempt to read the database file synchronously.

 3. Reading a file asynchronously with Node JS
3-read_file_async.js contains a module that exports a function countStudents with the following requirements:

Create a function named countStudents. It should accept a path in argument (same as in 2-read_file.js).
The script should attempt to read the database file asynchronously.

 4. Create a small HTTP server using Node's HTTP module
4-http.js contains a script that creates and exports a small HTTP server using the http module with the following requirements:

It should be assigned to the variable app, which must be exported.

 5. Create a more complex HTTP server using Node's HTTP module
5-http.js contains a script that creates and exports a small HTTP server using the http module with the following requirements:

It should be assigned to the variable app, which must be exported.

 6. Create a small HTTP server using Express
6-http_express.js contains a script that creates and exports a small HTTP server using the Express module with the following requirements:

It should be assigned to the variable app, which must be exported.

 7. Create a more complex HTTP server using Express
7-http_express.js contains a script creates and exports a small HTTP server using the Express module with the following requirements:

It should be assigned to the variable app, which must be exported.

 8. Organize a complex HTTP server using Express
Writing every part of a server within a single file is not sustainable. Create a full server in a directory named full_server with the requirements listed below.
Since you have used ES6 and Babel in the past projects, let's use babel-node to allow to use ES6 functions like import or export.

  8.1 Organize the structure of the server
  8.2 Write the App controller
  8.3 Write the Students controller
  8.4 Write the routes
  8.5 Write the server reusing everything you created
  8.6 Update package.json (if you are running it from inside the folder full_server)
