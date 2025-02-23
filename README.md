# Frontend Mentor - NFT preview card component solution

This is a solution to the [NFT preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/nft-preview-card-component-SbdUL_w0U). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)



## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements


### Links

- Solution URL: [https://github.com/RoxySash/nft-preview-card-component-main.git](https://your-solution-url.com)
- Live Site URL: [https://roxysash.github.io/nft-preview-card-component-main/](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow

### What I learned

I learnt that css is daunting even overlaying a simple svg over an image is quite the work. I had to do research to complete this challenge. 

To see how you can add code snippets, see below:

```html
<h1>Some HTML code I'm proud of</h1>
```
```css
.overlay {
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    background-color: rgba(0, 188, 212, 0); /* Start as fully transparent */
    display: flex;
    justify-content: center;
    align-items: center;
    transition: background-color 0.3s ease-in-out, opacity 0.3s ease-in-out;
    opacity: 0;
    border-radius: 10px;
    
  }

  .overlay img {
    width: 50px;
    transition: opacity 0.3s ease-in-out;
  }


  .image-container:hover .overlay
   {
    cursor: pointer;
    background-color: hsla(178, 100%, 50%, 0.5);
    opacity: 1;
  }


.profile__section--pic {
  border-radius: 50%;
  box-shadow: 0 0 0 1.5px white;
  margin-right: 20px;
}
```


### Continued development

I will refine CSS techniques displayed in this project. 

Topics are overlay effects and svg images 

### Useful resources

- [W3 School](https://www.w3schools.com/cssref/sel_hover.php) - This helped me with the hover issue. 

- [Josh's CSS Reset](https://www.joshwcomeau.com/css/custom-css-reset/) - I use this often now to reset my css saves me a lot of time.


## Author

- Frontend Mentor - [@RoxySash](https://www.frontendmentor.io/profile/RoxySash)


