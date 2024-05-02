## Table of contents

- [Overview](#overview)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)

## Overview

### Screenshot

![View Image](./images/screenshot.png)

### Links

- Solution URL: [https://github.com/christinelinster/fm-qr-code](https://github.com/christinelinster/fm-qr-code)
- Live Site URL: [https://christinelinster.github.io/fm-qr-code/](https://christinelinster.github.io/fm-qr-code/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox

### What I learned

This was the project I implemented using flexbox without any assistance, and is an area I need to review. During this project, I struggled with using the right properties to center-align the components and had to continuously complete a trial-and-error method. 

For example, I struggled to center the qr code container in the middle of the screen, only to discover it was because I missed setting the body element's height to 100% of the viewport. 

```css
body{
    background-color: hsl(212, 45%, 89%);
    justify-content: center;
    height: 100vh;
}
```

### Continued development

In future projects, I will place more emphasis on cleaning up and simplifying repetitive areas in my style sheet. Since this was my first project, the process I used to approach the project was not as efficient as I hoped. I will continue to learn more best practices to implement for future projects. 
