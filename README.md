# Frontend Mentor - QR code component solution

This is a solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview]
  - [Screenshot]
  - [Built with]
  - [What I learned]
- [Author]
- [Acknowledgments]

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

Excellent project to put into practice basic knowledge.

### Screenshot

![](./images/meu-QR.jpg)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- CSS Grid


### What I learned

through an example of a colleague learns to use the variables to define values of colors and font I was also able to solve the difficulty to center the automatic height using the "height" and I improved my semantics by adjusting my css style in a more optimized way

:root{
    --White: hsl(0, 0%, 100%);
    --LightGray: hsl(212, 45%, 89%);
    --GrayishBlue: hsl(220, 15%, 55%);
    --DarkBlue: hsl(218, 44%, 22%);
    --fw-bold:700;
    --fw-regular :400
}
body {
    font-family: Outfit;
    margin: 0;
    padding: 0; 
    height: 100vh;
    background-color: var(--LightGray);
}
.container {
    display: grid;
    grid-auto-flow: column;
    grid-auto-columns: 1fr;
    justify-content: center;
    align-items: center; 
    height: 100%;
}


## Author

https://github.com/danilosilvamg
https://www.frontendmentor.io/profile/danilosilvamg

## Acknowledgments

Through the solution of the colleague managed to solve my difficulties thank you.
https://www.frontendmentor.io/profile/abdallahifox
