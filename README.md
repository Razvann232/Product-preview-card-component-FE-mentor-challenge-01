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
- [Author](#author)

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover and focus states for interactive elements

### Screenshot

./screenshot1.png (web)
./screenshot2.png (mobile)


### Links

- Solution URL: https://github.com/Razvann232/Product-preview-card-component-challenge-on-Frontend-Mentor
- Live Site URL: https://razvann232.github.io/Product-preview-card-component-challenge-on-Frontend-Mentor/

## My process

### Built with

- HTML5
- SASS

### What I learned

I used this project specially to learn the BEM naming convention and I indend to keep using this convention
in many future projects. I learned how it works, its importance and its advantages (mainly clarity and reducing
the number of css selectors and thus improving performance).

To see how you can add code snippets, see below:

<div class="card__text">
        <header class="card__type">PERFUME</header>
        <header class="card__title">Gabrielle Essence Eau De Parfum</header>
        ...
</div>

.card {
  display: flex;

  ...
  &__image {
    height: 450px;
    width: 300px;

    content: url("../images/image-product-desktop.jpg");
  }

  &__text {
    display: flex;
    flex-direction: column;
    align-items: flex-start;

    padding: 32px;
  }

  ...
}

### Continued development

Going forward I'd like to refine and perfect this naming convention as well as overall front-end skills.

## Author

- Frontend Mentor - @Razvann232 (https://www.frontendmentor.io/profile/Razvann232)
- LinkedIn - Pinzariu Razvan (https://www.linkedin.com/in/pinzariu-razvan-98a94a205/)

