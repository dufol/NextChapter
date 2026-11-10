# NextChapter

NextChapter is a student community application for sharing the experiences, milestones, and advice that shape academic, personal, and career journeys. It helps college students and recent graduates discover other perspectives, celebrate progress, and keep useful stories close at hand.

## Features

- Browse a sample community feed and filter posts by category.
- Search stories and students by name, school, subject, or post content.
- Create text posts in categories such as Career, Academic, Achievement, Advice, and College Life.
- Like posts, add comments, and save posts for later.
- Explore student profiles, trending topics, and connect with suggested students.
- View a sample personal journey with milestones, skills, and career guidance.
- Use responsive navigation and layouts on desktop and mobile screens.

## Technologies

- HTML for the application structure.
- CSS for layout, styling, and responsive behavior.
- Vanilla JavaScript for navigation, rendering, search, post interactions, and browser storage.
- `localStorage` to retain posts and connections in the current browser.

There are no external libraries, package installations, or build tools required.

## Project Structure

```text
NextChapter/
├── index.html      # Application structure and asset links
├── style.css       # Application styles
├── script.js       # Application behavior and sample content
├── README.md       # Project documentation
└── REFLECTION.md   # Project reflection
```

## Installation

1. Download or clone the project and open its folder.
2. Open `index.html` in a modern web browser.

Alternatively, run a local static web server from the project folder:

```sh
python3 -m http.server 8000
```

Then visit `http://localhost:8000` in your browser.

## Usage

Use the navigation to switch between the feed, Explore, Create Post, My Journey, Career, Saved Posts, and Profile views. In the feed, select a category or use the search field to find posts. Choose **Create Post** or the feed composer to write and publish a categorized text post. Use the actions on each post to like, comment, or save it.

Explore lists sample topics and students. Use **Connect** to follow a suggested student. The Journey and Career views provide sample milestones, skills, and career advice; the Profile view shows the sample user's details.

Posts, post interactions, and connections are stored in the browser's local storage, so they are available again in the same browser. This is a front-end demonstration: it has no account system or server, and its sample users and career content are not live community data. Notifications and messages display demonstration notices; profile editing is not implemented.
