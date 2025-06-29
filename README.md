# Journal API

This is a basic API that stores data in and retrieves data from a SQLite DB

## Features
- Accepts journal entries via **POST** requests
- Returns all stored entries via **GET** requests
- Uses SQLite as a lightweight, file-based database
- Built with minimal dependencies and beginner-friendly code

## Tech Stack
- Python (Flask for API)
- SQLite (database)
- Postman (for testing)

## How It Works
- POST /DiaryEntry.html — Accepts JSON journal entries and stores them
- GET /PrvEnt.html — Returns a list of all stored entries

## Why I Made This
This was part of a bigger personal project - a digital journal website. I wanted to see if it was possible to use a database like SQLite for the data, instead of MongoDB or Firebase. So, I watched a tutorial to understand how this could be done.

## Running Locally
1. Clone the repo
2. Make sure you Flask installed:
   ```bash
   pip install Flask
   ```
3. Run it with
   ```bash
   python main.py
   ```

## Notes
- You can use a tool like SQLite Browser to view or manually insert data if needed.
- The database won't persist if deployed without extra setup.
   
