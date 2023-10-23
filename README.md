# Frontend Mentor - QR code component solution

This is a solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)

## Overview

Challenge was to build out the QR code component and get it looking as close to the design as possible.

### Screenshot

![](./Screenshot-QR-code-component.png)

### Links

- Solution URL: (https://github.com/Gunner40/QR-code-component/)
- Live Site URL: [[Add live site URL here](https://gunner40.github.io/QR-code-component/)](https://gunner40.github.io/QR-code-component/)

## My process

Stidy design and plan the html structure and class names. Build the HTML first followed by the CSS and use best judgement on magins and paddings. Use custom variables attained from the style guide.

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow

### What I learned

The css calc function must have a space between the operator. So width: calc(375px - 4em); will work but width: calc(375px -4em); will not.

```css
.card {
  width: calc(375px - 4em);
}
```

### Continued development

I need to start using css grid on future challenges. I also need to revise React and start using that too.

### Useful resources

- [Example resource 1](https://www.w3schools.com/) - Great resource.

## Author

- Frontend Mentor - [@Gunner40](https://www.frontendmentor.io/profile/Gunner40)
