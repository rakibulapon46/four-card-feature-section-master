# Frontend Mentor - Four card feature section solution

This is a solution to the [Four card feature section challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/four-card-feature-section-weK1eFYK). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
- [Author](#author)

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the site depending on their device's screen size

### Screenshot

![](./design/desktop-design.jpg)
![](./design/mobile-design.jpg)

### Links

- Solution URL: [Source code](https://github.com/rakibulapon46/four-card-feature-section-master)
- Live Site URL: [Live demo](https://rakibulapon46.github.io/four-card-feature-section-master/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- CSS Grid
- Mobile responsive

### What I learned

Use this section to recap over some of your major learnings while working through this project. Writing these out and providing code samples of areas you want to highlight is a great way to reinforce your own knowledge.

To see how you can add code snippets, see below:

```css
.card_section {
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  gap: 30px;
  place-items: center;
}

.card:nth-child(1) {
  grid-row: 2/4;
}
.card:nth-child(2) {
  grid-row: 1/3;
  grid-column: 2/3;
}
.card:nth-child(3) {
  grid-row: 3/5;
  grid-column: 2/3;
}
.card:nth-child(4) {
  grid-row: 2/4;
}
```
### Continued development

Use this section to outline areas that you want to continue focusing on in future projects. These could be concepts you're still not completely comfortable with or techniques you found useful that you want to refine and perfect.


## Author

- Github - [rakibulapon46](https://github.com/rakibulapon46)
- Frontend Mentor - [@rakibulapon46](https://www.frontendmentor.io/profile/rakibulapon46)
- Facebook - [rakibul.apon79](https://www.facebook.com/rakibul.apon79)