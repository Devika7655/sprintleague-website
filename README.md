# Sprint League

Gamified productivity tracker with sprints, scoring, analytics, and squad accountability.

## Live Demo

https://devika7655.github.io/sprintleague-website/

---

## Technologies Used

- HTML
- CSS
- JavaScript
- React 18
- IndexedDB
- Node.js

---

## Features

- Sprint-based productivity tracking
- Gamified scoring system
- Task management dashboard
- Analytics and performance tracking
- Squad accountability system
- Leaderboards and badges
- Live clock and activity tracking
- Responsive multi-page UI

---

## Quick Start

```bash
node server.js
```

Then open:

```text
http://localhost:3000
```

in your browser.

> ⚠️ Must be served over HTTP — opening index.html directly as a file:// URL breaks IndexedDB functionality.

---

## Project Structure

```text
sprint-league/
├── server.js
├── index.html
├── tasks.html
├── analytics.html
├── friends.html
├── league.html
│
├── css/
│   ├── base.css
│   ├── components.css
│   ├── dashboard.css
│   └── auth.css
│
└── js/
    ├── auth-ui.js
    ├── app.js
    ├── clock.js
    ├── dashboard.js
    ├── tasks.js
    ├── analytics.js
    ├── friends.js
    ├── league.js
    └── lib/
        ├── db.js
        ├── auth.js
        └── utils.js
```

---

## Authentication Flow

1. IndexedDB initializes on page load
2. Session state is checked automatically
3. React auth modal handles login and registration
4. User data and statistics are stored locally
5. Session persists using localStorage
6. Logout clears session and reloads the application

---

## Purpose of the Project

Sprint League was built as a gamified productivity platform to help users:
- manage tasks efficiently
- stay focused using sprint sessions
- track productivity analytics
- compete through leaderboards
- improve accountability with squads

---

## Author

Devika Srivastava
