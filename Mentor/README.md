# Learning Journey — Mentor Template

A small, responsive educational website template (Mentor) customized for the "Learning Journey" project.

## Overview

This repository contains a static HTML/CSS/JS site based on the Mentor template from BootstrapMade. It's designed as a simple learning/course landing site and includes pages for courses, trainers, events, pricing and contact.

Key goals:
- Provide a clean, responsive educational site starter.
- Be easy to customize: update `index.html`, assets under `assets/`, and vendor libraries.

## Features

- Responsive layout (Bootstrap 5)
- Hero, About, Courses, Trainers, Events, Pricing, Contact pages
- Vendor integrations: AOS, Glightbox, Swiper, PureCounter
- Simple PHP forms (in `forms/`) for contact/newsletter (needs PHP on server to work)

## Quick start (Windows PowerShell)

1. Open the project folder: `Mentor`
2. Open `index.html` in your browser. In PowerShell you can run:

```powershell
Start-Process .\index.html
```

Or simply double-click `index.html` in File Explorer.

Notes:
- The contact/newsletter forms require a PHP-capable server to process submissions (`forms/contact.php`, `forms/newsletter.php`).
- Vendor libraries are included under `assets/vendor/` — you don't need to install anything to run the static site.

## File structure (important files)

- `index.html` — Home / landing page
- `about.html`, `courses.html`, `trainers.html`, `events.html`, `pricing.html`, `contact.html` — other pages
- `assets/css/main.css` — main stylesheet
- `assets/js/main.js` — main JavaScript
- `assets/vendor/` — bundled third-party libraries (Bootstrap, AOS, Glightbox, Swiper, etc.)
- `assets/img/` — images used across the site
- `forms/` — PHP handlers for contact and newsletter forms (requires a server with PHP)

## Customization tips

- Change site title/logo: edit the header in `index.html` and update `.sitename` in `assets/css/main.css` if needed.
- Replace images in `assets/img/` and update references in HTML.
- Modify styles in `assets/css/main.css` or add custom rules in a new stylesheet.
- For animation timing, tweak `data-aos` attributes or the AOS initialization in `assets/js/main.js`.

## Development / Serving locally

For static preview you can use the simple PowerShell command above. For testing forms or running a lightweight PHP server (if you have PHP installed), run in PowerShell from the `Mentor` folder:

```powershell
php -S localhost:8000
```

Then open `http://localhost:8000/index.html` in your browser.

## Credits & License

This project is based on the free "Mentor" Bootstrap template by BootstrapMade. The original licensing and credits remain in the template. See the header comments in `index.html` and the `assets/vendor/` directories for more details.

If you plan to publish the site commercially, please review the template license at: https://bootstrapmade.com/license/

## Contact

If you want help customizing this template (colors, layout, or converting to a CMS), reply here and I can implement small changes.
