<div align="center">
    <h1 id="Header">filmX 🎥</h1>
</div>

**Your gateway to exploring movies, genres, and trending films!**
```
Note: This was my final project for my Web Dev. class I took at WashU.
```

## Table of Contents

1. [Overview](#overview)
2. [Project Link](#project-link)
3. [Features](#features)
4. [Tech Stack](#tech-stack)
3. [React Setup](#react-setup)
5. [Installation and Usage](#installation-and-usage)

---

## Overview

**filmX** is a user-friendly public platform designed to let users explore a wide variety of movies across genres, trending films, and more. Built with inspiration from Netflix's iconic design, **filmX** provides a seamless browsing experience with interactive features.

---

## Project Link

- **Homepage**: [filmX Homepage](https://wustl-cse204a-fl2024-2.github.io/final-project-kananahmadov2001/)

---

## Features

- **Trending Section**: Browse trending movies across various genres.
- **Search Movies**: Find movies based on titles, genres, and keywords.
- **Interactive Modal**: Click on a movie poster to view details like genre, release year, and a short description.
- **Responsive Design**: Works on desktops, tablets, and mobile devices.
- **Genre-based Browsing**: Explore movies categorized under Action, Comedy, Horror, and more.
- **FAQ Section**: Answers to common user questions.

---

## Tech Stack

- **Frontend**: React.js, Bootstrap, JSX
- **API**: The Movie Database (TMDb) API
- **Styling**: CSS, Bootstrap
- **Icons**: Bootstrap Icons

---

## React Setup

The React environment is established via CDN links in `index.html` and `movies.html`:

```html
<script src="https://unpkg.com/react@18/umd/react.development.js"></script>
<script src="https://unpkg.com/react-dom@18/umd/react-dom.development.js"></script>
<script src="https://unpkg.com/axios/dist/axios.min.js"></script>
<script src="https://unpkg.com/@babel/standalone/babel.min.js"></script>
```

---

## Installation and Usage

### Prerequisites

- A web browser to view the application.
- Internet connection to fetch data from the TMDb API.

### Steps

1. Clone the repository:
   ```bash
   git clone https://github.com/kananahmadov2001/filmX.git
   ```
2. Navigate to the project folder:
   ```bash
   cd filmX
   ```
3. Open the project in your browser:

- Open index.html for the main homepage.
- Open movies.html for the movie search page.
