# Frontend Mentor - 3-column preview card component solution

This is a solution to the [3-column preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/3column-preview-card-component-pH92eAR2-). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
- [Author](#author)

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements

### Screenshot

![](./screenshot3.jpg)


### Links

- Live Site URL: [page web](https://candid-crumble-c5cf03.netlify.app/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid

### What I learned

I learned to use the display grid better depending on the size of the screen.

```css
.container {
        display: grid;
        grid-template-columns: repeat(3, 1fr );
        grid-template-rows: repeat(1, 400px);
        place-content: center;
        max-width: 840px;
        margin: 120px auto;
    }
```


## Author

- Website - [Add your name here](https://www.your-site.com)
- Frontend Mentor - [@IsGhost19](https://www.frontendmentor.io/profile/isghost19)

