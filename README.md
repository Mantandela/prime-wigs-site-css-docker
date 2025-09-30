# Prime Wigs Enterprise Website 

A 4-page responsive website for **Prime Wigs Enterprise**, styled with modern **CSS3 features** and packaged into a **Docker container** for easy deployment.  
This project demonstrates **design tokens, responsive layouts, accessibility, and containerization** best practices.

## Project Overview
The website includes:
- **Home Page** → Hero section, collections, customer promise, and flip-card facts.
- **About Page** → History, values, services, and key wig terms.
- **Media Page** → Image gallery, product videos, and audio testimonials.
- **Extras Page** → Tables, interactive HTML5 elements, and customer highlights.
  
## Design Decisions
# Palette:
- Primary color: Soft pink (hsl(337, 62%, 63%)) – conveys elegance and femininity.
- Accent color: Light rose (hsl(342, 38%, 91%)) – used for highlights and section backgrounds.
- Neutral tones: Black (hsl(0, 0%, 7%)) for text and white for contrast.
- The palette was chosen to balance luxury, beauty, and readability.
  
# Type Scale:
- Heading 1 (H1): 2.2rem desktop → 1.8rem mobile
- Heading 2 (H2): 1.8rem desktop → 1.6rem mobile
- Heading 3 (H3): 1.4rem desktop → 1.2rem mobile
- Body text: 1rem (16px base).
- Fonts: Playfair Display (headings) + Lora (body text) for a professional, modern feel.
- 
# Spacing Scale
- Consistent spacing tokens defined in CSS variables:
--space-1: 0.25rem
--space-2: 0.5rem
--space-3: 1rem
--space-4: 1.5rem
--space-5: 2rem

# Accessibility Notes
- Contrast Choices: Pink + black palette tested to ensure readability against light backgrounds.
- Focus Styles: Links and buttons have visible outlines for keyboard navigation.
- Reduced Motion Handling: Card flip animation disabled for users with prefers-reduced-motion enabled.
- Skip to Content Link: Allows screen reader and keyboard users to bypass navigation.
- Semantic HTML5 Elements: header, main, section, article, aside, footer used appropriately.

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



