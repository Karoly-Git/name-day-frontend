# Name Day Frontend Documentation

A static frontend documentation site for the **Name Day Backend API**.  
It provides clear, human-readable API documentation with live example links for exploring name-day data for Poland and Hungary.

🔗 Live frontend demo: https://karoly-git.github.io/name-day-frontend/  
🔗 Backend API: https://name-day-backend-0d74dcea0ed2.herokuapp.com/

---

## Overview

This project serves as the public-facing documentation for the Name Day Backend API.  
It explains available endpoints, request formats, and example usage in a simple and accessible way.

The frontend is intentionally lightweight and framework-free to ensure:
- fast load times
- zero build complexity
- easy hosting via GitHub Pages

---

## Tech Stack

- HTML5
- CSS3
- Vanilla JavaScript
- GitHub Pages (deployment)

---

## Features

- Clear API endpoint documentation
- Live clickable example requests
- Syntax-highlighted JSON responses
- Health check endpoint visibility
- Responsive, minimal layout
- No external dependencies

---

## Supported API Features

- Retrieve all name days
- Filter by month
- Filter by month and date
- Filter by month, date, and country
- Health check endpoint

Supported countries:
- Hungary (`hu`)
- Poland (`pl`)

---

## Project Structure

```text
.
├── index.html      # API documentation page
├── styles.css      # Styling for documentation layout
├── script.js       # Small helper scripts (e.g. year update)
├── favicon.ico     # Site favicon
└── README.md       # Project documentation
```

---

## Local Development

This project does not require a build step.

To run locally:
1. Clone the repository
2. Open `index.html` in your browser

Alternatively, you can use a local server:
```bash
npx serve .
```

---

## Deployment

The frontend is deployed using **GitHub Pages**.

- The `main` branch contains the static files
- Any push to the branch updates the live site automatically
- No build or CI pipeline required

---

## Relationship to Backend

This frontend is designed specifically to document and showcase the **Name Day Backend API**.

Backend features demonstrated here include:
- RESTful routing
- Input normalization
- Error handling
- Continuous deployment via GitHub and Heroku

---

## Future Improvements

- Interactive API tester (fetch requests from the browser)
- Copy-to-clipboard buttons for endpoints
- OpenAPI / Swagger integration
- Dark mode toggle
- Multi-language documentation

---

## Author

**Karoly Hornyak**  
Full-Stack Web Developer  
📧 karoly.webdev@gmail.com  
🌐 https://karolyhornyak.co.uk/
