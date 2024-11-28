# Frontend Mentor - Stats Preview Card Component Solution

This is my solution to the [Stats preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/stats-preview-card-component-8JqbgoU62). This challenge helped me practice building responsive layouts and applying modern CSS techniques to create visually appealing components.

## Table of Contents

- [Overview](#overview)
  - [The Challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My Process](#my-process)
  - [Built With](#built-with)
  - [What I Learned](#what-i-learned)
  - [Continued Development](#continued-development)
  - [Useful Resources](#useful-resources)
- [Author](#author)

## Overview

### The Challenge

Users should be able to:

- View the optimal layout for the component depending on their device's screen size

### Screenshot

#### Desktop View

![Desktop Screenshot](./assets/screenshots/desktop-view.png)

#### Mobile View

![Mobile Screenshot](./assets/screenshots/mobile-view.png)

### Links

- Solution URL: [GitHub Repository](https://github.com/Mayen007/stats-preview-card)
- Live Site URL: [Live Demo](https://Mayen007.github.io/stats-preview-card/)

## My Process

### Built With

- Semantic HTML5 markup
- CSS custom properties for maintainable and reusable styling
- **Flexbox** for layout alignment
- **Media queries** for responsive design
- Mobile-first workflow

### What I Learned

This project enhanced my understanding of:

- Managing responsive images using `<picture>` tags or conditionally displayed `<img>` tags:

```html
<img
  src="./assets/images/image-header-desktop.jpg"
  alt="Statistics Image"
  class="card-image desktop-image"
/>
<img
  src="./assets/images/image-header-mobile.jpg"
  alt="Statistics Image"
  class="card-image mobile-image"
/>
```

### Applying Responsive Design Techniques

One key takeaway was learning how to rearrange elements dynamically based on screen size:

```css
@media screen and (max-width: 768px) {
  .card {
    flex-direction: column-reverse;
  }
}
```

### Continued Development

I aim to:

- Explore **CSS Grid** for more complex layouts in future projects
- Experiment with **SASS** for better organization of CSS in larger projects
- Further optimize images for performance across devices

### Useful Resources

- [CSS-Tricks: Flexbox Guide](https://css-tricks.com/snippets/css/a-guide-to-flexbox/)
- [MDN Web Docs: Media Queries](https://developer.mozilla.org/en-US/docs/Web/CSS/Media_Queries/Using_media_queries)

### Author

- Frontend Mentor - [@Mayen007](https://www.frontendmentor.io/profile/Mayen007)
- GitHub - [@Mayen007](https://github.com/Mayen007)
