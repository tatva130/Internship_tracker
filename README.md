
# Backend Internship Roadmap Tracker

A standalone, interactive web dashboard designed to track a 10-month study plan aiming for a ₹20k+ remote backend internship[cite: 1]. Built entirely as a single file, the application gamifies the learning process through progress bars, sequential unlocking, and streak tracking[cite: 1]. 

## 🚀 Features

* **Sequential Level Progression:** Features 5 distinct curriculum levels (Python, DSA, Backend, Internship Ready, and AI / ML)[cite: 1]. Subsequent levels remain visually locked until the current level reaches 100% completion[cite: 1].
* **Mixed-Type Tracking:** Supports standard checkbox items, grouped sub-tasks (e.g., mini-projects), and numeric inputs for target-based goals like solving 100 LeetCode problems[cite: 1].
* **Daily Tracker & Streaks:** Monitors daily habits including Learn (1 hr), DSA (1 hr), Project (1 hr), and Revision (30–60 min)[cite: 1]. Completing all daily tasks increments a continuous streak counter[cite: 1].
* **Weekly Metrics:** Tracks dynamic weekly inputs such as GitHub Commits, Projects Built, and Study Days[cite: 1]. The weekly tracker uses ISO weeks and automatically resets every Monday[cite: 1].
* **Overall Progress Calculation:** Dynamically updates a master progress bar in the sticky header based on the completion of tasks across all levels[cite: 1].
* **Data Persistence:** Automatically saves all user interactions (checkboxes, numeric inputs, and streaks) to the browser's `localStorage`[cite: 1].

## 🛠️ Tech Stack

* **HTML5:** Semantic structure contained entirely within `index.html`[cite: 1].
* **CSS3:** Custom dark theme featuring CSS variables, CSS Grid, backdrop-filters, and radial-gradient backgrounds[cite: 1].
* **Vanilla JavaScript:** Handles DOM manipulation, date parsing, ISO week calculations, and state management without any external libraries or frameworks[cite: 1].

## 📋 Roadmap Overview

The tracker is divided into the following timeline:
1. **Level 1 (September):** Python fundamentals, OOP, and mini-projects[cite: 1].
2. **Level 2 (Oct – Nov):** Data Structures and Algorithms, aiming for 100 LeetCode problems[cite: 1].
3. **Level 3 (Dec – Feb):** Backend engineering with FastAPI, PostgreSQL, and REST APIs[cite: 1].
4. **Level 4 (Mar – May):** Internship readiness, Docker, testing, deployment, and applications[cite: 1].
5. **Level 5 (After Internship):** AI/ML fundamentals including NumPy, Pandas, and Scikit-learn[cite: 1].

## 💻 Getting Started

This project is a zero-dependency, single-file application.

1. Clone or download the repository.
2. Double-click `index.html` to open it in any modern web browser[cite: 1].
3. Bookmark the page to maintain your daily streak[cite: 1]. Your data will remain saved in your browser as long as you do not clear your site data[cite: 1].
