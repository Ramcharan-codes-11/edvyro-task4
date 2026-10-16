# Internship REST API

A REST API built with Node.js, Express.js, and SQLite to manage internship records.

## Features

- List all internships
- View an internship by ID
- Add new internships
- Update internship details
- Delete internships
- Input validation and error handling
- Pagination using page and limit
- SQLite database storage
- API health-check endpoint

## Technologies

- Node.js
- Express.js
- SQLite
- JavaScript

## API Endpoints

| Method | Endpoint | Purpose |
|---|---|---|
| GET | /api/internships | List internships |
| GET | /api/internships/:id | View one internship |
| POST | /api/internships | Add an internship |
| PUT | /api/internships/:id | Update an internship |
| DELETE | /api/internships/:id | Delete an internship |
| GET | /health | Check API status |

## Pagination

Example: `/api/internships?page=1&limit=2`

## Run Locally

1. Install Node.js.
2. Run `npm install`.
3. Run `npm start`.
4. Open `http://localhost:3000/health`.

## Task 5 Improvements

- Documented the API health-check endpoint.
- Listed the CRUD endpoints and pagination.
- Documented validation and error handling.

## Testing Status

The project code is available on GitHub.

## Repository

https://github.com/Ramcharan-codes-11/edvyro-task4
