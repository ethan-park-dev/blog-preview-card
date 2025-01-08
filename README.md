Ethan, here is the revised README content in English, incorporating your experience of completing the project solely with HTML and CSS, using a mobile-first approach, and noting your desire to learn more real-world techniques for HTML/CSS in the future. Feel free to adjust any part of this text to suit your needs!

---

# Frontend Mentor - Blog preview card solution

This project is a solution to the [Blog preview card challenge](https://www.frontendmentor.io/challenges/blog-preview-card-ckPaj01IcS) on [Frontend Mentor](https://www.frontendmentor.io). Frontend Mentor helps you improve your coding skills by building realistic projects.

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

**Note:** Feel free to delete this note and update your table of contents based on the sections you actually keep.

---

## Overview

### The challenge

Users should be able to:

- See hover and focus states for all interactive elements on the page

### Screenshot

![](./screenshot.jpg)

Add a screenshot of your solution. The easiest way is to open your project in Firefox, right-click the page, and select “Take a Screenshot.” Depending on the page length, you can choose a full-page screenshot or a cropped one.

Alternatively, you can use a tool like [FireShot](https://getfireshot.com/) to take your screenshot. FireShot has a free version, so you don’t need to purchase anything.

Once you capture the image, crop/optimize/edit it as you like, place it in your project, and update the image path above.

**Note:** Delete this note (and the above paragraphs) once you’ve added your screenshot. If you prefer not to add a screenshot, remove this entire section.

### Links

- **Solution URL:** [https://github.com/ethan-park-dev/blog-preview-card](https://github.com/ethan-park-dev/blog-preview-card)
- **Live Site URL:** [https://blog-preview-card-beta-five.vercel.app/](https://blog-preview-card-beta-five.vercel.app/)

---

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow
- [React](https://reactjs.org/) - JavaScript library
- [Next.js](https://nextjs.org/) - React framework
- [Styled Components](https://styled-components.com/) - For styles

**Note:** These are just examples. Remove this note and replace the items above with actual technologies you used.

### What I learned

For this challenge, I completed everything using **only HTML and CSS**. Notably, I defined **mobile-first styles** and then used **media queries for the desktop version**, which helped me reduce duplicated code. By building for smaller screens first and then expanding for larger viewports, I found it easier to maintain and keep the overall structure clean.

Below is an example snippet:

```css
/* Mobile-default styles */
.card {
  max-width: 32.7rem;
  margin: 0 var(--spacing-150);
}

/* Expanded layout for screens wider than 376px */
@media screen and (min-width: 376px) {
  .card {
    max-width: 38.4rem;
    margin: 0;
  }
}
```

Additionally, using semantic markup helped boost the readability and maintainability of the project. Structuring elements with `<header>`, `<section>`, and `<footer>` made it clearer how content is organized.

### Continued development

- **HTML & CSS in real-world scenarios:** I want to learn more **real-world techniques** for HTML and CSS (such as advanced responsive strategies, CSS preprocessors, ITCSS/BEM structures, etc.).
- **Accessibility (A11Y):** I’m interested in exploring semantic tags and ARIA attributes to improve the user experience for those relying on screen readers.
- **Performance optimization:** In the future, I'd like to delve into strategies like image optimization, splitting up CSS or JS, and other best practices to make the site load faster.

---

## Author

- Frontend Mentor - [@ethan-geek](https://www.frontendmentor.io/profile/ethan-geek)
