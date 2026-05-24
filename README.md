# Flask CRUD App

A simple CRUD app with Flask + SQLite. Search, filter, status toggle, edit modal, and a JSON API.

## One Click Deploy

[![Deploy on Railway](https://railway.com/button.svg)](https://railway.com/deploy/d7euiC?referralCode=-Xd4K_&utm_medium=integration&utm_source=template&utm_campaign=generic)

## Local Run

```bash
pip install -r requirements.txt
python main.py
```

## API Endpoints

| Method | Route | Description |
|--------|-------|-------------|
| GET | `/api/items` | List all items |
| POST | `/api/items` | Create item `{"title":"...","description":"..."}` |
| DELETE | `/api/items/<id>` | Delete item |

## Env Variables (optional)

- `SECRET_KEY` — Flask secret key
- `PORT` — Server port (default 8080)
- `DATABASE_PATH` — SQLite file path
