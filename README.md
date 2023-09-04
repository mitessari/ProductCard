# Frontend Mentor - Product preview card component solution

This is a solution to the [Product preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/product-preview-card-component-GO7UmttRfa). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover and focus states for interactive elements

### Screenshot

![](./images/Screenshot%202023-09-03%20182058.png)

### Links

- [Solution URL](https://github.com/mitessari/ProductCard)
- [Live site URL here](https://mitessari.github.io/ProductCard/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow
- CSS Media Queries

### What I learned

I have learned with this challenge how to build a responsive product card using HTML and CSS. I have learned how to make your site responsive using CSS Media Queries, I also revise subjects like padding and margin when building the css of the product card.

```css
.proud-of-this-css {
  @media (max-width: 640px) {
    img {
      content: url(image-product-mobile.jpg);
      object-fit: cover;
      width: 100%;
      height: auto;
    }

    .product-card {
      display: flex;
      flex-direction: column;
      justify-content: center;
      align-items: center;
      border-radius: 6px;
      width: 500px;
      height: auto;
    }

    .product-description {
      width: 90%;
      padding: 3rem;
    }

    h1 {
      font-size: 2.5rem;
      line-height: 40px;
    }

    p {
      font-size: 1rem;
      line-height: 1.7rem;
      font-weight: 500;
    }

    body {
      background-color: hsl(30, 38%, 92%);
      padding: 3rem;
    }
  }
}
```

### Continued development

I will continue to study the fundaments of media queries to get more confartable when using it. I also have to improve on how to change image's positions. I will continue to build diferents designs of product cards to improve even more my HTML and CSS skills.

### Useful resources

- [Media Queries](https://www.w3schools.com/css/css3_mediaqueries.asp) - This resourse helped me on how to make the product card responsive, and how to identify each screen type.
- [Learn CSS](https://www.codecademy.com/enrolled/courses/learn-css) - This course helped me understand the concepts of padding and margin which helped me to build the CSS of my product card.

## Author

- Linkedin - [Milena Zanqui](https://www.linkedin.com/in/milena-zanqui-328b17269/)
- Github - [mitessari](https://github.com/mitessari)
- Dev - [@miilexxx](https://dev.to/miilexxx)
