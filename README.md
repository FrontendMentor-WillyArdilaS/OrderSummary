# Frontend Mentor - QR code component solution

This is a solution to the [Order summary card challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/order-summary-component-QlPmajDUj).

## Table of contents

  - [Overview](#overview)
    - [Screenshot](#screenshot)
    - [Links](#links)
  - [My process](#my-process)
    - [Built with](#built-with)
    - [What I learned](#what-i-learned)
    - [Useful resources](#useful-resources)
  - [Author](#author)

## Overview

### Screenshot

![](https://i.imgur.com/1CJSpOM.png "Screenshot")

### Links

- Live site URL: https://cutt.ly/1GfbgKf

## My process

### Built with

- HTML
- CSS (Flexbox)

### What I learned

Use variables in the root element to avoid repeating an element too much

```css
:root {
    --pale-blue: hsl(225, 100%, 94%);
    --dark-blue: hsl(223, 47%, 23%);
    --bright-blue: hsl(245, 75%, 52%);
}
```

Use of media queries for responsive changes in mobile design

```css
@media (max-width:375px) {
    body {
        background-image: url('Images/Pattern-Background-Mobile.svg');
        background-size: 100vw 25vh;
    }

    .orderSummary {
        width: 85%;
    }
}
```

### Useful resources

- [FreeCodeCamp](https://www.freecodecamp.org/learn/)

## Author

- Frontend Mentor - [@WilliamArdilaS](https://www.frontendmentor.io/profile/WilliamArdilaS)
- Twitter - [@W_A_A_S_](https://twitter.com/W_A_A_S_)
