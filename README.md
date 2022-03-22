# Frontend Mentor - Huddle landing page with single introductory section solution

This is a solution to the [Huddle landing page with single introductory section challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/huddle-landing-page-with-a-single-introductory-section-B_2Wvxgi0). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Frontend Mentor - Huddle landing page with single introductory section solution](#frontend-mentor---huddle-landing-page-with-single-introductory-section-solution)
  - [Table of contents](#table-of-contents)
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

- View the optimal layout for the page depending on their device's screen size
- See hover states for all interactive elements on the page

### Screenshot

![](./images/Screenshot.png)



### Links

- Solution URL: [Github](https://github.com/L1m1tz/Huddle-landing-page)
- Live Site URL: [Github-pages](https://l1m1tz.github.io/Huddle-landing-page/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow

### What I learned
In this challange i've learned how to build a website using the mobile first workflow.
futher learned how to alighn grids more effeciently

```html
 <div class="card grid">
```
```css
.grid {
    display: grid;
    grid-template-columns: repeat(12, 1fr);
    gap: 10px;
}

.image {
    grid-column: 2/12;
}

.huddle-text {
  
    grid-column: 2/12;  
}
```


### Continued development

i will continue my challanges using mobile-first workflow. 
i have yet to understand the placement of background images, thus i shall continue to learn more about image placement.


### Useful resources

- [Mobile-first workflow](https://www.youtube.com/playlist?list=PL4cUxeGkcC9hH1tAjyUPZPjbj-7s200a4) - This was a huge help guiding me through the process of mobile first work flow.

## Author

- Website - [Andrewmk](https://github.com/L1m1tz)
- Frontend Mentor - [@L1m1ts](https://www.frontendmentor.io/profile/L1m1tz)

