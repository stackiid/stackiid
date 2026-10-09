# Project Directory

A catalogue of the projects in [Ubaid Ahmad's](https://github.com/stackiid) GitHub portfolio: web apps, websites, and console programs. For a one-page summary of my background and skills, see the [profile README](https://github.com/stackiid/stackiid/blob/main/README.md).

Projects are listed from newest to oldest. Study Station is the most recent project and Tic Tac Toe was the first.

## Contents

- [Project index](#project-index)
- [Education and Learning Platforms](#education-and-learning-platforms)
- [Editorial and Content Websites](#editorial-and-content-websites)
- [Portfolio Websites](#portfolio-websites)
- [Interactive Applications and Games](#interactive-applications-and-games)
- [Business and Service Websites](#business-and-service-websites)
- [Console and Practice Projects](#console-and-practice-projects)
- [Adding a new project](#adding-a-new-project)

## Project index

| Project                                                     | Category                           | Technologies                                | Repository                                                        | Live demo                                                  |
| :---------------------------------------------------------- | :--------------------------------- | :------------------------------------------ | :---------------------------------------------------------------- | :--------------------------------------------------------- |
| [Study Station](#study-station)                             | Education and Learning Platforms   | React, TypeScript, Vite, Tailwind CSS, GSAP | [GitHub](https://github.com/stackiid/study-station)               | [Demo](https://stackiid.github.io/study-station/)          |
| [Insight Magazine](#insight-magazine)                       | Editorial and Content Websites     | HTML5, CSS3                                 | [GitHub](https://github.com/stackiid/insight-magazine)            | [Demo](https://stackiid.github.io/insight-magazine/)       |
| [Zaheer Abbas Portfolio](#zaheer-abbas-portfolio)           | Portfolio Websites                 | React, TypeScript, Tailwind CSS, GSAP       | [GitHub](https://github.com/stackiid/zaheer-abbas-portfolio)      | [Demo](https://stackiid.github.io/zaheer-abbas-portfolio/) |
| [StudentHub](#studenthub)                                   | Education and Learning Platforms   | React, Vite, Tailwind CSS, Chart.js         | [GitHub](https://github.com/stackiid/studenthub)                  | [Demo](https://stackiid.github.io/studenthub/)             |
| [Cashew](#cashew)                                           | Interactive Applications and Games | JavaScript (ES modules), Chart.js, Anime.js | [GitHub](https://github.com/stackiid/cashew)                      | [Demo](https://stackiid.github.io/cashew/)                 |
| [Ludo Royale](#ludo-royale)                                 | Interactive Applications and Games | JavaScript, Anime.js, Web Audio API         | [GitHub](https://github.com/stackiid/ludo-royale)                 | [Demo](https://stackiid.github.io/ludo-royale/)            |
| [Transport Logistic](#transport-logistic)                   | Business and Service Websites      | HTML, Tailwind CSS, JavaScript              | [GitHub](https://github.com/stackiid/transport-logistic)          | None                                                       |
| [JavaScript Console Projects](#javascript-console-projects) | Console and Practice Projects      | JavaScript                                  | [GitHub](https://github.com/stackiid/javascript-console-projects) | None                                                       |
| [Wildflour Bakehouse](#wildflour-bakehouse)                 | Business and Service Websites      | HTML5, Tailwind CSS, CSS3                   | [GitHub](https://github.com/stackiid/wildflour-bakehouse)         | [Demo](https://stackiid.github.io/wildflour-bakehouse/)    |
| [Greenova](#greenova)                                       | Business and Service Websites      | HTML5, CSS3                                 | [GitHub](https://github.com/stackiid/greenova)                    | [Demo](https://stackiid.github.io/greenova/)               |
| [Quiz Master](#quiz-master)                                 | Console and Practice Projects      | C++                                         | [GitHub](https://github.com/stackiid/quiz-master)                 | None                                                       |
| [Tic Tac Toe](#tic-tac-toe)                                 | Console and Practice Projects      | C++                                         | [GitHub](https://github.com/stackiid/tic-tac-toe)                 | None                                                       |

---

## Education and Learning Platforms

### Study Station

**Category:** Education and Learning Platforms

A free, searchable directory of curated courses, tutorials, developer resources, and YouTube channels. It does not host learning content; it organizes links to third-party material, and all content lives in typed data files in the repository.

**Highlights**

- Content from typed data files: 10 courses, 65 resources, 4 tutorials, and 82 YouTube channels.
- Weighted, accent-insensitive in-browser search with a keyboard-driven overlay (opens with `/`) and a full results page.
- Category filters kept in the URL query string through React Router.
- GSAP and Framer Motion animations, with reduced-motion support.
- Contact form with client-side validation that posts to Formspree.
- GitHub Actions workflow that lints, builds, and deploys to GitHub Pages.

**Stack:** React 19, TypeScript, Vite, Tailwind CSS 4, React Router 7, GSAP, Framer Motion, Formspree<br>
**Links:** [Repository](https://github.com/stackiid/study-station) | [Live demo](https://stackiid.github.io/study-station/)

### StudentHub

**Category:** Education and Learning Platforms

A front-end academic management and analytics dashboard for a fictional institute. Picking one of seven sample student profiles shows that student's attendance, grades, quizzes, assignments, presentations, and activity. There is no backend; all data is calculated in the browser.

**Highlights**

- Per-student overview with eight metric cards and Chart.js line, doughnut, bar, and radar charts.
- Student roster with live search, filter chips, a semester filter, and add, view, edit, and delete actions with form validation.
- GPA, attendance percentage, and weighted performance score derived in the browser from raw records.
- State handled with React Context and custom hooks, with localStorage persistence and a seed-data fallback.
- GitHub Actions workflow that lints, builds, and deploys to GitHub Pages.

**Stack:** React 19, Vite, Tailwind CSS 3, Chart.js 4 (react-chartjs-2), GSAP 3<br>
**Links:** [Repository](https://github.com/stackiid/studenthub) | [Live demo](https://stackiid.github.io/studenthub/)

---

## Editorial and Content Websites

### Insight Magazine

**Category:** Editorial and Content Websites

A static, editorial-style homepage for a fictional technology magazine, built with HTML5 and CSS3 and no JavaScript. All articles, bylines, and statistics are invented sample content.

**Highlights**

- Cover-story hero and a mixed-size featured grid.
- Breaking-news ticker driven by a CSS keyframe animation, paused on hover.
- Article list with a sticky sidebar holding a trending list, an editor's pick, and a newsletter block.
- Category browse grid and a secondary navigation row that scrolls horizontally on narrow screens.
- Reduced-motion support, semantic landmarks, and keyboard-focusable cards.

**Stack:** HTML5, CSS3 (custom properties, Grid, Flexbox, keyframes)<br>
**Links:** [Repository](https://github.com/stackiid/insight-magazine) | [Live demo](https://stackiid.github.io/insight-magazine/)

---

## Portfolio Websites

### Zaheer Abbas Portfolio

**Category:** Portfolio Websites

A single-page portfolio for full-stack developer Zaheer Abbas. According to the repository README, it was designed and built by Ubaid Ahmad for him, and all page content comes from typed data files.

**Highlights**

- Diagonal split hero using CSS `clip-path` with a GSAP intro animation.
- Projects and testimonials carousels with arrow buttons, keyboard arrows, and touch swipe.
- Dual-mode contact form that sends email through Formspree or opens a pre-filled WhatsApp message, with per-mode validation.
- Reduced-motion support across animations and autoplay.
- GitHub Actions workflow that lints, builds, and deploys to GitHub Pages.

**Stack:** React 19, TypeScript, Vite, Tailwind CSS 4, GSAP (ScrollTrigger), Formspree<br>
**Links:** [Repository](https://github.com/stackiid/zaheer-abbas-portfolio) | [Live demo](https://stackiid.github.io/zaheer-abbas-portfolio/)

---

## Interactive Applications and Games

### Cashew

**Category:** Interactive Applications and Games

A personal expense tracker built with vanilla JavaScript ES modules and no framework or backend. Data stays in the browser's `localStorage`.

**Highlights**

- Three-step onboarding, a personalized dashboard, and 25 selectable display currencies (amounts are formatted, not converted).
- Add and delete expenses across nine categories, with live search, a category filter, and four sort orders.
- Monthly budget card with a progress bar and over-budget status.
- Chart.js doughnut chart of spending by category and line chart of spending over time.
- Light and dark themes, a keyboard-accessible custom dropdown, and optional temporary sample data.

**Stack:** JavaScript (ES modules), HTML5, CSS3, Chart.js, Anime.js, localStorage<br>
**Links:** [Repository](https://github.com/stackiid/cashew) | [Live demo](https://stackiid.github.io/cashew/)

### Ludo Royale

**Category:** Interactive Applications and Games

A browser-based Ludo board game for two to four players, built with vanilla JavaScript. It runs entirely on the client with no backend.

**Highlights**

- Rules engine covering exact-roll finishing, captures, safe squares, six-to-exit, extra turns, a three-sixes penalty, and blockades.
- AI opponents that choose moves with a scoring heuristic.
- CSS 3D dice animated with Anime.js, with rolls drawn through the Web Crypto API.
- Sound effects synthesized at runtime with the Web Audio API, so the repository has no audio files.
- Match timer, local statistics, and automatic save with a Resume Match option.
- Code split into rules, presentation, and support layers that communicate through an event bus.

**Stack:** HTML5, CSS3, JavaScript, Tailwind CSS (CDN), Anime.js, Web Audio API, Web Crypto API, localStorage<br>
**Links:** [Repository](https://github.com/stackiid/ludo-royale) | [Live demo](https://stackiid.github.io/ludo-royale/)

---

## Business and Service Websites

### Transport Logistic

**Category:** Business and Service Websites

A responsive multi-page logistics and freight transportation website. According to the repository description, it was developed as part of a HerDev challenge. The repository README is currently a placeholder with documentation still to come, so the details below come from the repository description and folder structure only.

**Highlights**

- Multi-page site organized into `pages`, `scripts`, `styles`, and `assets` folders.
- Repository description cites modern UI design, smooth animations, and interactive user experiences.

**Stack:** HTML, Tailwind CSS, JavaScript<br>
**Links:** [Repository](https://github.com/stackiid/transport-logistic)

### Wildflour Bakehouse

**Category:** Business and Service Websites

A responsive single-page website for a fictional artisan bakery. All text, prices, and testimonials are sample content.

**Highlights**

- 11 page sections, including a hero, product categories, daily specials, testimonials, and a footer.
- Mobile navigation built from a hidden checkbox and the CSS sibling selector, with no application JavaScript.
- Tailwind CSS through the Play CDN plus a custom stylesheet using CSS variables, Grid, Flexbox, and `clamp()`.
- Semantic landmarks, aria-labels, image alt text, focus-visible styles, and a reduced-motion rule.

**Stack:** HTML5, Tailwind CSS (CDN), custom CSS3<br>
**Links:** [Repository](https://github.com/stackiid/wildflour-bakehouse) | [Live demo](https://stackiid.github.io/wildflour-bakehouse/)

### Greenova

**Category:** Business and Service Websites

A responsive single-page marketing website for a renewable energy company, built with plain HTML5 and CSS3. The text, statistics, and contact details are sample content.

**Highlights**

- Sections for solar, wind, energy storage, and consulting services, plus about, impact, projects, and blog preview areas.
- JavaScript-free mobile menu built with a hidden checkbox and the CSS `:has()` selector.
- Design tokens as CSS custom properties and fluid typography with `clamp()`.
- Semantic landmarks, aria-labels, image alt text, and focus-visible styles.

**Stack:** HTML5, CSS3 (custom properties, Grid, Flexbox)<br>
**Links:** [Repository](https://github.com/stackiid/greenova) | [Live demo](https://stackiid.github.io/greenova/)

---

## Console and Practice Projects

### JavaScript Console Projects

**Category:** Console and Practice Projects

Twelve independent console programs for the browser. Each is a single `main.js` file with its own README, uses `prompt()` and `alert()` for input and output, and keeps its data in memory. Scope grows from a 36-line number-guessing game to a 2,487-line cinema booking system with customer and administrator menus.

**Highlights**

- Projects 01 to 12: Guessing Game, Todo List, Super Mart, Library System, Student Grading System, Secure Digital Banking, Expense Tracker, Meal Planner, Boutique Inventory Tracker, Car Rental System, Book My Flight, CineMax Cinema.
- Book My Flight has guest, user, and administrator roles with 60 generated flights.
- CineMax Cinema includes a seat map, food ordering, coupons, a wallet, and administrator reports.

**Stack:** Vanilla JavaScript (browser console, no dependencies)<br>
**Links:** [Repository](https://github.com/stackiid/javascript-console-projects)

### Quiz Master

**Category:** Console and Practice Projects

A console quiz application in C++, built as a Semester 2 project according to its README. A single `main.cpp` holds the whole program.

**Highlights**

- Student registration with 10 fields and level-aware validation for school, college, and university students.
- 30 multiple-choice questions across seven subjects, with a two-round skip system.
- Result sheet with score, percentage, and letter grade, followed by a text completion certificate with a random verification code.
- Object-oriented structure with `User`, `Question`, and `QuizEngine` classes.

**Stack:** C++ (standard library only)<br>
**Links:** [Repository](https://github.com/stackiid/quiz-master)

### Tic Tac Toe

**Category:** Console and Practice Projects

A two-player console Tic-Tac-Toe game in C++, built as a Semester 1 project for Windows terminals according to its README.

**Highlights**

- Custom player names and a numbered board redrawn after every move.
- Win detection across rows, columns, and diagonals, plus draw detection.
- Input validation for non-numeric, out-of-range, and already-taken positions.
- Scoreboard across multiple rounds with a play-again loop.

**Stack:** C++ (`iostream`, `string`, `limits`)<br>
**Links:** [Repository](https://github.com/stackiid/tic-tac-toe)

---

[Back to profile README](https://github.com/stackiid/stackiid/blob/main/README.md)
