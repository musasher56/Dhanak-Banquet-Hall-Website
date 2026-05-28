# Dhanak Banquet Hall — Website Project

A multi-page static website for Dhanak banquet hall, built as a front-end development learning project. The site covers everything a real event venue website needs — venue showcases, menus, a photo gallery, and a working booking form.

## Pages

| File | Purpose |
|---|---|
| `index.html` | Landing page, about, and gallery etc |
| `Venues.html` | Venue listings for all three Dhanak locations |
| `gallery.html` | Photo gallery organised by venue and hall name |
| `Menu.html` | Event menus for Corporate, Wedding, Birthday, and Meeting categories |
| `customplanner.html` | Booking form that submits to a Google Apps Script endpoint |

## What I practised building this

- Structuring a multi-page site with shared navigation across all pages
- CSS Flexbox layouts — used heavily for the navbar, image grids, two-column sections, and the footer
- Responsive design with `@media` queries — the site collapses to a single-column mobile layout at 768px, with a hamburger menu replacing the navbar
- HTML forms — input types, dropdowns, validation, and intercepting the submit with `fetch` to avoid a page redirect
- Working with Google Sheets as a free form backend via Google Apps Script
- Font and icon libraries — Google Fonts (Antic Didone, Great Vibes) and Font Awesome 6 for the contact icons
- CSS transitions and hover effects for the navigation links and buttons

## Tech stack

- HTML5, CSS3, vanilla JavaScript — no frameworks
- [Font Awesome 6](https://fontawesome.com/) for icons
- [Google Fonts](https://fonts.google.com/) for typography
- Google Apps Script as the form submission endpoint

## Running it

No build step needed. Just open `index.html` in a browser, or serve the folder with any static file server:

```bash
# Python
python -m http.server 5500

# Node (if you have live-server)
npx live-server
```

Keep all HTML, CSS, and image files in the same directory so the relative paths resolve correctly.

## Project status

This is a learning project completed as part of front-end development practice. Not intended for production use.
