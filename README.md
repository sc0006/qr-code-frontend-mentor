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

Main Container: I started by structuring the content using the main element for semantic clarity, wrapping the core content in a div with the class .QR-container, which houses the QR code image, heading, and description.

QR Code Image: The img tag with class .QR-img was used for the QR code, ensuring it scales and centers responsively within the card.

Text Elements: The heading h2 and paragraph p were added to give context to the QR code. Both are semantically appropriate for their roles and visually align within the card.

CSS Styling

Global Reset and Font Setup: I applied a global reset with the \* selector to remove default margins and padding, ensuring consistent layout. box-sizing: border-box was used to simplify width and padding calculations. I included the "Outfit" font from Google Fonts for a clean and modern feel.

Layout and Centering: The body of the page was styled with Flexbox, centering the .QR-container both vertically and horizontally. I used min-height: 100svh to ensure the card takes up the full viewport height, making it centered and balanced on any screen.

QR Code Card Styling: The .QR-container was styled with a white background (background-color: #fff), rounded corners (border-radius: 2rem), and a subtle shadow (box-shadow: 0 5px 30px #adb5bd) to create a polished card-like appearance. The QR image inside the container was styled with rounded corners as well and a margin to ensure proper spacing.

Typography: The heading (.prime-heading) was given a bold weight and a large font size (2rem) to make it stand out, while the paragraph (.description) was styled with a smaller font size (1.5rem) and a softer color (#495057) for contrast and readability.

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox for layout

### What I learned

In this project, I focused on improving my skills in responsive design, centering elements using Flexbox, and maintaining a clean layout across different screen sizes. One key learning was how to simplify layout control with Flexbox.

I also gained more confidence in using modern web fonts and ensuring text and images are well-aligned.

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

In future projects, I aim to dive deeper into accessibility features and advanced CSS layouts like Grid to better organize complex designs.

### Useful resources

- [Example resource 1](https://www.w3schools.com/css/css3_mediaqueries.asp) - This helped me with better understanding media queries. I also used some MDN web docs.

## Author

- Frontend Mentor - [@sc0006](https://www.frontendmentor.io/profile/sc0006)
