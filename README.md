# Prime Wigs Enterprise Website 

A 4-page responsive website for **Prime Wigs Enterprise**, styled with modern **CSS3 features** and packaged into a **Docker container** for easy deployment.  
This project demonstrates **design tokens, responsive layouts, accessibility, and containerization** best practices.

## Project Overview
The website includes:
- **Home Page** → Hero section, collections, customer promise, and flip-card facts.
- **About Page** → History, values, services, and key wig terms.
- **Media Page** → Image gallery, product videos, and audio testimonials.
- **Extras Page** → Tables, interactive HTML5 elements, and customer highlights.

## Features

## CSS3 Styling
- **Design Tokens:** CSS variables for colors, fonts, and spacing.
- **Typography:** Playfair & Lora Google Fonts, semantic HTML elements (`code`, `kbd`, `mark`, etc.).
- **Layout:** Flexbox and CSS Grid for header, sections, and footer.
- **Components:** 
  - Flip card (front & back facts).
  - Styled tables for schedules.
  - Responsive images, audio, and video.
- **Utilities:** Reusable spacing & alignment helpers.
- **Animations & States:** Hover effects, transitions, and reduced-motion support.
- **Accessibility:** Skip links, ARIA labels, semantic tags, and focus indicators.

## Responsiveness
- **Mobile-first design** with breakpoints at:
  - 480px (small screens)
  - 768px (tablets)
  - 1024px (desktops)

## Dockerization
The site is containerized using Docker for consistent deployment.

## Dockerfile (simplified)
# Building the Docker image
docker build -t primewigs .
# Running the container
docker run -p 8080:80 primewigs
# Exposed port was port 8080
## Live Demo
GitHub Pages: https://mantandela.github.io/prime-wigs-site-css-docker/
Docker Hub Image: https://hub.docker.com/repository/docker/delmantan48/html5-css3-site/tags/lab2



