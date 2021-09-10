# Personal portfolio featuring my updated collection of projects.

## Table of contents

- [Overview](#overview)
  - [The goal](#the-goal)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)
<!-- - [Acknowledgments](#acknowledgments) -->

## Overview

### The goal

Users should be able to:

- [x] View the optimal layout for the site depending on their device's screen size
- [x] Enter the game app through age verification
- [x] Play and restart the game as many times as they want
<!-- - Choose between a green, red, or black table. -->

### Screenshot

![](./screenshot.jpg)

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

- I organize my html classes using double\_\_underscore and double--dash to improve readability. This can make it easier to keep track of parent and children elements when working with the css.
- <img> always has an alt="", but is left empty if unnecessary.

### Built with

- Semantic HTML5 markup
- CSS
- Flexbox
<!-- - CSS Grid -->
- Mobile-first workflow
    <!-- - [React](https://reactjs.org/) - JS library -->
    <!-- - [Next.js](https://nextjs.org/) - React framework -->
  <!-- - [Styled Components](https://styled-components.com/) - For styles -->

### What I learned

<!-- - How to work with if/else statements.
- How to work with for-loops.
- Practiced working with logical operators. -->

<!-- ```html
<h1>Some HTML code I'm proud of</h1>
```

```css
.proud-of-this-css {
  color: papayawhip;
}
``` -->

I learned that instead of making a nested if-statement where two conditions need to be met, we can use the && operator inside the parentheses.

```js
// Don't use this nesting
if (hasCompletedCourse === true) {
  if (givesCertificate === true) {
    generateCertificate();
  }
}

// Use this instead
if (hasBlackJack && isAlive) {
  gameOver();
}

// Which is the same as
if (hasBlackJack === true && isAlive === false) {
  gameOver();
}

// This is how we get a random integer in any range
function getRandomCard() {
  let randomNumer = Math.floor(Math.random() * 13) + 1;
  if (randomNumer > 10) {
    return 10;
  } else if (randomNumer === 1) {
    return 11;
  } else {
    return randomNumer;
  }
}
```

<!-- If you want more help with writing markdown, we'd recommend checking out [The Markdown Guide](https://www.markdownguide.org/) to learn more. -->

### Continued development

Use this section to outline areas that you want to continue focusing on in future projects. These could be concepts you're still not completely comfortable with or techniques you found useful that you want to refine and perfect.

### Useful resources

- [Example resource 1](https://www.example.com) - This helped me for XYZ reason. I really liked this pattern and will use it going forward.
- [Example resource 2](https://www.example.com) - This is an amazing article which helped me finally understand XYZ. I'd recommend it to anyone still learning this concept.

## Author

- Website - [Add your name here](https://www.your-site.com)
- GitHub - [@FredrikRidderfalk](https://www.frontendmentor.io/profile/yourusername)
- Twitter - [@yourusername](https://www.twitter.com/yourusername)

<!-- ## Acknowledgments

This is where you can give a hat tip to anyone who helped you out on this project. Perhaps you worked in a team or got some inspiration from someone else's solution. This is the perfect place to give them some credit.

**Note: Delete this note and edit this section's content as necessary. If you completed this challenge by yourself, feel free to delete this section entirely.** -->
