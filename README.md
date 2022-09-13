# Frontend Mentor - Clipboard landing page solution

This is a solution to the [Clipboard landing page challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/clipboard-landing-page-5cc9bccd6c4c91111378ecb9). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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

- View the optimal layout for the site depending on their device's screen size
- See hover states for all interactive elements on the page

### Screenshot

# Mobile Preview

![screenshot](https://github.com/romila2003/Clipboard-landing-page/blob/main/mobile%20preview.PNG)

# Desktop Preview 

![screenshot](https://github.com/romila2003/Clipboard-landing-page/blob/main/desktop%20preview.PNG)

### Links

 - Source code: [https://github.com/romila2003/Clipboard-landing-page](https://github.com/romila2003/Clipboard-landing-page)
 - Live website: [https://romila-clipboard-landing-page.netlify.app/](https://romila-clipboard-landing-page.netlify.app/)

## My process

### Built with

- Semantic HTML5 markup
- SASS (SCSS)
- Flexbox
- Grid
- Mobile-first workflow

### What I learned

This project really tested my layout skills since I felt quite nervous to take up a HTML and CSS challenge that requires creating a web layout. Also, I learned more about `clip-path` and the `filter` properties which became very useful for the image and the social media icons. I feel confident with my recreation of the design from scratch however the `:hover` effect of the button seems too light and was not sure of the right opacity however overall, I think I did well.

Clip-path:

```css

@media (min-width: 830px) {
  position: relative;
  left: -5%;
  clip-path: inset(0 0 0 5%);
}

```
Filter:

```css

.icon:hover {
  filter: invert(57%) sepia(82%) saturate(387%) hue-rotate(121deg) brightness(92%) contrast(88%);
}

```


### Continued development

For future developments, I want to continue making responsive web layouts and feel more confident with it. Also, I want to implement more JS into my work such as a nav-bar.


## Author

- Frontend Mentor - [@romila2003](https://www.frontendmentor.io/profile/romila2003)
- Twitter - [@romila003](https://www.twitter.com/romila003)

