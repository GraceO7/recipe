# Frontend Mentor - Recipe page solution

This is a solution to the [Recipe page challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/recipe-page-KiTsR8QQKm). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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

### Screenshot

![](./my%20design/desktop-design.jpeg)
![](./my%20design/mobile.jpeg)

### Links

- Solution URL: (https://graceo7.github.io/recipe)
- Live Site URL: (https://recipeetemp.netlify.app/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flex
- CSS Grid
- Mobile-first workflow


### What I learned
During this challenge, I learned how to:

Structure a recipe page with semantic HTML.
Use CSS custom properties for better maintainability.
Implement responsive design using media queries.
Style elements to match the provided design.


```html
<h1>Simple Omelette Recipe</h1>
<p>An easy and quick dish, perfect for any meal. This classic omelette combines beaten eggs cooked to perfection, optionally filled with your choice of cheese, vegetables, or meats.</p>

```
```css
css

:root {
   --primary-color1: hsl(14, 45%, 36%);
    --primary-color2: hsl(332, 51%, 32%);
   
}
/* centering a div container */
body {
  background-color: var(--color-3);
  display: grid;
  place-items: center;
  font-family: var(--font-family2);
}
/* styling a list-style-type */
.instructions ol li::marker{
    color: var(--primary-color1);
    font-weight: 700;
    font-size: 1em;
    padding-right: 10px
}


```



### Continued development

In future projects, I aim to:

Explore more advanced CSS techniques.
Implement JavaScript to add interactivity to the page.
Continue improving my responsive design skills.


### Useful resources
MDN Web Docs - Comprehensive documentation for web development.
CSS-Tricks - A great resource for CSS techniques and tutorials.


## Author

- Website - [ojeyemi opeyemi](https://recipeetemp.netlify.app/)
- Frontend Mentor - [@GraceO7](https://graceo7.github.io/recipe)
- Twitter - [@Gracie_coder](https://www.twitter.com/@Gracie_coder)

## Acknowledgments
This project was inspired by the Recipe Page challenge on Frontend Mentor. Special thanks to the Frontend Mentor community for their support and feedback.

