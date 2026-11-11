# Travel Agency Website

A responsive, static travel-agency website built with HTML and CSS. The page presents destination packages and travel-related information in a single scrolling layout.

## Features

- Landing section with a travel-themed video background
- Navigation to packages, services, gallery, reviews, contact, and booking sections
- Destination cards with descriptions and sample pricing
- Travel-service and gallery sections
- Review section using Swiper-compatible markup
- Login, search, contact, and booking form interfaces

> **Note:** This repository contains front-end presentation only. The login, search, contact, and booking forms are UI examples; no authentication, payment, booking, or contact-processing backend is included.

## Tech Stack

- HTML5
- CSS3
- [Swiper](https://swiperjs.com/) for slider components (loaded from a CDN)
- [Font Awesome](https://fontawesome.com/) for icons (loaded from a CDN)

## Project Structure

~~~text
website/
├── index.html
├── style.css
└── images/
    └── images, video, and other visual assets
~~~

## Run Locally

No package installation or build step is required.

1. Clone or download the repository.
2. Open **index.html** in a browser.

For a local web server, run this command from the repository root:

~~~bash
python -m http.server 8000
~~~

Then open [http://localhost:8000](http://localhost:8000).

The externally hosted fonts, icons, and slider library require an internet connection.

## Customization

- Update destination content and page sections in **index.html**.
- Adjust layout, colors, and responsive styling in **style.css**.
- Replace or add visual assets in the **images/** directory, keeping file paths in the HTML in sync.
