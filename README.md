# Frontend Mentor - Recipe page solution

This is a solution to the [Recipe page challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/recipe-page-KiTsR8QQKm). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [What I learned](#what-i-learned)
  - [Useful resources](#useful-resources)
- [Author](#author)

## Overview

An HTML CSS responsive static page challenge for practice at any level.

### Screenshot

![Screenshot 2024-12-16 at 20-06-00 Recipes](https://github.com/user-attachments/assets/be9573fa-f4cd-4c9b-93d1-26a34b6c506b)
![Screenshot 2024-12-17 at 16-34-18 Recipes](https://github.com/user-attachments/assets/0d768be1-9efe-4308-86be-4dbf2f838358)

### Links

- Solution URL: [code](assets)
- Live Site URL: [live site URL](https://audriaheinrich.github.io/recipe-page/index.html)

## My process

I started by creating the structure with HTML and then applied CSS based on the requirements. As a best practice, I containerized everything using <article> and <section> tags before adding CSS properties to each portion. Media queries were used to ensure the display adapts to different screen sizes. Most of the CSS properties use tag names to maintain consistency throughout the code. 

### What I learned


Use link to Google Fonts instead of local font files
```html
    <link rel="preconnect" href="https://fonts.googleapis.com" />
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin />
    <link
      href="https://fonts.googleapis.com/css2?family=Outfit:wght@100..900&family=Young+Serif&display=swap"
      rel="stylesheet"
    />
```
The ::marker CSS pseudo-element selects the marker box of a list item, which typically contains a bullet or number.

```css
::marker {
  color: hsl(14, 45%, 36%);
  font-weight: bold;
}
```

```css

object-fit property determines how an <img> should be resized to fit its container.
img {
  width: 100%;
  height: auto;
  object-fit: cover;
}
```

### Useful resources

- [List Alignment](https://www.geeksforgeeks.org/how-to-remove-indentation-from-an-unordered-list-item-using-css/) - This helped me to align lists with the rest of the sections.
- [List Markers](https://developer.mozilla.org/en-US/docs/Web/CSS/::marker) - This helped me to change colour of <li> markers without making changes to the content.
- [Media Queries](https://www.geeksforgeeks.org/how-to-remove-indentation-from-an-unordered-list-item-using-css/https://www.geeksforgeeks.org/how-to-remove-indentation-from-an-unordered-list-item-using-css/) - This is an amazing article which helped me understand media queries. I'd recommend it to anyone still learning this concept.
- [Responsiveness](https://www.freecodecamp.org/news/css-responsive-image-tutorial/) - This is an amazing article which helped me understand responsiveness. I'd recommend it to anyone still learning this concept.

## Author

- Frontend Mentor - [@AudriaHeinrich](https://www.frontendmentor.io/profile/AudriaHeinrich)

