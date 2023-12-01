# Frontend Mentor - Stats preview card component solution

This is a solution to the [Stats preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/stats-preview-card-component-8JqbgoU62). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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

- View the optimal layout depending on their device's screen size

### Screenshot

![](./images/desktop%20version.png)
![](./images/mobile%20version.png)


### Links

- Solution URL: [Add solution URL here]
- Live Site URL: [Add live site URL here]

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox

### What I learned

I've implemented a background overlay technique by utilizing the ::before pseudo-element on the .card-img. This method introduces a semi-transparent color filter over the background image. Also, I gained insights into adjusting opacity settings during this process.

```css
.card-img::before {
    content: "";
    position: relative;
    width: 100%;
    height: 100%;
    background-color: #7300b9;
    opacity: .5;
}
```

## Author

- Website - [@jiehlaraee](https://github.com/jiehlarae)
- Frontend Mentor - [@jiehlarae](https://www.frontendmentor.io/profile/jiehlarae)
- Twitter - [@JiehlaDacara](https://twitter.com/JiehlaDacara)