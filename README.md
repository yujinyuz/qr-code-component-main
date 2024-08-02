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
- [Acknowledgments](#acknowledgments)

## Overview

### Screenshot

![](./screenshot.jpeg)

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox

### What I learned

You need to provide the width: 100% to the image so that it only takes up the available width of the
parent container

```css
.card img {
  width: 100%;
  height: 100%;
  border-radius: inherit;
}
```


I also made a rookie mistake where I was applying the padding to the `img` instead of the parent
container.

```css
.card {
  ...
  padding: 1.5em;
}
```

## Author

- Website - [Yujin](https://jinyuz.dev)
- Frontend Mentor - [@yujinyuz](https://www.frontendmentor.io/profile/yujinyuz)
- Twitter - [@yujinyuz_](https://www.twitter.com/yujinyuz_)
