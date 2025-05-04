# Frontend Mentor - NFT preview card component solution

This is a solution to the [NFT preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/nft-preview-card-component-SbdUL_w0U). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Frontend Mentor - NFT preview card component solution](#frontend-mentor---nft-preview-card-component-solution)
  - [Table of contents](#table-of-contents)
  - [Overview](#overview)
    - [The challenge](#the-challenge)
    - [Screenshot](#screenshot)
    - [Links](#links)
  - [My process](#my-process)
    - [Built with](#built-with)
    - [What I learned](#what-i-learned)
  - [Author](#author)

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements

### Screenshot

![](./screenshot.jpg)

Add a screenshot of your solution. The easiest way to do this is to use Firefox to view your project, right-click the page and select "Take a Screenshot". You can choose either a full-height screenshot or a cropped one based on how long the page is. If it's very long, it might be best to crop it.

Alternatively, you can use a tool like [FireShot](https://getfireshot.com/) to take the screenshot. FireShot has a free option, so you don't need to purchase it.

Then crop/optimize/edit your image however you like, add it to your project, and update the file path in the image above.

**Note: Delete this note and the paragraphs above when you add your screenshot. If you prefer not to add a screenshot, feel free to remove this entire section.**

### Links

- Solution URL: [github.com/Opeyemi-stack/nft-preview-card-component-main](https://github.com/Opeyemi-stack/nft-preview-card-component-main)
- Live Site URL: [nft-preview-card-component-main-phi-ten.vercel.app/](https://nft-preview-card-component-main-phi-ten.vercel.app/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS BEM Methodology
- Mobile-first workflow

**Note: These are just examples. Delete this note and replace the list above with your own choices**

### What I learned

I learnt the use of :hover and ::before psuedo element in css to create an overlay effect on the card image.

```html
<div class="card__img-wrapper">
  <img
    class="card__img card__img--hover"
    src="images/image-equilibrium.jpg"
    alt=""
  />
</div>
```

```css
.card__img-wrapper {
  position: relative;
}

.card__img-wrapper:hover::before {
  content: " ";
  width: 100%;
  height: 100%;
  position: absolute;
  top: 0;
  left: 0;
  background: hsla(178, 100%, 50%, 0.548) url(images/icon-view.svg) center no-repeat;
  cursor: pointer;
  border-radius: 10px;
}
```

## Author

- Website - [Obatola Opeyemi](https://github.com/Opeyemi-stack)
- Frontend Mentor - [@Opeyemi-stack](https://www.frontendmentor.io/profile/opeyemi-stack)
- Twitter - [@opeyemi_obatola](https://www.twitter.com/Opeyemi_obatola)
