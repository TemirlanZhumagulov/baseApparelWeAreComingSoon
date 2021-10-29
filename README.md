# Frontend Mentor - Base Apparel coming soon page solution

This is a solution to the [Base Apparel coming soon page challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/base-apparel-coming-soon-page-5d46b47f8db8a7063f9331a0). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Useful resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)


## Overview

### The challenge

Users should be able to:

- View the optimal layout for the site depending on their device's screen size
- See hover states for all interactive elements on the page
- Receive an error message when the `form` is submitted if:
  - The `input` field is empty
  - The email address is not formatted correctly

### Screenshot

![](./screenshot.png)

### Links

- Solution URL: (https://www.frontendmentor.io/solutions/base-apparel-coming-soon-page-zhumagulov-temirlan-m6gvlNq4x/)
- Live Site URL: (https://temirlanzhumagulov.github.io/baseApparelWeAreComingSoon/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- [React](https://reactjs.org/) - JS library
- [Next.js](https://nextjs.org/) - React framework
- [Styled Components](https://styled-components.com/) - For styles

### What I learned

```css
input::placeholder {
    color: hsl(0, 36%, 70%);
```
```js
form.addEventListener("submit", (e) => {
    if (email.validity.typeMismatch) {
        e.preventDefault();
        dangerIcon.style.opacity = 1;
        dangerText.style.opacity = 1;
    } else {
        dangerIcon.style.opacity = 0;
        dangerText.style.opacity = 0;
    }
})
```

### Useful resources

- [W3SCHOOLS](https://www.w3schools.com/js/) - This helped me for writing data validations to check if the email input is correct. I really liked this and will use it going forward.
- [W3SCHOOLS](https://www.w3schools.com/css/default.asp) - it helped me remember how to use different properties of CSS. I'd recommend it to anyone.

## Author

- Website - [Temirlan Zhumagulov and Aisha Buasheva](https://www.your-site.com)
- Frontend Mentor of Temirlan - [@TemirlanZhumagulov ](https://www.frontendmentor.io/profile/TemirlanZhumagulov)
- Frontend Mentor of Aisha - [@Aisbv2](https://www.frontendmentor.io/profile/Aisbv2)

## Acknowledgments

I am grateful to my classmate for participating in coding, thereby greatly facilitating the task.
