# Frontend Mentor - Time tracking dashboard solution

This is a solution to the [Time tracking dashboard challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/time-tracking-dashboard-UIQ7167Jw). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

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

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the site depending on their device's screen size
- See hover states for all interactive elements on the page
- Switch between viewing Daily, Weekly, and Monthly stats

### Screenshot

### Links

- Solution URL: [GitHub](https://github.com/KharlAbban/frontendmentor-time-tracking-soln)
- Live Site URL: [GitHub Pages](https://kharlabban.github.io/projects/frontendmentor_time_tracker/index.html)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Vanilla JS
- Mobile-first workflow
- [Bootstrap 5](https://getbootstrap.com) - CSS Framework

### What I learned

Great project! Full of fun. I learnt how to access object properties using values from variables. Man, such good things!
Find the snippet below, a sample from my original work:

```js
let timeFrame = "weekly";
data.forEach((item, index) => {
	currentHour[index].textContent = `${item.timeframes[timeFrame].current}hrs`;
	prevHours[
		index
	].textContent = `${prefix} - ${item.timeframes[timeFrame].previous}hrs`;
});
```

### Continued development

I was so excited to finish this project I forgot to correctly render it for mobile users. Its therefore my plan to update this project with a better, mobile responsive version.

### Useful resources

- [Bootstrap 5](https://www.getbootstrap.com) - This CSS framework is amazing. It virtually does all the styling and grid work for you. Check it out!
- [W3Schools](https://www.w3schools.com) - This is an amazing article which helped me throughout with helpful CSS tips, best practices, and examples.
- [Google Fonts](https://fonts.google.com) - This font collection really helped me spped up my workflow. I simply copied the @import code generated and I was good to go.
- [Stack Overflow](https://stackoverflow.com) - This is a very helpful technical and developer solution base. I found a lot of the answers to my issues here.
- [Web Dev Simplified](https://www.youtube.com/WebDevSimplified) - This channel has been a great learning source for all my frontend works. Do check him out!

## Author

- Frontend Mentor - [@KharlAbban](https://www.frontendmentor.io/profile/KharlAbban)
- Github - [KharlAbban](https://www.github.com/KharlAbban)
- LinkedIn - [KharlAbban](https://www.linkedin.com/in/er-carl-abban-623817271/)
