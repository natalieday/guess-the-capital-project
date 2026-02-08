# Guess the Capital

A small interactive geography game: guess the capital city for a given country. Built with HTML/CSS/JavaScript and a simple JSON data source, with an optional Docker setup for running locally in a container.

## Features
- Randomized country prompts
- Input validation + instant feedback
- Score/attempt tracking (if implemented)
- Lightweight static frontend (no backend)

## Run locally
Open `index.html` directly in your browser.

## Run with Docker (optional)
Build and run the container:
```bash
docker build -t guess-the-capital .
docker run -p 8080:80 guess-the-capital
```
Then visit http://localhost:8080.
