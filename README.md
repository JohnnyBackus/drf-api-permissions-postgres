
# LAB - Class 32

## Project: Permissions & Postgresql

### Author: Johnny Backus

### Links and Resources

- [CodeFellows Python Lab Instructions](https://codefellows.github.io/code-401-python-guide/reference/submission-instructions/labs/)
- [CodeFellows README template](https://codefellows.github.io/code-401-python-guide/reference/submission-instructions/labs/README-template.html)
- lecture demo code used for reference
- GitHub CoPilot chat feature used to uncover error caused by modifying model after making migtations

### Setup

- *.env requirements: n/a*
- must have Docker

### How to Initialize/Run Your Application

- Enter CLI command `docker compose build`
- Enter CLI command `docker compose up`
- View content in local port indicated in terminal
- path to booklist is /api/v1/books/

### How to Use Your Library

- n/a

### Tests

#### How to Run Tests

- run CLI command `Docker compose exec web python manage.py test`

#### Tests of Note

- Tests for CRUD; followed format provided by demo.

#### Incomplete Tests

- unable to pass CRUD tests; failure likely related to permissions
