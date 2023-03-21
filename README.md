# Frontend Mentor - Single price grid component solution

This is a solution to the [Single price grid component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/single-price-grid-component-5ce41129d0ff452fec5abbbc). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Links](#links)
- [CSS-Grid, Span , Responsives](#my-process)
  - [CSS,HTML5](#built-with)
  - [CSS-grid ,](#what-i-learned)
  - [Div alignment's, Styling](#continued-development)
  - [MDN , web3schools](#useful-resources)
- [Mridul Garg](#author)
- [Acknowledgments](#acknowledgments)


## Overview

### The challenge

Users should be able to:

- View the optimal layout for the component depending on their device's screen size
- See a hover state on desktop for the Sign Up call-to-action

### Links

- Solution URL: [Add solution URL here]
- Live Site URL: [Add live site URL here]

## My process

### Built with

- Semantic HTML5 markup
- Flexbox
- CSS Grid

### What I learned

In this project learned about CSS-grid. Got a detailed idea about the css-grid.
and a great to use new features of media query;

To see how you can add code snippets, see below:

```html
<div class="hh lowerLeft">
 <h3>Monthly Subscription</h3>

 <p > <span>&dollar;29 </span> per month
   <br></p><p>
 Full access for less than &dollar;1 a day</p>
 <a href="https://www.google.com/" type="button" class="button" target="_blank">Sign up</a>
</div>
```
```css
section{
  height: 100vh;
  width: 100%;
  display: flex;
  align-items: center;
  justify-content: center;
  flex-direction:column;
  padding: 100px 30px;
}
.container{
  display: grid;
  grid-template-columns: 100%;
  max-width: 550px;
  margin: 0 auto;
  border-radius: 8px;
  box-shadow: 0px 0px 14px 1px #00000024;
  overflow:auto;
}
...
@media (min-width:760px) {
  .container{
    grid-template-columns: repeat(2, 1fr);
  }
  .upper{
    grid-column: 1/3;
  }
}

```

### Continued development

- Div alignment's
- Styling

### Useful resources

- [https://www.w3schools.com/css/css_grid.asp]- This helped me for understanding css grid . I really liked this pattern and will use it going forward.

## Author

- Website - [Mridul Garg](https://www.your-site.com)
- Frontend Mentor - [@Mridul07garg](https://www.frontendmentor.io/profile/Mridul07garg)
- Twitter - [@MridulG27253526](https://www.twitter.com/MridulG27253526)
- LinkenIn - [@mridul-garg-072004](https://www.linkedin.com/in/mridul-garg-072004/)


## Acknowledgments

Go for mobile(cell phone) design initially then arranging it for desktop will be a piece of cake.
