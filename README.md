# Frontend Mentor - Bento Grid Solution

This is my solution to the [Bento Grid challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/bento-grid-RMydElrlOj). It’s a responsive layout built using CSS Grid and Flexbox.

## Table of Contents

* [Overview](#overview)

  * [The Challenge](#the-challenge)
  * [Screenshot](#screenshot)
  * [Links](#links)
* [My Process](#my-process)

  * [Built With](#built-with)
  * [What I Learned](#what-i-learned)
  * [Continued Development](#continued-development)
* [Author](#author)

---

## Overview

### The Challenge

Users should be able to:

* View the optimal layout for the interface depending on their device’s screen size

### Screenshot

![Desktop Version Screenshot](/screenshots/Bento%20Grid%20Desktop.png)
![Mobile Version Screenshot](/screenshots/Bento%20grid%20Mobile.png)


### Links

* **Solution URL:** [Frontend Mentor Solution](https://www.frontendmentor.io/solutions/bento-grid-layout-grid-and-flexbox-bJ7Vj8uad2)
* **Live Site URL:** [Live Preview](https://michaelo-o.github.io/Bento-grid-frontend-mentor/)

---

## My Process

### Built With

* Semantic HTML5 markup
* CSS custom properties
* CSS Grid
* Flexbox
* Responsive media queries

### What I Learned

This challenge helped solidify my ability to:

* Create complex layouts using `grid-template-areas`
* Diagnose issues when `grid-template-areas` values mismatch their corresponding columns
* Use `object-fit` and `position` to control media presentation inside containers
* Handle responsive breakpoints without relying on JavaScript

#### Example: Responsive Grid Fix

```css
@media screen and (max-width: 1280px) {
  .grid-container {
    grid-template-columns: 1fr 1fr;
    grid-template-areas:
      "item2 item2"
      "item5 item5"
      "item6 item6"
      "item3 item3"
      "item8 item8"
      "item7 item7"
      "item1 item1"
      "item4 item4";
  }
}
```

### Continued Development

I’d like to continue refining my approach to:

* Fully fluid layouts using `auto-fit` and `minmax` instead of fixed breakpoints
* Better accessibility handling and semantic structure for screen readers

---

## Author

* Website – [Michael Okwuosah](https://mikeokwuosah.vercel.app/)
* Frontend Mentor – [@michaelo-o](https://www.frontendmentor.io/profile/michaelo-o)
