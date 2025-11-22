# experiment1-simple-db
# Experiment 1: Simple Database Connection & Display

## Objective
Connect to a MySQL database and fetch static data (list of users).

## Description
- Create a MySQL database `testdb` with a table `users`.
- Insert sample data into the table.
- Use Node.js with `express` and `mysql2` to fetch and display data.
- Render data in an HTML table using EJS.

## Project Structure
myproject/
│
├─ app.js                  # Node.js server code
├─ package.json            # Project dependencies
├─ package-lock.json       # Lock file
├─ testdb.sql              # SQL file for creating database/table/data
└─ views/
   └─ users.ejs            # EJS template for displaying users

## How to Run
1. Clone repository
2. Run `npm install` to install dependencies
3. Ensure MySQL is running and database `testdb` exists
4. Run `node app.js`
5. Open `http://localhost:3000/users` in a browser
