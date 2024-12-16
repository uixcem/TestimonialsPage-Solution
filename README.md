# Frontend Mentor - Testimonials Grid Section Solution

This is a solution to the [Frontend Mentor Testimonials Grid Section](https://www.frontendmentor.io/challenges/testimonials-grid-section-Nnw6J7Un7) challenge. Frontend Mentor challenges help improve coding skills by building realistic projects.

## Table of Contents

- [Overview](#overview)
- [The Challenge](#the-challenge)
- [Screenshot](#screenshot)
- [Links](#links)
- [My Process](#my-process)
- [Built With](#built-with)
- [What I Learned](#what-i-learned)

## Overview

### The Challenge

Users should be able to:

- View the optimal layout for the testimonials grid based on their device's screen size
- See hover and focus states for interactive elements

### Screenshot

![Desktop View](./design/desktop-design.jpg)
![Mobile View](./design/mobile-design.jpg)

### Links

- Live Site URL:[View](https://testimonialpagesolution.netlify.app)
- Solution URL: [View](https://github.com/uixcem/TestimonialsPage-Solution)

## My Process

### Built With

- Semantic HTML5 markup
- SCSS/SASS
- CSS Grid
- Flexbox
- Mobile-first workflow
- BEM Methodology

### What I Learned

- Using SCSS mixins for responsive design:

```scss
@mixin responsive($breakpoint) {
  @if $breakpoint == tablet {
    @media (min-width: 376px) and (max-width: #{$breakpoint-desktop - 1px}) {
      @content;
    }
  }
}
```
