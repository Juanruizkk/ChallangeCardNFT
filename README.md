# Frontend Mentor - NFT preview card component solution

This is a solution to the [NFT preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/nft-preview-card-component-SbdUL_w0U). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [What I learned](#what-i-learned)
- [Author](#author)
## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements

### Screenshot

![](/preview.jpg)

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- Tailwind Css


### What I learned

This was my first project using Tailwind CSS. I learned how to create custom variables for colors and practiced using relative and absolute positioning to center the eye icon when hovering over the image.  
To achieve the hover effect, I wrapped the image and the eye icon in a parent div with `relative` positioning. The eye icon is placed inside another div with `absolute` positioning, which is initially hidden. When I hover over the image (using the `group` and `group-hover` utilities), the icon becomes visible and is centered using grid utilities. This helped me understand how to combine Tailwind classes for interactive UI effects.

## Author

- Website - [Add your name here](https://www.your-site.com)
- Frontend Mentor - [@yourusername](https://www.frontendmentor.io/profile/yourusername)
