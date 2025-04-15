# Frontend Mentor - Blog preview card solution

This is a solution to the [Blog preview card challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/blog-preview-card-ckPaj01IcS). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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

## Overview

### The challenge

Users should be able to:

- See hover and focus states for all interactive elements on the page

### Screenshot

![](./screenshots/desktop%20screenshot.png)

### Links

- Solution URL: [Solution repo](https://github.com/giannindm/blog-preview-card)
- Live Site URL: [Live site](https://giannindm.github.io/blog-preview-card/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow

### What I learned

- How to use `overflow:hidden` to mask the corner radius of images contained with in a div.
- Writing code snippets in markdown.
- Creating hover states
- Using media queries to create mobile and desktop versions

### Continued development

I want to continue learning about media queries and how to build responsive designs. Additionally, I had some trouble zooming in the image on the mobile design, so I have to look further into that. I decided not to bother with it for now.

I also had trouble aligning the card in the center of the page vertically using Flexbox. I tried adding the following to the parent element of the card:
```css
body {
  display: flex;
  justify-content: center;
  align-items: center;
}
```

However, it always just centered the content horizontally and did not add any vertical spacing above the card. Not sure why this kept happening.

### Useful resources

- [Markdown Guide](https://www.markdownguide.org/basic-syntax/) - This helped me write parts of this README.md file in markdown.
