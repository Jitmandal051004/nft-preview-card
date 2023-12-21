# Frontend Mentor - NFT preview card component solution

This is a solution to the [NFT preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/nft-preview-card-component-SbdUL_w0U). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements

### Screenshot

![non-hover state](images/screenshot(non-hover).png)
![active state](images/Screenshot(active%20state).png)

### Links

- [Solution URL](https://jitmandal051004.github.io/nft-preview-card/)
- [Live Site URL](https://www.frontendmentor.io/solutions/nft-preview-card-tRv4oLXQEM)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox

### What I learned

To add hover state to a image which has a ranslucent background plus a icon on it and positioning it.

```css
.view-icon{
    margin-top: -180px;
    margin-left: -275px;
    height: 250px;
    width: 250px;
    border-radius: 10px;
    display: flex;
    justify-content: center;
    align-items: center;
}

.view-icon:hover{
    background-color: var(--hover-color);
}

.view-icon img{
    opacity: 0;
}

.view-icon:hover img{
    opacity: 1;
}
```
### Useful resources

- [flexboxfroggy game](https://flexboxfroggy.com/) - This helped me to learn flexbox by applying it in a fun way.
- [MDN doc on hover state](https://developer.mozilla.org/en-US/docs/Web/CSS/:hover) - This is an amazing article which helped me to understand and use hover state.

## Author

- Hashnode Blog - [Indrajit Mandal](https://jitm25.hashnode.dev/)
- Frontend Mentor - [@Jitmandal051004](https://www.frontendmentor.io/profile/Jitmandal051004)
- Twitter - [@mandal24_jit](https://twitter.com/mandal24_jit)