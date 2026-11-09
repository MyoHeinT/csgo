# CS:GO Website

A static website about Counter-Strike: Global Offensive (CS:GO), featuring an overview, community-style reviews, topic pages, and a registration screen.

## Pages

- **Home page:** Game overview, basic information, and recent reviews.
- **Topics:** Short community-style reactions and reviews.
- **Topics details:** A longer introduction, gameplay overview, and comments.
- **Register:** A visual sign-up page.

## Run locally

This project uses plain HTML and CSS and does not require a build step or package installation.

1. Download or clone the project.
2. Open `html/home.html` in a web browser.
3. Use the navigation links to visit the other pages.

You can also serve the project directory with any static web server and open `/html/home.html`.

## Project structure

```text
.
├── css/
│   ├── details.css
│   ├── home.css
│   └── topics.css
├── fontawesome/       # Font Awesome assets
├── html/
│   ├── details.html
│   ├── index.html
│   ├── register.html
│   └── topics.html
└── images/
    └── csgo.jpg
```

## Technologies

- HTML
- CSS

The pages load a Font Awesome kit from an external URL, so an internet connection may be needed for those icons to appear.

## Notes

The registration page is a front-end mockup; it does not submit or store account information. The search box and review buttons are also visual elements and do not currently provide interactive functionality.
