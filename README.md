<div id="top"></div>

<div align="center">
  <h2 align="center">Fylo landing page with two column layout</h2>
  <p align="center">
    <a href="https://www.frontendmentor.io/solutions/fylo-landing-page-with-two-column-layout-WRPVqmFCKD"><strong>Frontend Mentor Challenge</strong></a>
    <br />
    <br />
    <a href="https://fylo-landing-page-with-two-column-layout-hdez.vercel.app/">View Demo</a>
    ·
    <a href="https://github.com/MelvinAguilar/fylo-landing-page-with-two-column-layout/issues" target="_blank">Report Bug</a>
    ·
    <a href="https://github.com/MelvinAguilar/fylo-landing-page-with-two-column-layout/issues" target="_blank">Request Feature</a>
  </p>
</div>

<!-- Bagdes -->
<div align="center">
  <!-- Profile -->
  <a href="https://www.frontendmentor.io/profile/MelvinAguilar">
    <img src="https://img.shields.io/badge/Profile-Melvin%20Aguilar-07043B?style=for-the-badge&logo=frontendmentor" alt="Melvin Profile">
  </a>
  <!-- Status -->
  <a href="#">
    <img src="https://img.shields.io/badge/Status-Completed-brightgreen?style=for-the-badge" alt="Status Completed">
  </a>

</div>

#

<div align="center">

![](./design/desktop-preview.jpg)

</div>

This is a solution to the [Fylo landing page with two column layout challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/fylo-landing-page-with-two-column-layout-5ca5ef041e82137ec91a50f5). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

<h2 align="center">Links</h2>

- Solution URL: [Fylo landing page with two column layout (SASS + Mobile-first + BEM) | Frontend Mentor](https://www.frontendmentor.io/solutions/fylo-landing-page-with-two-column-layout-WRPVqmFCKD)
- Live Site URL: [https://fylo-landing-page-with-two-column-layout-hdez.vercel.app/](https://fylo-landing-page-with-two-column-layout-hdez.vercel.app/)

<br>

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
- [My process](#my-process)
  - [Built with](#built-with)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

## Overview

### The challenge

Your challenge is to build out this landing page and get it looking as close to the design as possible.

You can use any tools you like to help you complete the challenge. So if you've got something you'd like to practice, feel free to give it a go.

Your users should be able to:

- View the optimal layout for the site depending on their device's screen size
- See hover states for all interactive elements on the page

## My process

### Built with

<!-- Bagdes -->

![](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![](https://img.shields.io/badge/SASS-hotpink?style=for-the-badge&logo=sass&logoColor=white)
![](https://img.shields.io/badge/BEM-black?style=for-the-badge&logo=bem&logoColor=white)
![](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)

- Semantic HTML5 markup
- Mobile-first approach
- Flex Layout
- BEM naming convention
- [SASS](https://sass-lang.com/documentation/modules) - Sass modules

### Useful resources

- [A11Y 101: Ensure landmarks are unique](https://daily-dev-tips.com/posts/a11y-101-ensure-landmarks-are-unique/)
- [Mobile-first approach](https://www.freecodecamp.org/news/taking-the-right-approach-to-responsive-web-design/)
- [CSS Guidelines](https://cssguidelin.es/#bem-like-naming)
- [BEM naming convention](https://css-tricks.com/bem-101/)
- [BEM naming examples](https://getbem.com/naming/)

- [Material Design Box Shadows](https://codepen.io/sdthornton/pen/wBZdXq)
- [CSS background Property](https://www.w3schools.com/cssref/css3_pr_background.asp)

- [Solving Sticky Hover States with @media (hover: hover)](https://css-tricks.com/solving-sticky-hover-states-with-media-hover-hover/)

## Author

- Frontend Mentor - [@melvinaguilar](https://www.frontendmentor.io/profile/melvinaguilar)

## Acknowledgments

When using `sass` in order to build this solution

- Install `sass` if not yet installed:

```bash
npm install -g sass
```

- Run build command from command line:

```bash
sass assets/sass/main.scss assets/css/style.css
```

- If you want to edit the code and test, in the root folder of this repository, run this command from the command line:

```bash
sass --watch assets/sass/main.scss assets/css/style.css
```

## File structure

```
.
├── assets
│   ├── css
│   │   ├── style.css
│   │   └── style.css.map
│   ├── images
│   │   ├── avatar-testimonial.jpg
│   │   ├── bg-curve-desktop.svg
│   │   ├── bg-curve-mobile.svg
│   │   ├── favicon-32x32.png
│   │   ├── icon-arrow.svg
│   │   ├── icon-email.svg
│   │   ├── icon-phone.svg
│   │   ├── icon-quotes.svg
│   │   ├── illustration-1.svg
│   │   ├── illustration-2.svg
│   │   └── logo.svg
│   └── sass
│       ├── abstracts
│       │   ├── _mixins.scss
│       │   └── _variables.scss
│       ├── base
│       │   ├── _page.scss
│       │   └── _reset.scss
│       ├── component
│       │   ├── _attribution.scss
│       │   ├── _buttons.scss
│       │   ├── _container.scss
│       │   ├── _form-control.scss
│       │   ├── _heading.scss
│       │   ├── _horizontal-list.scss
│       │   ├── _media-links.scss
│       │   ├── _screen-reader.scss
│       │   ├── _scrollbar.scss
│       │   └── _skip-link.scss
│       ├── layout
│       │   ├── _contact-section.scss
│       │   ├── _features-section.scss
│       │   ├── _footer.scss
│       │   ├── _header.scss
│       │   ├── _introduction-section.scss
│       │   └── _testimonial-section.scss
│       └── main.scss
├── design
│   ├── active-states.jpg
│   ├── desktop-design.jpg
│   ├── desktop-preview.jpg
│   ├── mobile-design.jpg
│   └── screenshot.png
├── index.html
└── README.md
```
