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

## Overview

### The challenge

Users should be able to:

- See hover states for interactive elements

### Screenshot

<img src="https://github.com/madhusmita1307/Order-Summary-Component-Main/blob/011c51f7fa95c159c6762b5dbabed4f72291b881/images/frontendchallenge1.png">


### Links

- Solution URL: (https://github.com/madhusmita1307/Order-Summary-Component-Main)
- Live Site URL: (https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid

### What I learned

Some code snippets are given below, which helped me to reinforce my knowledge:

```css

/* Learnt the @media query and how to display background pictures and colour*/

@media screen and (max-width: 1440px) {
  body {
    background-image: url("images/pattern-background-mobile.svg");
  }

  .container {
    height: 580px;
    width: 375px;
    position: absolute;
    top: 0;
    right: 0;
    bottom: 0;
    left: 0;
    margin: auto;
  }
}

@media screen and (min-width: 375px) {
  body {
    background-image: url("images/pattern-background-desktop.svg");
    background-size: cover;
  }
}

```



## Thank you.
