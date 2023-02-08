# Boolean Academy - Boolando Products Details
This is a solution to the exercice of - Classe #92 - 08 Febbraio 2023.


## Table of contents

- [Overview](#overview)
  - [The exercice](#the-exercice)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Useful resources](#useful-resources)


## Overview

### The exercice

Students should be able to:

- View the optimal layout for the website using CSS Flexbox and Position (Absolute and Relative)
- Set up the hover state on the products card

### Screenshot
Below is how the page should looks like

![Page](./boolando.png)
![Hover state](./boolando_hover.png)

### Links

- Solution URL: [https://github.com/filecc/htmlcss-discord](https://github.com/filecc/htmlcss-discord)
- Live Site URL: [https://filecc.github.io/htmlcss-discord/](https://filecc.github.io/htmlcss-discord/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox

### What I learned

We were required to use Flexbox (with no media query and no other framework). I have create some usueful class, like bootstrap, to helmp me in the process.


```html
<!-- links -->
<ul class="d-flex align-center">
  <li>Scarica</li>
  <li>Perché Discord</li>
  <li>Nitro</li>
  <li>Sicurezza</li>
  <li>Assistenza</li>
</ul>
<!-- /links -->
```
```css
.d-flex{
    display: flex;
    flex-flow: row wrap;
}

.align-center{
    align-items: center;
}
```

### Useful resources

- [Change SVG color in CSS ](https://codepen.io/sosuke/pen/Pjoqqp) - This helped me for the ability to change the color of the svg waves between sections. The Codepen use CSS properties to apply to SVG targeting the desidered color. 

```html
<!-- wave decoration -->
     <div aria-label="hidden" id="wave"></div>
<!-- /wave decoration -->
```
```css
#wave::after{
    display: block;
    font-size: 0;
    content: url('../img/wave.svg');
    filter: invert(100%) sepia(8%) saturate(1%) hue-rotate(169deg) brightness(115%) contrast(93%);
}
```
