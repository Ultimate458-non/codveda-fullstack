# Codveda · Users REST API

A Node.js and Express REST API with full CRUD on user records stored in SQL Server.
Built during my full-stack internship at Codveda Technologies (Aug – Sep 2025).

## Endpoints
| Method | Route | Action |
|---|---|---|
| GET | `/users` | List all users |
| GET | `/users/:id` | Get one user |
| POST | `/users` | Create a user |
| PUT | `/users/:id` | Update a user |
| DELETE | `/users/:id` | Delete a user |

[Check the routes in `index.js` and edit the table if the paths differ.]

## Tech
`Node.js` `Express` `SQL Server` `mssql` `dotenv`

## Run it
```bash
git clone https://github.com/Ultimate458-non/codveda-fullstack.git
cd codveda-fullstack
npm install
```
Create a `.env` file (never commit it):
```
DB_USER=your_user
DB_PASSWORD=your_password
DB_SERVER=localhost
DB_NAME=your_database
```
Then start the server:
```bash
node index.js
```

## Status
Backend complete. A React front end is planned.

## Author
Ultimate Ngobeni · [Portfolio](https://ultimate-portfolio-six.vercel.app)
