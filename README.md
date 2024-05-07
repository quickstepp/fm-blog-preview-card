# Frontend Mentor - Blog preview card solution

This is a solution to the [Blog preview card challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/blog-preview-card-ckPaj01IcS). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The Challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
- [Author](#author)

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### The Challenge

Users should be able to:

- See hover and focus states for all interactive elements on the page

### Screenshot

![Desktop View](./screenshots/screenshot-desktop.png "Desktop View")

### Links

- Solution URL: [https://github.com/quickstepp/fm-blog-preview-card/tree/main](https://github.com/quickstepp/fm-blog-preview-card/tree/main)
- Live Site URL: [https://quickstepp.github.io/fm-blog-preview-card/](https://quickstepp.github.io/fm-blog-preview-card/)

## My process

### Built with

- HMTL5
- CSS
- a little Flexbox
- a little CSS Grid

### What I learned

Align an object in the middle of the screen using grid.
```css
body {
	display: grid;
	min-height: 100vh;
	place-items: center;
}
```

Activating the hover-effect, when the curso is over the card not just the title.
```css
.card:hover {
	cursor: pointer;
    h1 {
        color: var(--yellow);
    } 
}
```

Inserting and using a custom font in HTML.
```html
<style media="screen, print">
  @font-face {
    font-family: "Figtree";
    src: url("./assets/fonts/Figtree-VariableFont_wght.ttf");
}
</style>
```

## Author

- Frontend Mentor - [@quickstepp](https://www.frontendmentor.io/profile/quickstepp)