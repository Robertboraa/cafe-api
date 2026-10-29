# Cafe API

A REST API built with Flask and SQLAlchemy to manage cafe data.

## Endpoints

| Method | URL | Description |
|--------|-----|-------------|
| GET | /random | Get a random cafe |
| GET | /all | Get all cafes |
| GET | /search?loc=London | Search cafes by location |
| POST | /add | Add a new cafe |
| PATCH | /update-price/<id>?new_price=£4 | Update coffee price |
| DELETE | /delete/<id>?api_key=TopSecretAPIKey | Delete a cafe |

## Tech Stack
- Python, Flask, SQLAlchemy, SQLite
