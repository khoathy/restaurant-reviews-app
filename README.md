# Restaurant Reviews App

## Project Overview

This project is to convert a static design that lacks accessibility to a web application that is responsive on all displays and accessible for screen reader use.

The starter code (https://github.com/udacity/mws-restaurant-stage-1) has a lot of issues. It is barely usable on a desktop browser, much less a mobile device. It also doesn’t include any standard accessibility features, and it doesn’t work offline at all. The project is to resolve these issues while still maintaining the included functionality.

Besides, service worker is to be added to begin the process of creating a seamless offline experience for users.


## Features

- The site fully responsive. All of the page elements is usable and visible in any viewport, including desktop, tablet, and mobile displays. Page elements should wrap when the viewport is too small to display them side by side.

- The site is made accessible. Alt attributes are present and descriptive for images. Add screen-reader-only attributes when appropriate to add useful supplementary text. Use semantic markup where possible, and aria attributes when semantic markup is not feasible.

- Cache the static site for offline use. Using Cache API and a ServiceWorker, cache the data for the website so that any page (including images) that has been visited is accessible offline.


## How to run the app

Clone or download this repo.

Extract and open the folder.

From inside the new directory, launch a local client server using Python from your terminal:
- Python 2: python -m SimpleHTTPServer 8000
- Python 3: python3 -m http.server 8000

Visit the site in your browser at http://localhost:8000


