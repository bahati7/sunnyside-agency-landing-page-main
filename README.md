# Frontend Mentor - Sunnyside agency landing page solution

This is a solution to the [Sunnyside agency landing page challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/sunnyside-agency-landing-page-7yVs3B6ef). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
- [Author](#author)
- [Acknowledgments](#acknowledgments)



## Overview

### The challenge

Users should be able to:

- View the optimal layout for the site depending on their device's screen size
- See hover states for all interactive elements on the page

### Screenshot

https://github.com/bahati7/sunnyside-agency-landing-page-main/blob/main/design/desktop-design.jpg

https://github.com/bahati7/sunnyside-agency-landing-page-main/blob/main/design/mobile-design.jpg

### Links

- Solution URL: https://www.frontendmentor.io/solutions/css-flexbox-and-css-grid-and-vanilla-js-QCKKqTqrT0
- Live Site URL: https://sunnyside-agency-landing-page-main-kappa.vercel.app/

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid



### What I learned

combination of css grid and flexbox for the layout



```css
.grid .row1{
    display: flex;
    justify-content: space-between;
    flex-wrap: wrap-reverse;
}
.grid .row_text{
    flex: 1 1 45rem;
    display: flex;
    flex-direction: column;
    align-items: flex-start;
    justify-content: center;
    padding: 0 10%;
    height: 50rem;
}

```

```js
let navbar=document.querySelector('.nav');

document.querySelector('#menu-btn').onclick=()=>{
    navbar.classList.toggle('active');

};
```


## Author

- Website - https://bahatiphilemon.netlify.app/
- Frontend Mentor - https://www.frontendmentor.io/profile/bahati7
- Twitter - https://twitter.com/PhilemonBahati



## Acknowledgments

Thank you to Frontend Mentor team - https://www.frontendmentor.io/