# Jesse Ochoi Portfolio Website

## Overview

This is a professional IT portfolio website built using HTML, CSS, and JavaScript.
The site showcases professional experience, technical skills, projects, and contact information.

## Features

* Responsive design (Mobile + Desktop)
* Dark mode toggle
* Smooth scrolling navigation
* Fade-in animations
* Professional hero section
* Skills & services cards
* Project showcase
* Contact section with social links

## Technologies Used

* HTML5
* CSS3
* JavaScript (Vanilla)
* Google Fonts (Inter)

## Project Structure

portfolio/
│
├── index.html
├── style.css
├── images/
│   └── banner.jpg
└── README.md

## Sections Explained

### Header

Contains:

* Logo
* Navigation links
* Dark mode toggle
* Mobile hamburger menu

### Hero Section

Main introduction:

* Name
* Role
* Description
* Call-to-action buttons
* Branding image

### About Section

Displays:

* Experience
* Current Role
* Education
* Availability

Uses CSS Grid and card layout.

### Skills Section

Displays:

* Infrastructure & Networking
* System Administration
* IT Service Management
* Consulting Services

Uses card-based layout.

### Projects Section

Shows current IT projects:

* Network Infrastructure
* Automation Scripts
* Portfolio Website

### Contact Section

Includes:

* Email link
* LinkedIn
* Twitter
* GitHub
* Company website

## JavaScript Features

### Mobile Menu Toggle

toggle.addEventListener('click', () => {
nav.classList.toggle('active');
});

This enables mobile navigation menu.

### Dark Mode

Uses Local Storage:

* Saves theme preference
* Loads theme on refresh

### Scroll Animation

IntersectionObserver used for:

* Fade-in animation
* Smooth appearance of sections

## Responsive Design

Uses:

@media (max-width: 768px)

To adjust layout for:

* Mobile devices
* Tablets

## Author

Jesse Ochoi
IT Manager | Systems & Infrastructure
OJO NET

## License

Personal Portfolio — All Rights Reserved
