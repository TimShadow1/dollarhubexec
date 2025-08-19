# Executor Authentication Site

This repository contains the frontend (static site) and backend (API) for the Executor login and purchase system.

## Setup Instructions

### Backend (API)
1. Deploy the `api` folder to Heroku, Railway, or a similar service.
2. Set the environment variable `SECRET_KEY` to a random string.
3. The database (SQLite) will be created automatically.

### Frontend (Website)
1. The `docs` folder is set up for GitHub Pages.
2. Update the `apiUrl` in `docs/js/auth.js` to point to your deployed backend URL.
