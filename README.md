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
- [Acknowledgments](#acknowledgments)


## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover and focus states for interactive elements

### Screenshot

![](./images/Screenshot%20(36).png)
![](./images/Screenshot%20(37).png)


### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- CSS Grid


**Note: These are just examples. Delete this note and replace the list above with your own choices**

### What I learned
While working on this project, I learned quite alot and it helped me to know what areas I actually didnt understand thoroughly.
I learn't:
-how to ensure an img is fit into its parent container with constant with of 100%
-how to show different images with different screen widths using media query.


To see how you can add code snippets, see below:

```html
<div class="container">
    <div>
      <img src="./images/image-product-desktop.jpg" height="300px" class="desktop" alt="perfume catalog">
      <img src="images/image-product-mobile.jpg" height="300px" class="mobile" alt="perfume catalog">
```
```css
/* image fit into parent */
 div>img{
        object-fit: cover;
        width: 100%;
        max-width: 100%;
        border-radius: 10px;
      }

/* different images for various screen widths */
       @media only screen and (max-width: 576px) {
        .container{
          display: block;
        }
        .desktop{
          display: none;
        }
        .mobile{
          display: block;
        }
      }
```




### Continued development
I want to practice more with Boostrap framework.


### Useful resources

- [Example resource 1](https://stackoverflow.com/questions/46090760/controlling-the-size-of-an-image-within-a-css-grid-layout) - This helped me to fit my image into the parent container.




## Author

- Website - [Add your name here](https://www.your-site.com)
- Frontend Mentor - [@ideeassim](https://www.frontendmentor.io/profile/ideeassim)



