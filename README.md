# frontend-mentor-nftCard-challenge
This is my solution of the frontend Mentor NFT challenge with some hover states.
![](design/Frontend_Mentor_-_NFT_preview_card_component_solution.png)

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

![](design/Web%20capture_5-9-2022_13348_127.0.0.1.jpeg)


### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox


### What I learned

As I'm practicing the skills that I already know, I learnt how to use some css pseudo elements that I never used before. I am also learning how to search for solutions fo the the problems that occurs to me.

To see how you can add code snippets, see below:

```html
<div class="nft-image">
  <img class="nftimg" id="nftimg" src="images/image-equilibrium.jpg" alt="a cube photo">
</div>
```
```css
.nft-image{
    position: relative;
    
}
.nft-image::after{
    content: url('./images/icon-view.svg');
    background-color: hsla(178, 100%, 50%, .5);;
    display: flex;
    justify-content: center;
    align-items: center;
    width:18rem;
    height: 18rem;
    border-radius: 12px;
    position: absolute;
    top: 0;
    left :0;
    transform: scale(0);
    transition-duration: 500ms;
    transition-delay: 50ms;
}
.nft-image:hover::after{
    transform: scale(1) rotate(180deg);
}
```

### Continued development

I'm not quite sure if I did the hover overlay for the picture just right. Also I need to work to work on leaving important commets so others can understand my code; I believe it is important to do so.


## Author

- Frontend Mentor - [@HadjerL](https://www.frontendmentor.io/profile/HadjerL)


## Acknowledgments

This where I should give credit for those who have helped.

I should thank [@hyrongennike](https://www.frontendmentor.io/profile/hyrongennike). His [nft card solution](https://www.frontendmentor.io/solutions/nft-card-using-sass-with-glassmorphism-hover-F1j05B92EA) inspired me to do mine, so I tried to add some stuff like the transform on the hover on the picture.
