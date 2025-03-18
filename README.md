# Frontend Mentor - Testimonials grid section solution

This is a solution to the [Testimonials grid section challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/testimonials-grid-section-Nnw6J7Un7). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the site depending on their device's screen size

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- My Live Site: [My Live Site](https://isaiahp04.github.io/testimonials-grid-section)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow

### What I learned

I learned about CSS Grid

```css
main {
    display: grid;
    column-gap: 32px;
    row-gap: 24px;
    grid-template-columns: repeat(4, 1fr);
    grid-template-rows: repeat(2, auto);
    grid-template-areas: 
    "purple-card purple-card gray-card white-card-2"
    "white-card black-card black-card white-card-2";
}

.purple-card {
    grid-area: purple-card;
}
```

### Continued development

I want to keep focusing on CSS Grid.

### Useful resources

- [CSS Grid Intro and Basic Layout Tutorial for Beginners](https://www.youtube.com/watch?v=EaWj2AWI5Es) - This helped me for XYZ reason. I really liked this pattern and will use it going forward.
- [Learn CSS Grid in 20 Minutes](https://www.youtube.com/watch?v=9zBsdzdE4sM) - This is an amazing article which helped me finally understand XYZ. I'd recommend it to anyone still learning this concept.

## Author

- Frontend Mentor - [@isaiahp04](https://www.frontendmentor.io/profile/isaiahp04)


