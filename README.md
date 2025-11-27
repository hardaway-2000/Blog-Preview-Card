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
- [Author](#author)

## Overview

### The challenge

Users should be able to:

- See hover and focus states for all interactive elements on the page

### Screenshot

![Screenshot%202025-11-27%20144320.png](Screenshot%202025-11-27%20144320.png)

### Links

- Solution URL: [https://github.com/hardaway-2000/Blog-Preview-Card.git](https://github.com/hardaway-2000/Blog-Preview-Card.git)
- Live Site URL: [https://hardaway-2000.github.io/Blog-Preview-Card/](https://hardaway-2000.github.io/Blog-Preview-Card/)

## My process

### Built with

- Semantic HTML5 markup
- Plain CSS
- Flexbox
- Desktop-first workflow

### What I learned

One of the main challenges I faced during this project was aligning the elements correctly. Specifically, I struggled to make the image and the text below it start from the exact same line (left alignment) to match the design.

To solve this, I used **Flexbox**, which allowed me to control the alignment of the text and images within the card container effectively.

```css
.card-content {
  display: flex;
  flex-direction: column;
  align-items: flex-start; /* This ensured everything started from the left */
}
```
