# Social-links-profile-solution
# Frontend Mentor - Social links profile solution

This is a solution to the [Social links profile challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/social-links-profile-UG32l9m6dQ). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)



## Overview

### The challenge

Users should be able to:

- View social media links in button format

- See hover and focus states for all interactive elements on the page

### Screenshot

![](./Screenshot%20(32).png)
### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup

- CSS custom properties

- Flexbox

- Mobile-first workflow

- Google Fonts (Inter)

### What I learned
This project allowed me to enhance my knowledge of CSS variables, hover effects, and responsive design. Below are examples of the code I implemented:
:root {
  --Green: hsl(75, 94%, 57%);
  --White: hsl(0, 0%, 100%);
  --Grey700: hsl(0, 0%, 20%);
  --Grey800: hsl(0, 0%, 12%);
  --Grey900: hsl(0, 0%, 8%);
}

.content {
  padding: 35px;
  background-color: var(--Grey800);
  width: 380px;
  display: flex;
  flex-direction: column;
  justify-content: center;
  border-radius: 10px;
}

.content:hover {
  box-shadow: 1px 2px 3px 4px var(--Green);
}

### Continued development
In the future, I plan to:

- Incorporate additional animations for a better user experience.

- Make the project fully responsive across all device sizes.


### Useful resources

- CSS Tricks - This website provided valuable insights into Flexbox properties.

- Google Fonts - For adding the Inter font family.



## Author

- Frontend Mentor - @Codeman-Piklu

- GitHub - Codeman-Piklu



## Acknowledgments

Thanks to Frontend Mentor for providing such a fantastic challenge. It was an excellent opportunity to improve my coding skills and learn something new.
