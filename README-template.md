# Frontend Mentor - Product preview card component solution

This is a solution to the [Product preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/product-preview-card-component-GO7UmttRfa). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Desktop](#desktop)
  - [Mobile](#mobile)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
- [Author](#author)


## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover and focus states for interactive elements

### Screenshot

### Desktop

![Solution (Desktop)](/screenshot.png)

### Mobile

![Solution (Mobile)](/screenshot2.png)

### Links

- Solution URL: [https://github.com/sajia-h/product-preview-card-component.git]
- Live Site URL: [https://sajia-h.github.io/product-preview-card-component/]

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow

### What I learned

I learned how to optimise screens for certain widths. The following CSS made it possible to manipulate the image and text of the product card when the screen is smaller than 601px;

```css
@media only screen and (max-width: 601px) {
  body {
    padding: 20px;
    height: auto;
  }
  .product-preview-card {
    flex-direction: column;
    width: 100%;
  }
  .product-img img {
    width: 100%;
    border-top-right-radius: 12px;
    border-bottom-left-radius: 0px;
  }
  .attribution {
    position: relative;
    bottom: unset;
    margin-top: 20px;
  }
}
```
I also learned how to use '<source>' to set min and max widths of an image using HTML:

```html
 <source
          media="(min-width: 601px)"
          srcset="./images/image-product-desktop.jpg">
```

### Continued development

I still need to consolidate mobile-first workflow and better understand how to using ```css @media only screen ```

## Author

- Website - [Sajia](Coming soon)
- Frontend Mentor - @sajia-h