
---

# Frontend Mentor - Profile Card Component Solution

This is my solution to the [Profile Card Component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/profile-card-component-cfArpWshJ).
A clean, responsive profile card with subtle background patterns and neatly structured analytics.

## Table of Contents

* [Overview](#overview)

  * [The challenge](#the-challenge)
  * [Links](#links)
* [My process](#my-process)

  * [Built with](#built-with)
  * [What I learned](#what-i-learned)
  * [Continued development](#continued-development)
  * [Useful resources](#useful-resources)
* [Author](#author)

---

## Overview

### The Challenge

Users should be able to:

* View the component perfectly centered on all screen sizes
* See responsive decorative background patterns
* View profile details and analytics in a clean, balanced layout

### Links

* **Solution URL:** 
* **Live Site URL:** []()

---

## My Process

### Built With

* Semantic HTML5
* CSS (Flexbox, absolute positioning, custom properties)
* Mobile-first workflow
* Google Fonts (Kumbh Sans)

### What I Learned

This project helped strengthen my understanding of:

* **Layering background patterns** using absolute positioning
* Maintaining visual balance with centered components
* Using `flex` and spacing utilities to align analytics sections
* Styling circular avatars with borders

**Snippet showing avatar placement:**

```css
.avatar-image {
  position: relative;
  bottom: 2rem;
  left: 7.5rem;
  border-radius: 100%;
  border: 0.4rem solid white;
}
```

And the background pattern layout:

```css
.bg-pattern-top {
  position: absolute;
  width: 25rem;
  top: -1rem;
  left: -9rem;
}
```

### Continued Development

Future improvements I’d like to explore:

* Adding subtle motion or hover animations
* Converting this UI into a reusable React component
* Making the card theme-switchable (light/dark mode)

### Useful Resources

* MDN Web Docs – Absolute & relative positioning
* Frontend Mentor community solutions (layout inspiration)
* Google Fonts (for clean typography)

---

## Author

* Website — [https://devolabanks.vercel.app](https://devolabanks.vercel.app)
* Frontend Mentor — [https://www.frontendmentor.io/profile/olabanks](https://www.frontendmentor.io/profile/BANKOLE)
* Twitter — [https://twitter.com/olabanks](https://twitter.com/olabanks)

---
