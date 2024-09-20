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

For this project, I created a simple webpage that displays a QR code encouraging users to improve their front-end development skills by building projects. The challenge is part of the Frontend Mentor platform. I used HTML and CSS to structure the content and style the page, focusing on a clean layout that works well across different screen sizes. The page features a centered QR code image, a bold heading, and a descriptive call-to-action message that prompts users to scan the code for further learning resources.

### Screenshot

! ![Alt text](<QR-Code solution.png>)

Above is a screenshot of my solution.

### Links

- Solution URL: [Add solution URL here](https://github.com/sc0006/qr-code-frontend-mentor)
- Live Site URL: [Add live site URL here](https://sc0006.github.io/qr-code-frontend-mentor/)

## My process

HTML Structure:

I began by setting up a basic HTML document with meta tags for character encoding and viewport settings for responsive design.
I linked a Google Fonts stylesheet to use the "Outfit" font throughout the page for a modern, clean look.
I structured the content inside a div with the class qr-container to serve as a wrapper for the entire card, ensuring that the QR code, heading, and description were centrally located on the page.
I used a h1 tag for the main heading and a p tag for the description, both of which are styled to be readable and align with the overall design goals.
CSS Styling:

I began by using a universal selector to set a default font family, remove any default margins and padding, and apply box-sizing: border-box to make sizing predictable across elements.
I set the base font size using the root html element, with 62.5% to allow for easy rem calculations in other elements.
For the body, I applied a light background color (#d6e2f0) to create a contrast with the white card containing the QR code.
The .qr-container div was styled to have a specific width (35rem) and height (50rem), with a white background, rounded corners, and a subtle box shadow to give the card a floating effect.
Inside the card, the .qr-img class was used to control the width and apply a border-radius to round off the QR code's edges.
The heading and description are centered and styled with font sizes and weights that make them stand out. The description also has a different color (#495057) to provide some hierarchy between the text elements.
I included a media query to adjust the margin for smaller screens (max-width of 37.5rem), making the card more accessible on mobile devices.

### Built with

- Semantic HTML5 markup
- CSS custom properties

### What I learned

I gained hands-on experience with building a simple, centered layout using CSS. I learned how to structure content within a container and center it both horizontally and vertically on the page. Additionally, the use of media queries allowed me to ensure that the layout would adapt well on smaller screens like mobile devices.

```css
.qr-container {
  margin-left: auto;
  margin-right: auto;
}

@media screen and (max-width: 37.5rem) {
  .qr-container {
    margin-top: 2rem;
  }
}
```

### Continued development

I really had to play with padding and width/height to get the image to center inside the container. I hope with more practice I can simplify this process and make it a lot easier on myself.

I also hope to do more involving media queries because up until this project I had never used them before.

### Useful resources

- [Example resource 1](https://www.w3schools.com/css/css3_mediaqueries.asp) - This helped me with better understanding media queries. I also used some MDN web docs.

## Author

- Frontend Mentor - [@sc0006](https://www.frontendmentor.io/profile/sc0006)
