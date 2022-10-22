# frontendmentor
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

This is a simple product landing page that offers a simple description of the product and the price tag. It is a combination of different HTML and CSS components 
integrated to create a visually appealing concept for a potential client.

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover and focus states for interactive elements

### Screenshot

Desktop View
![](.product-preview-card-component-main\screenshots\desktop.png)
![](.product-preview-card-component-main\screenshots\Viewpoint 375px.png)


### Links

- Live Site URL: (https://perfume-chanel.netlify.app/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox

### What I learned

With the HTMLand CSS concepts I had previously learned, this challenge was a chance to brush on some of the concepts that I had learned some time ago. However, creating 
a breakpoint of 375px was a new experience that also built on my css skills and knowledge.

To achieve the 375px viewpoint, I used this css property:

```css
.flex-items{
        background-image: url("/images/image-product-mobile.jpg");
        background-size: 100%;
        height: 300px;
        width: 100%;
        background-repeat: no-repeat;
        border-radius: 10px;
    }

    .flex-items1{
        position: absolute;
        top: 45%;
        width: 290px;
    }
```


### Continued development

In future developments, I am eager to learn more about display properties, using grids and understand how javascript and bootstrap libraries could have helped accomplish 
the same outcome.

### Useful resources

- [Resource 1](https://www.w3schools.com/cssref/pr_class_display.asp) - This is one of the favourite resources I use. It helped me learn and define the different display properties for the different breakpoints in the challenge.

## Author

- Website - [Elvis Odhiambo](https://lvohs.netlify.app/index.html)
- Frontend Mentor - [@Lvoh901](https://www.frontendmentor.io/profile/Lvoh901)
- Twitter - [@LvohOdhis](https://twitter.com/LvohOdhis)
