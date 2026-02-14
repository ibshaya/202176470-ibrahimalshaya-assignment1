# Technical Documentation – Assignment 1 Portfolio

## 1. Project Overview
This project is a simple, responsive personal portfolio web application built using HTML, CSS, and JavaScript. It demonstrates fundamental web development skills, responsive design techniques, and AI-assisted development. The portfolio includes three main sections: About Me, Projects, and Contact, with additional interactivity features and AI-supported enhancements.

## 2. Folder Structure

assignment-1/
├── README.md # Project overview and setup instructions
├── index.html # Main HTML page
├── css/
│ └── styles.css # CSS styling for layout and responsiveness
├── js/
│ └── script.js # JavaScript for interactivity
├── assets/
│ └── images/ # Placeholder and profile images
├── docs/
│ ├── ai-usage-report.md # AI tools used and workflow explanation
│ └── technical-documentation.md # This file
└── .gitignore # Files/folders to ignore in Git



Each folder has a specific role:

- **css/** – Contains all styling rules. Organized with clear section comments.
- **js/** – Contains scripts for interactive features like smooth scrolling, theme toggle, and dynamic greetings.
- **assets/images/** – Stores all images, including placeholders for projects and profile picture.
- **docs/** – Contains AI usage report and technical documentation.

## 3. HTML Structure
The `index.html` page is structured into main semantic sections:

1. **About Me** – Brief introduction, tagline, optional profile image.
2. **Projects** – At least two projects displayed with title, description, and placeholder image.
3. **Contact** – Form with fields for Name, Email, and Message (no backend implemented).
4. **Optional Sections** – Can include Skills, Hobbies, or Achievements.

Semantic tags (`<header>`, `<section>`, `<main>`, `<footer>`) are used to improve accessibility and organization.

## 4. CSS Implementation
The `styles.css` file handles:

- **Layout**: Flexbox and CSS Grid are used for responsive layouts.
- **Responsive Design**: Media queries adjust sections for mobile, tablet, and desktop views.
- **Styling**: Color schemes, font sizes, spacing, and hover effects are implemented consistently.
- **Interactivity Support**: Classes for dynamic effects (e.g., theme toggling) are defined.

## 5. JavaScript Features
The `script.js` file provides interactive functionality:

- **Smooth Scrolling** – Clicking navigation links scrolls smoothly to target sections.
- **Theme Toggle** – Light/dark theme switching with user preference saved in `localStorage`.
- **Dynamic Greeting** – Displays greeting messages based on time of day.
- **Form Interaction** – Basic front-end validation and dynamic focus effects.


## 6. Responsive Design
Responsiveness was achieved using:

- **CSS Grid and Flexbox** – Flexible containers and columns.
- **Media Queries** – Adjust layout, font sizes, and spacing for mobile (<768px), tablet (768–1024px), and desktop (>1024px).
- **Testing** – Used browser resizing and DevTools to ensure all content adapts correctly.

## 7. AI Integration
AI tools were leveraged to streamline development:

- **ChatGPT** – Consulted for project folder structure, file organization, and responsive design guidance.
- **Claude** – Assisted in generating HTML sections, CSS styling snippets, and JavaScript functionality.

All AI-generated code was reviewed and modified to maintain correctness and assignment compliance.

## 8. Development Workflow
1. Planned the folder structure and section layout with ChatGPT guidance.
2. Created HTML skeleton and basic CSS styling.
3. Added JavaScript interactivity (smooth scrolling, theme toggle, greeting messages).
4. Tested responsive design across different screen sizes.
5. Documented AI usage and technical details.

## 9. Challenges & Solutions
- **AI-generated code adjustments** – Some snippets required modification to fit project needs.
- **Responsive layout issues** – Fixed overlapping or misaligned elements using media queries and Flexbox tweaks.
- **Dynamic interactions** – Ensured smooth scrolling and theme toggle worked across devices.

## 10. Conclusion
This technical documentation summarizes the implementation details of the portfolio project, explaining the structure, functionality, and AI-assisted development workflow. The project demonstrates proficiency in HTML, CSS, and JavaScript, along with responsible and effective use of AI tools for coding support.
