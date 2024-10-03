# Frontend Mentor - QR code component solution

This is a solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)

## Overview

This project is part of a Frontend Mentor challenge that involved building a QR code component using HTML and CSS. The goal was to create a visually appealing and responsive webpage that displays a QR code with a clear message encouraging users to visit Frontend Mentor and improve their coding skills. The design features a clean and modern layout with the QR code, a bold heading, and a supporting description, all of which are centered and easy to read across various device sizes.

### Screenshot

[Alt text](<QR-Code solution.png>)

Above is a screenshot of my solution.

### Links

- Solution URL: [Add solution URL here](https://github.com/sc0006/qr-code-frontend-mentor)
- Live Site URL: [Add live site URL here](https://sc0006.github.io/qr-code-frontend-mentor/)

## My process

HTML Structure:

Main Container: I started with a basic HTML structure and used the <main> element to wrap the core content, ensuring semantic clarity. Inside the main container, a div with the class .qr-container acts as a wrapper for the QR code, heading, and description.

QR Code Image: An <img> element with the class .qr-img was used to display the QR code image, ensuring it was responsive and centered within the card.

Text Elements: The heading and paragraph provide context for the QR code, and both are structured semantically with an <h1> for the primary heading and a <p> for the description.

CSS Styling

Global Reset and Font Setup: I applied a global reset using the universal selector \* to remove default margins and paddings, while box-sizing: border-box ensured consistent sizing. I also linked the "Outfit" font from Google Fonts for a clean, modern aesthetic.

Layout and Centering: The body was styled using Flexbox to vertically and horizontally center the .qr-container on the page. The min-height: 100svh guarantees the layout takes up the entire viewport height for a balanced appearance, even on larger screens.

QR Code Card Styling: The .qr-container class was styled to have a width of 35rem, with rounded corners (border-radius: 2rem) and a subtle shadow (box-shadow: 0 5px 30px #adb5bd) to create a card-like appearance. Inside, the QR code image is scaled to 30rem and centered using margin: auto.

Typography: The heading was given a bold weight and large font size (2rem) for emphasis, while the paragraph was styled with a smaller font size (1.5rem) and a muted color (#495057) to create visual hierarchy.

Responsiveness: I included a media query that adjusts the layout for screens narrower than 37.5rem (600px). This ensures the card remains centered and legible on mobile devices, with padding and margins that adjust to fit smaller screens.

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox for layout
- Media queries for responsiveness

### What I learned

In this project, I focused on improving my skills in responsive design, centering elements using Flexbox, and maintaining a clean layout across different screen sizes. One key learning was how to simplify layout control with Flexbox and how to make elements responsive using media queries.

I also gained more confidence in using modern web fonts and ensuring text and images are well-aligned. The media query implementation helped me ensure that the design would remain user-friendly and visually appealing on smaller devices.

```css
body {
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  min-height: 100svh;
}

.qr-container {
  background-color: #fff;
  border-radius: 2rem;
  padding: 2.4rem;
  width: 35rem;
  box-shadow: 0 5px 30px #adb5bd;
}
```

### Continued development

I plan to further explore responsive design techniques, particularly improving my understanding of fluid layouts and media queries. Although I successfully implemented a mobile-friendly layout, I see room for improvement in simplifying the process of centering content inside containers and optimizing padding and margin settings for better responsiveness.

In future projects, I aim to dive deeper into accessibility features and advanced CSS layouts like Grid to better organize complex designs.

### Useful resources

- [Example resource 1](https://www.w3schools.com/css/css3_mediaqueries.asp) - This helped me with better understanding media queries. I also used some MDN web docs.

## Author

- Frontend Mentor - [@sc0006](https://www.frontendmentor.io/profile/sc0006)
