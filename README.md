# Journal API

A REST API for a simple journaling application, built with **Flask** and **SQLite**.

This API was originally part of my [Journal Site](https://github.com/Tanaum/Journal_Site) project and was later separated into its own repository.

## Features

* User signup and login
* Password hashing
* Create journal entries
* Retrieve a user's entries
* SQLite database with user/entry relationships
* CORS support

## Tech Stack

* Python
* Flask
* SQLite
* Flask-CORS

## Endpoints

| Method | Endpoint                        | Description                 |
| ------ | ------------------------------- | --------------------------- |
| `POST` | `/sign-up`                      | Create a user account       |
| `POST` | `/log-in`                       | Log in and retrieve user ID |
| `POST` | `/api/save-entry/`              | Save a journal entry        |
| `GET`  | `/api/get-entries/<userID>`     | Get a user's entries        |
| `GET`  | `/api/edit-entry/<TimeInMilli>` | Retrieve an entry           |

## Running Locally

```bash
git clone https://github.com/Tanaum/Journal_API.git
cd Journal_API
pip install -r requirements.txt
python main.py
```

> This repository contains the backend/API extracted from the original Journal Site project. The frontend/templates are kept in the original project.

## What's Next?

This project is mainly a backend learning project. Future improvements could include moving to **PostgreSQL**, adding **SQLAlchemy**, proper authentication, and expanding the API into a full CRUD service.
