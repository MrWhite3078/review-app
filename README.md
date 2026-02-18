#  FilmBox — Movie Reviews Platform

A fully client-side movie review web application built with vanilla HTML, CSS, and JavaScript. FilmBox lets users create accounts, write and manage movie reviews, and explore what others are watching.

---

##  Features

- **User Authentication** — Sign up and log in with persistent sessions via `localStorage` and `sessionStorage`
- **Add & Edit Reviews** — Submit movie reviews with a title, release year, poster image URL, star rating (1–5), and written review
- **Browse Reviews** — View all reviews across multiple pages: Home, All Reviews, Popular This Week, and Trending
- **Sort & Filter** — Sort reviews by newest, oldest, or rating (high to low / low to high)
- **Review Detail Modal** — Click any review card to open a full-detail modal view
- **Profile Page** — See your personal stats, recent activity, and top-rated movies
- **Delete Reviews** — Remove your own reviews at any time
- **Responsive Design** — Works on desktop and mobile

---

##  Getting Started

No build tools or dependencies required. Just open the file in a browser.

```bash
git clone https://github.com/your-username/filmbox.git
cd filmbox
open index.html
```

Or simply drag `index.html` into your browser.

---

##  Project Structure

```
filmbox/
└── index.html       # Entire application (HTML + CSS + JS in one file)
```

FilmBox is intentionally a single-file app with no external dependencies or frameworks.

---

##  Tech Stack

| Layer | Technology |
|-------|------------|
| Markup | HTML5 |
| Styling | CSS3 (custom, no frameworks) |
| Logic | Vanilla JavaScript (ES6+) |
| Storage | `localStorage` / `sessionStorage` |

---

## Pages Overview

| Page | Description |
|------|-------------|
| **Home** | Featured review + recent reviews + site-wide stats |
| **All Reviews** | Every review with sort controls |
| **Popular This Week** | Reviews submitted in the last 7 days |
| **Trending** | Most recently added reviews |
| **Profile** | Your personal stats, activity feed, and top-rated films |

---

##  Data Storage

All data is stored in the browser's `localStorage`:

- `filmboxUsers` — registered usernames and passwords
- `filmboxUserMetadata` — join date and last login per user
- `movieReviews` — all review data

>  **Note:** Data is stored in plain text in `localStorage`. This app is intended for personal/demo use only and is **not suitable for production** without a proper backend and password hashing.

---

## Default Credentials

There are no pre-seeded accounts. Use the **Sign Up** screen to create your own account (username ≥ 3 characters, password ≥ 6 characters).

---

##  Contributing

Contributions are welcome! Feel free to open an issue or submit a pull request for:

- Backend integration (e.g. Node.js + MongoDB)
- Password hashing (e.g. bcrypt)
- Image upload support
- Genre tagging and filtering
- Likes / upvotes on reviews

---

## License

MIT License — free to use, modify, and distribute.
