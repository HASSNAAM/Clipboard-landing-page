# Frontend Mentor - Clipboard landing page solution

This is a solution to the [Clipboard landing page challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/clipboard-landing-page-5cc9bccd6c4c91111378ecb9). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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

- View the optimal layout for the site depending on their device's screen size
- See hover states for all interactive elements on the page

### Screenshot

![Desktop Design](./design/desktop-design.jpg)
![Mobile Design](./design/mobile-design.jpg)

### Links

- Solution URL: [Solution URL](https://github.com/HASSNAAM/Clipboard-landing-page.git)
- Live Site URL: [live site URL](https://hassnaam.github.io/Clipboard-landing-page/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow
- [Styled Components](https://styled-components.com/) - For styles

### What I learned

In this project, I learned to effectively utilize semantic HTML5 elements to improve the accessibility and structure of the web page. I also refined my skills in CSS custom properties, Flexbox for responsive design. Here are some code snippets that I am proud of:

```html
<section>
  <h2>Keep track of your snippets</h2>
  <p>Clipboard instantly stores any item you copy in the cloud, meaning you can access your snippets immediately on all your devices. Our Mac and iOS apps will help you organize everything.</p>
</section>
```
```css
button {
  border-radius: 30px;
  padding: 18px 45px;
  border: none;
  outline: none;
  font-weight: bolder;
  color: #fff;
  cursor: pointer;
  transition: opacity 0.3s ease-in-out;
}

button:first-child {
  margin-right: 20px;
  background-color: var(--Strong-Cyan);
  box-shadow: 0 9px 14px hsla(171, 66%, 44%, 0.31);
  border-bottom: 4px groove hsla(171, 66%, 44%, 0.6);
}

button:last-child {
  background-color: var(--Light-Blue);
  box-shadow: 0 9px 14px hsla(233, 100%, 69%, 0.481);
  border-bottom: 2px groove hsla(233, 100%, 69%, 0.9);
}

button:hover {
  opacity: 0.8;
}
```
```js
const proudOfThisFunc = () => {
  console.log('🎉')
}
```
### Continued development

In future projects, I want to focus on improving the accessibility of my web pages by ensuring that all interactive elements are keyboard navigable and have appropriate ARIA labels. I also plan to explore more advanced CSS techniques, such as CSS animations and transitions, to enhance the user experience.
### Useful resources

- [CSS Tricks](https://css-tricks.com) - A comprehensive resource for CSS tutorials and tips.
- [MDN Web Docs](https://developer.mozilla.org) - A valuable reference for web development documentation.
- [The Markdown Guide](https://www.markdownguide.org/) - Helped me write better markdown for documentation.

## Author

- Github - [Hassnaa Mahmoud](https://github.com/HASSNAAM)
- Frontend Mentor - [@HASSNAAM](https://www.frontendmentor.io/profile/HASSNAAM)

## Acknowledgments

I would like to thank the Frontend Mentor community for their support and feedback on my project.