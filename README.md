# Frontend Mentor - NFT preview card component solution

This is a solution to the [NFT preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/nft-preview-card-component-SbdUL_w0U).

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Link](#link)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
- [Author](#author)

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements

### Screenshot

![](../nft-preview-card-component/src/images/screeshot-desktop.png)

### Link

- [Live Site URL](https://carolinaciolin.github.io/nft-preview-card/)

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Pseudo-elements


### What I learned

In this project, I used pseudo-elements for the first time. I applied them to add icons directly in the style and to create two different hover effects for the link on the main image.


```html
      <div class="info">
        <p class="quantidade">0.041 ETH</p>
        <p class="days-left">3 days left</p>
      </div>
```
```css
.info .quantidade{
    color: var(--cyan);
    font-size: 12px;
    font-weight: 600;
    display: flex;
    align-items: center;
}

.info .quantidade::before{
    content: '';
    background-image: url('../images/icon-ethereum.svg');
    background-repeat: no-repeat;
    background-position: center;
    display: inline-block;
    width: 11px;
    height: 20px;
    margin-right: 5px;
}
```

## Author

- Frontend Mentor - [@carolinaciolin](https://www.frontendmentor.io/profile/CarolinaCiolin)
- LinkedIn - [Carolina Ciolin](https://www.linkedin.com/in/carolinaciolin/)