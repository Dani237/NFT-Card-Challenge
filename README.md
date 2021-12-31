This is a solution to the [NFT preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/nft-preview-card-component-SbdUL_w0U). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

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

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements

### Screenshot

![](.images/ss.png)

### Links

- Live Site URL: [Here](https://friendly-leakey-39a924.netlify.app)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow

### What I learned

I learned the way to put an overlay into a div using the opacity property and center the elements inside

```css
.view-space {
    display: flex;
    justify-content: center;
    align-items: center;
    opacity: 0;
}
.view-space:hover {
    background-color: hsl(178, 100%, 50%, 0.6);
    opacity: 1;
}
```

### Continued development

In future projects I would like to focus on the styles of a website, use methods such as flex and grid, among others.

### Useful resources

- [MDN Web Docs](https://developer.mozilla.org/en-US/docs/Web/CSS) - This helped me to check the right way to use the properties of CSS.

## Author

- Frontend Mentor - [@Dani237](https://www.frontendmentor.io/profile/Dani237)
