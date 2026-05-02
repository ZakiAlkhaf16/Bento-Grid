# Frontend Mentor - Bento Grid Solution

This is a professional solution to the [Bento grid challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/bento-grid-RMydElrlOj). This project focuses on building a highly responsive layout using modern CSS techniques while maintaining accessibility standards.

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [UI/UX Accuracy](#uiux-accuracy)
- [Author](#author)

## Overview

### The challenge

The goal was to replicate the Bento Grid design, ensuring:
- Optimal layout across all device sizes (Mobile, Tablet, Desktop).
- Semantic HTML for better SEO and screen reader support.
- Compliance with WCAG accessibility guidelines, specifically regarding contrast and logical reading order.

### Links

- **Solution URL:** [GitHub Repository](https://github.com/ZakiAlkhaf16/Bento-Grid)
- **Live Site URL:** [GitHub Pages Demo](https://zakialkhaf16.github.io/Bento-Grid/)

## My process

### Built with

- **Semantic HTML5:** Ensuring a structured and accessible document.
- **CSS Custom Properties:** For efficient theme and spacing management.
- **CSS Grid:** Used for the main layout structure and `grid-template-areas` for responsiveness.
- **Flexbox:** Implemented for internal alignment within individual cards.
- **Mobile-first Workflow:** Developing for smaller screens first to ensure performance and clarity.

### What I learned

This project was a great opportunity to master **CSS Grid Layout**. I focused on how to manipulate the grid flow between mobile and desktop without altering the DOM structure, which is crucial for both performance and accessibility.

**Key Technical Takeaway:**
Using `grid-template-areas` allowed me to completely rearrange the layout for mobile users (as seen in `mobile-design.jpg`) while keeping the HTML code clean and logical for screen readers.

### UI/UX Accuracy

To master the content inside the cards and match the design precisely:
1. **Nested Layouts:** I treated each grid item as a flex container to center text and position icons.
2. **Overflow Control:** Used `overflow: hidden` on cards with partial images (like the Schedule card) to ensure they crop correctly according to the design.
3. **Responsive Typography:** Adjusted font sizes using variables to maintain readability on smaller screens.

## Author

- **Zaki Al-Khalaf** - [Frontend Developer](https://github.com/ZakiAlkhaf16)
- **Frontend Mentor:** [@ZakiAlkhaf16](https://www.frontendmentor.io/profile/ZakiAlkhaf16)