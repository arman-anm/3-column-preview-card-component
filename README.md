# As Salamu Alaikum! 👋 

This is my solution to the <a href="https://www.frontendmentor.io/challenges/3column-preview-card-component-pH92eAR2-" target="_blank">3-column preview card component challenge</a> on Frontend Mentor. 

To give it a peek at the solution's live site please <a href="https://arman-anm.github.io/3-column-preview-card-component/" target="_blank">click here</a>.

## Table of contents

- [As Salamu Alaikum! 👋](#as-salamu-alaikum-)
  - [Table of contents](#table-of-contents)
  - [Overview](#overview)
    - [The challenge was:](#the-challenge-was)
    - [Screenshot](#screenshot)
    - [Links](#links)
    - [Built with](#built-with)
    - [What I learned](#what-i-learned)
    - [Resources](#resources)
  - [Acknowledgement](#acknowledgement)
  - [Get Connected](#get-connected)


## Overview

### The challenge was:

Users should be able to..

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements

### Screenshot

![The screenshot of my solution](./images/screenshot.png)

### Links

- <a href="https://www.frontendmentor.io/solutions/solution-to-3column-previewcard-component-challenge-using-flexbox-h-YuBCn58" target="_blank">Solution</a>
- <a href="https://arman-anm.github.io/3-column-preview-card-component/" target="_blank">Live site</a>

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow

### What I learned

```css
/* In CSS */

ELEMENT > element {
  padding: 10px;
}

/* Is not the same as  */

ELEMENT element {
 padding: 10px
}
```

The first one is <a href="https://www.w3schools.com/css/css_combinators.asp" target="_blank">Direct child Selector</a> & the second one is <a href="https://www.w3schools.com/css/css_combinators.asp" target="_blank">Descendant Selector</a>.

In one line of my code I've used
```css
.wrapper-cards * {
  padding: calc(var(--padding-default) * 2);
}
```
and expected to have some padding to the child cards of the wrapper. Which of course didn't happen. Instead it applied padding to all the elements. Then i've added one single character to the code;
```css
.wrapper-cards > * {
  padding: calc(var(--padding-default) * 2);
}
```
 Literally just ONE character which is '>' and voila, it fixed my broken page instantly. 
 
Now, should i get amazed about how powerful just one piece of character is? Or get freaked out about how powerful just ONE piece of character is?

### Resources

- <a href="https://fonts.google.com/specimen/Big+Shoulders+Display" target="_blank">Big Shoulders Display Font</a> - The font used in my Heading texts

- <a href="https://fonts.google.com/specimen/Lexend+Deca" target="_blank">Lexend Deca Font</a> - Used in Paragraph.

- <a href="https://webdevsimplified.com/specificity-cheat-sheet.html" target="_blank">CSS Cheatsheet by Kyle </a> - Helped me understand CSS selectors.
- <a href="https://www.w3schools.com/css/css_combinators.asp" target="_blank">W3School's CSS Combinator Reference Page</a> - A good guide to CSS combinators & also gives chance to play with them in it's great 'Tryit Editor'. 

## Acknowledgement

- Thanks to <a href="https://github.com/AlazarG19" target="_blank">Alazar Getachew</a> for giving me valuable <a href="https://www.frontendmentor.io/solutions/solution-to-3column-previewcard-component-challenge-using-flexbox-h-YuBCn58#comment-623850e08a1c69047217f8ab" target="_blank">feedback</a> after submitting my solution to Frontend Mentor 🙂
  
- Thanks to <a href="https://www.youtube.com/c/WebDevSimplified" target="_blank">Kyle Cook</a> for creating such a nice <a href="https://webdevsimplified.com/specificity-cheat-sheet.html" target="_blank">handbook</a> on CSS selector 🙂

## Get Connected 

- Facebook - <a href="https://www.facebook.com/armaan.anm" target="_blank">Abu Naser Muhammad Arman</a>
- Instagram - <a href="https://www.instagram.com/arman_anm" target="_blank">@arman_anm</a>

- Twitter - <a href="https://twitter.com/arman_anm" target="_blank"> @arman_anm</a>

- Gmail - <a href="mailto:armaan.anm@gmail.com">armaan.anm@gmail.com</a>