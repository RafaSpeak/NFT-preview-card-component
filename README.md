# Frontend Mentor - NFT preview card component solution

This is a solution to the [NFT preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/nft-preview-card-component-SbdUL_w0U).

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  


- [Author](#author)


## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements

### Screenshot

![](./src/images/Captura%20de%20tela.png)


### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Site URL: [Site URL here](https://www.frontendmentor.io/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid

### What I learned

These two blocks of code are responsible for styling components within an NFT card, creating an interactive and visually organized interface.

.nft-card .image-link:

Defines that the image link element has relative positioning and displays its content in a flexbox layout. This is important to control the layout of the image and ensure that other elements within the image, such as icons or hover effects, are positioned correctly.
.nft-card .info .days-left::before:

Creates a pseudo-element before the content that displays a clock icon (imported via an image). This icon is displayed inline, next to the "days-left" text, providing a visual cue of the remaining time.
The use of ::before allows the addition of an icon without needing an extra HTML element.
Relation:
Both blocks work to style different parts of the NFT card: the first organizes the layout of the main image, while the second adds a decorative icon before the text, creating a more user-friendly and intuitive interface.


```css

.nft-card .image-link {
    position: relative;
    display: flex;
}


.nft-card .info .days-left::before{
    content: '';
    background-image: url(../images/icon-clock.svg);
    background-repeat: no-repeat;
    background-position: center;
    width: 15px;
    display: inline-block;
    margin-right: 5px;
}
```

## Author

- Website - [Rafael Do Rosario](https://github.com/RafaSpeak)
- LinkedIn - [@rafaeldorosario](linkedin.com/in/rafaeldorosário)
- GitHub - [@yourusername](https://github.com/RafaSpeak)


