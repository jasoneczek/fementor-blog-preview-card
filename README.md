# Frontend Mentor - Blog preview card solution

This is a solution to the [Blog preview card challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/blog-preview-card-ckPaj01IcS). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Useful resources](#useful-resources)
- [Author](#author)

## Overview

### The challenge

Users should be able to:

- See hover and focus states for all interactive elements on the page

### Screenshots

![](/assets/images/screenshot.png)

![](/assets/images/screenshot-active.png)

### Links

- Solution URL: [My solution on my Frontend Mentor profile](https://www.frontendmentor.io/solutions/blog-preview-card-with-fluid-text-sizes-4TxTONa4OE)
- Live Site URL: [Live](https://fementor-blog-preview-card-kohl.vercel.app/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow

### What I learned

In creating this project I gained some valuable CSS skills and insights into best practices. Here are some key takeaways:

Custom Fonts with `@font-face`

- Utilized @font-face to incorporate custom fonts (Figtree) into the project, specifying different weights (500 and 800) for various text elements.

CSS Variables and Typography

- Employed CSS variables (`--clr-primary`, `--fw-reg`, etc.) for consistent color schemes and typography throughout the project.
- Utilized `clamp()` for responsive typography `--fs-sml`, --`fs-md`, `fs-lg` ensuring readability across different screen sizes.

Accessibility and User Interaction

- I employed the pseudo-element `::before` on the anchor `<a>` tag within the card header to extend the clickable area of the card while maintaining semantic HTML structure and accessibility.
- I incorporated a hover effect using the `:hover` pseudo-class on the card header, enhancing user interaction by providing visual feedback when users hover over the elements.

### Useful resources

- [Stop Making This BIG Mistake With Clickable Cards](https://www.youtube.com/watch?v=nM78am-FC9Q) - This YouTube video helped me understand how important it is to properly link clickable content for accessibilty.
- [Inclusive Components - Cards](https://inclusive-components.design/cards/) - This article beautifully explains how to make an entire card clickable properly and have hover/focus states.
- [This YouTube video by Kevin Powell](https://inclusive-components.design/cards/) demonstrates the min(), max(), and clamp() CSS functions, which helped me with responsive font sizes.
- [Supercharged CSS Variables](https://open-props.style/#typography) - Another site worth bookmarking for reference.

## Author

- Github - [@jasoneczek](https://github.com/jasoneczek)
- Frontend Mentor - [@jasoneczek](https://www.frontendmentor.io/profile/jasoneczek)
