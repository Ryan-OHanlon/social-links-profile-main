# Frontend Mentor - Social links profile solution

This is a solution to the [Social links profile challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/social-links-profile-UG32l9m6dQ). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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

- See hover and focus states for all interactive elements on the page

### Screenshot

![screenshot](./screenshot.jpg)

### Links

- Solution URL: [https://www.frontendmentor.io/solutions/social-links-profile-using-flex-PosdqUgSEi](https://www.frontendmentor.io/solutions/social-links-profile-using-flex-PosdqUgSEi)
- Live Site URL: [https://ryan-ohanlon.github.io/social-links-profile-main/](https://ryan-ohanlon.github.io/social-links-profile-main/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox

### What I learned

From this challenge I learned how to use flexbox to center all elements to a webpage and the importance of having the property margin be larger than the padding in order to make the visual appearance of boxes using div elements.

```css
body{
    font-family: Inter;
    background-color: hsl(0, 0%, 8%);
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
    min-height: 100vh;
}
```

```css
.social{
    background-color: hsl(0, 0%, 20%);
    border-radius: 0.5em;
    margin: 20px 50px;
    padding: 15px;
    color: hsl(0, 0%, 100%);
    font-weight: 600;
    font-size: 14px;
}
```

### Continued development

Placement of elements using flexbox and grid using CSS is still something I need to learn. The starting set of challenges from Frontend Mentor for newbies really feels like it threw me into the deep end and I've yet to find a decent guide or book to properly explain the display property in css and how and when to use flexbox, grid, or position. It's nice that all I've had to do so far is assign the display property to the body for the project to be in the center of the webpage. However, I know that website design is a lot more complicated and I'd like to know how to use CSS and CSS frameworks for future challenges.

### Useful resources

- [Example resource 1](https://ryan-ohanlon.github.io/blog-preview-card-main/) - Using my previous challenge, I've been able to iterate upon it for this project to start using flex and learn the finer points of using margin and padding to add space between elements and create boxes for text.

**Note: Delete this note and replace the list above with resources that helped you during the challenge. These could come in handy for anyone viewing your solution or for yourself when you look back on this project in the future.**

## Author

- Website - [Ryan O'Hanlon](https://ryan-ohanlon.github.io/)
- Frontend Mentor - [@Ryan-OHanlon](https://www.frontendmentor.io/profile/Ryan-OHanlon)
- Twitter - [@RyanROHanlon](https://www.twitter.com/RyanROHanlon)

**Note: Delete this note and add/remove/edit lines above based on what links you'd like to share.**

## Acknowledgments

I'd like to thank FrontEnd Mentor user beowulf1958 for giving me feedback on my blog-preview-card challenge to use flex which I am using for this project's solution.
