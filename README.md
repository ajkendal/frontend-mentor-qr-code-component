# Frontend Mentor - QR code component solution

This is a solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
- [Author](#author)

## Overview

### Screenshot

![Screenshot](./images/Screenshot%202025-09-15%20at%207.27.13 PM.png)

### Links

- Solution URL: [GitHub Repo](https://github.com/ajkendal/frontend-mentor-qr-code-component)
- Live Site URL: [QR Code Component](https://ajkendal.github.io/frontend-mentor-qr-code-component/)
- Frontend Mentor Submission: [Frontend Mentor](https://www.frontendmentor.io/solutions/responsive-qr-code-with-grid-Ipljsgu7du)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Google Fonts

### What I learned

While building this project, I learned and practiced several important front-end skills. I usually rely on Flexbox for layout, but I am intentionally working on using CSS Grid more to expand my skills and get more comfortable with its capabilities:

- **Semantic HTML5**: I used semantic elements like `<main>`, proper heading levels, and descriptive `alt` text to improve accessibility and structure.
- **CSS Grid for Centering**: I used CSS Grid's `place-items: center` to perfectly center the QR code component both vertically and horizontally on the page. This project was a great opportunity to practice Grid, since I tend to reach for Flexbox by default.
- **Accessibility (ARIA)**: I added ARIA labels and roles to make the component more accessible to screen readers.
- **Custom Properties**: I used CSS custom properties for easier color and style management.
- **Responsive Design**: I ensured the layout adapts well to different screen sizes.

Example of the centering technique:

```css
body {
  min-height: 100vh;
  display: grid;
  place-items: center;
}
```

Example of semantic and accessible HTML:

```html
<main class="content" role="main" aria-label="QR code component">
  <img
    src="./images/image-qr-code.png"
    alt="Scan this QR code to visit Frontend Mentor and improve your front-end skills"
  />
  <h1>Improve your front-end skills by building projects</h1>
  <p>
    Scan the QR code to visit Frontend Mentor and take your coding skills to the
    next level
  </p>
</main>
```

## Author

- Website - [Amanda J Kendal-Brown](https://ajkendal.github.io/)
- LinkedIn - [@akendalb](https://www.linkedin.com/in/akendalb)
- GitHub - [@ajkendal](https://github.com/ajkendal/)
- Frontend Mentor - [@ajkendal](https://www.frontendmentor.io/profile/ajkendal)
