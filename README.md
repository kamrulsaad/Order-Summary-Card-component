# Frontend Mentor - Order summary card solution

This is a solution to the [Order summary card challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/order-summary-component-QlPmajDUj). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### The challenge

Users should be able to:

- See hover states for interactive elements

### Screenshot

![](./design/desktop-preview.jpg)


### Links

- Solution URL: [Add solution URL here](https://github.com/kamrulsaad/Order-Summary-Card-component)
- Live Site URL: [Add live site URL here](https://kamrulsaad.github.io/Order-Summary-Card-component/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Tailwind CSS

### What I learned

I have learned how to use background-image property and background-size property in the best possible manner. Also I have learnt how to change the background image when the screen size changes.

```css
body{
    background-image: url('../images/pattern-background-desktop.svg');
    background-repeat: no-repeat;
    background-color: var(--pale-blue);
    background-size: contain;
}

@media all and (max-width:375px) {
    body{
        background-image: url('../images/pattern-background-mobile.svg');
    }
}
```

### Useful resources

- [Tailwind CSS](https://tailwindcss.com/) - This helped me for styling the component very easily.

## Author

- LinkedIn - [Kamrul Huda Sattari Saad](https://www.linkedin.com/in/kamrul-huda-sattari-saad-8b7454225/)
- Frontend Mentor - [@ykamrulsaad](https://www.frontendmentor.io/profile/kamrulsaad)
