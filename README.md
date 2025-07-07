# Frontend Mentor - Bento Grid Solution

This is my solution to the [Bento Grid challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/bento-grid-RMydElrlOj). It helped me sharpen my CSS Grid layout skills, implement responsive design across breakpoints, and apply modern font strategies using both static and variable sources.

---

## 📋 Table of Contents

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
- [Acknowledgments](#acknowledgments)

---

## 📌 Overview

### 🎯 The Challenge

Users should be able to:

- View the layout optimized for different screen sizes (mobile, tablet, desktop)
- Navigate a Bento-style grid system that rearranges responsively
- Experience clean typography and semantic layout across devices

### 🖼️ Screenshot

![Screenshot](./screenshot.jpg)

> Replace with your actual screenshot when ready.

### 🔗 Links

- **Solution URL:** [https://github.com/Juan-Restrepo-Dev/]([https://github.com/Juan-Restrepo-Dev/bento-grid](https://github.com/Juan-Restrepo-Dev/Challenge-frontendMentor-Bento-grid.git))
- **Live Site URL:** _Project currently runs on Live Server locally. A public deployment (e.g., GitHub Pages or Vercel) will be added soon._

---

## ⚙️ My Process

### 🔧 Built With

- Semantic HTML5
- CSS Custom Properties (variables)
- CSS Grid & Flexbox
- Mobile-first responsive workflow
- BEM methodology
- Variable fonts with static fallbacks

---

### 💡 What I Learned

- **Grid layout strategies:** I used `display: grid` in combination with `grid-template-areas` to define a semantic and responsive layout across desktop, tablet, and mobile views.
- **Modular CSS design:** I organized styles using the BEM methodology and grouped repeatable properties for better maintainability.
- **Responsive design with media queries:** I built a mobile-first layout and added fine-grained control for tablets and large screens.
- **Variable fonts:** I used `@supports (font-variation-settings: normal)` to load variable fonts with graceful fallback support:

```css
@supports (font-variation-settings: normal) {
  @font-face {
    font-family: 'DMSansVar';
    src: url('../fonts/DMSans-VariableFont_opsz,wght.ttf') format('truetype');
    font-weight: 400 800;
    font-style: normal;
  }
}
```

---

### 🚀 Continued Development

Next steps I want to explore:

- Building a utility-first helper system for spacing, font sizing, and breakpoints
- Adding animation and interaction feedback for enhanced UX
- Conducting accessibility audits for screen readers and keyboard navigation
- Deploying the site publicly on GitHub Pages or Vercel

---

### 📚 Useful Resources

- [CSS Tricks – A Complete Guide to Grid](https://css-tricks.com/snippets/css/complete-guide-grid/)
- [web.dev – Variable Fonts Guide (ES)](https://web.dev/articles/variable-fonts?hl=es) — Helped me understand how to use and optimize variable fonts with proper fallbacks

---

## 👨‍💻 Author

- GitHub – [@Juan-Restrepo-Dev](https://github.com/Juan-Restrepo-Dev)

---

## 🙌 Acknowledgments

Big thanks to:

- [Frontend Mentor](https://www.frontendmentor.io?ref=challenge) for providing this realistic and fun design challenge  
- [web.dev’s article on variable fonts](https://web.dev/articles/variable-fonts?hl=es) for helping me deeply understand modern web typography and performance techniques  
- team leader **Lina** at **Riwi** for sharing this challenge with me and encouraging continuous growth throughout the learning process
