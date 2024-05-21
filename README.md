# Frontend Mentor - QR code component solution

This is a solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
- [Author](#author)


## Overview

### Screenshot

![](./images/screenshot-desktop.png)

### Links

- Solution URL: [Add solution URL here](https://github.com/fvdumah/QR-Code)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process
I started with writing the html code.
I struggled a lot with figuring out how to centre the card.
There are so many ways listed online however I had issues with most :D
I decided to just stick with flex.

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox


### What I learned

The main thing I learnt was how important it is to set a height when trying to centre something both vertically and horizontally. I struggled to understand why my card was not vertically centred the way I wanted it. Once I defined the viewport height to a minimum of 100vh. The card became centered.



```css
body {
   display: flex;
    justify-content: center;
    align-items: center;
    min-height: 100vh;
}

```


## Author

- Website - [Fvdumah](https://github.com/fvdumah)
- Frontend Mentor - [@fvdumah](https://www.frontendmentor.io/profile/fvdumah)

