# Frontend Mentor - Order summary card solution

This is a solution to the [Order summary card challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/order-summary-component-QlPmajDUj). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

## Overview

### The challenge

Users should be able to:

- See hover states for interactive elements

### Screenshot

![Mobile](./public/assets/images/mobile-screenshot.jpeg)
![Desktop](./public/assets/images/desktop-screenshot.jpeg)

### Links

- Solution URL: [Solution on GitHub](https://github.com/horoserp/order-summary)
- Live Site URL: [Live Site](https://horoserp.github.io/order-summary)

## My process

### Built with

- Semantic HTML5 markup
- CSS variables
- Flexbox

### What I learned

This coding challenge reinforced the value of using Flexbox and using Semantic HTML when creating a site. I continue to implement the :where pseudo selector and the media query (hover:hover) wherever possible.

```css
:where(h1, .content > p, .plan-container, .button) {
  margin-bottom: 20px;
}

@media (hover: hover) {
  .change,
  .button,
  .cancel {
    cursor: pointer;
  }
}
```

### Continued development

- I would love to embark on a more in-depth exploration of the CSS box-shadow property.

### Useful resources

- [W3Schools](https://www.w3schools.com/) - This is a great reference site which helped me remember some of the required syntax.
- [Stack Overflow](https://stackoverflow.com/) - This is an excellent resource for finding answers to precise questions.

## Author

- Website - [Robert P. Horosewski](https://horoserp.github.io/React-Portfolio)
- Frontend Mentor - [@horoserp](https://www.frontendmentor.io/profile/horoserp)
- LinkedIn - [Robert P. Horosewski](https://www.linkedin.com/in/robert-horosewski-8a0608196/)

## Acknowledgments

Thanks to my wife for the encouragement to pursue my dream.
