# Frontend Mentor - Social proof section solution

This is a solution to the [Social proof section challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/social-proof-section-6e0qTv_bA). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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

- View the optimal layout for the section depending on their device's screen size

### Screenshot

[![Desktop_version](https://github.com/LidiaRJ/insure-landing-page/blob/main/screenshots/insure-landing-page-desktop.jpg)](https://github.com/LidiaRJ/insure-landing-page/blob/main/screenshots/insure-landing-page-desktop.jpg)
[![Mobile_version](https://github.com/LidiaRJ/insure-landing-page/blob/main/screenshots/insure-landing-page-mobile.jpg)](https://github.com/LidiaRJ/insure-landing-page/blob/main/screenshots/insure-landing-page-mobile.jpg)
[![Mobile_version_burger_menu](https://github.com/LidiaRJ/insure-landing-page/blob/main/screenshots/insure-landing-page-mobile-menu.jpg)](https://github.com/LidiaRJ/insure-landing-page/blob/main/screenshots/insure-landing-page-mobile-menu.jpg)

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow


### What I learned

Better understanding of element positioning within their container and the parent container. 

To see how you can add code snippets, see below:

```html
<div class="top__container">
        <div class="copy__container">
          <h1>10,000+ of our users love our products.</h1>
          <p>
            We only provide great products combined with excellent customer service.
            See what our satisfied customers are saying about our services.
          </p>
        </div>

        <div class="raitings__container">
          <div class="rating__one">
            <div class="stars">
              <img class="star__img" src="images/icon-star.svg" alt="Rating star icon.">
              <img class="star__img" src="images/icon-star.svg" alt="Rating star icon.">
              <img class="star__img" src="images/icon-star.svg" alt="Rating star icon.">
              <img class="star__img" src="images/icon-star.svg" alt="Rating star icon.">
              <img class="star__img" src="images/icon-star.svg" alt="Rating star icon.">
            </div>
            ....
```
```css
.body__container {
    display: flex;
    flex-wrap: wrap;
    max-width: 375px;
    width: 100%;
    background-image: url(images/bg-pattern-top-mobile.svg);
    background-repeat: no-repeat;
}
```



## Author

- Website - [Lidia Ruiz Jimeno](https://www.behance.net/Lidiarjimeno)
- Frontend Mentor - [@LidiaRJ](https://www.frontendmentor.io/profile/LidiaRJ)
- Github - [@LidiaRJ](https://github.com/LidiaRJ)
- Codepen - (https://codepen.io/lilyrj)