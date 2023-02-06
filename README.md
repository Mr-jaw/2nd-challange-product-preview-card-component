# Frontend Mentor - Product preview card component solution

This is a solution to the [Product preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/product-preview-card-component-GO7UmttRfa). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Useful resources](#useful-resources)
- [Author](#author)


**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview


### Screenshot

![](./screenshot.jpg)

### Links

- Live Site URL: [Live Site](https://taupe-kitten-d86f52.netlify.app/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow

### What I learned

Using grid to get more flexible position of elements

```css
  .card {
    display: grid;
    grid-template-columns: 1fr 1fr;
    background-color: var(--white);
    border-radius: .6em;
    max-width: 40em;
}
```

Usage of media queries

```css
@media (max-width: 40em) {

    .card {
        grid-template-columns: 1fr;
        max-width: 22em;
        margin: 1em;
    }

    .card h1 {
        margin-top: 0;
    }

    .card h2 {
        margin: .4em 0;
    }

    .img-mobile {
        display: block;
        max-width: 100%;
        border-radius: .6em .6em 0 0
    }

    .img-desktop {
        display: none;
    }

}
```


### Useful resources

- [Stackoverflow solution](https://stackoverflow.com/a/27853917) - This helped me to understand how to swap different images for different screen sizes

## Author

- Frontend Mentor - [@Mr-jaw](https://www.frontendmentor.io/profile/Mr-jaw)

