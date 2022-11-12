# Frontend Mentor - Interactive rating component solution

This is a solution to the [Interactive rating component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/interactive-rating-component-koxpeBUmI). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
- [Author](#author)

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the app depending on their device's screen size
- See hover states for all interactive elements on the page
- Select and submit a number rating
- See the "Thank you" card state after submitting a rating

### Links

- Solution URL: [Github](https://github.com/Kevin27j/interactive-rating-component)
- Live Site URL: [Live Site](https://kevin27j.github.io/interactive-rating-component/)

## My process

### Built with

- Semantic HTML5 markup
- SASS
- Flexbox
- Mobile-first workflow
- Vanilla JavaScript

### What I learned

For this challenge I used SASS for the first time, even though it's a small project and normal CSS is best in this case.
I put in practice my knowledge of the DOM and learned some new things about JavaScript, like using the target property to get the value of a Event Listener method and assign it to a global variable like so:

```js
btn.addEventListener('click', (e) => {
  ratingValue = e.target.value;
}
```

## Author

- Frontend Mentor - [@Kevin27j](https://www.frontendmentor.io/profile/Kevin27j)
