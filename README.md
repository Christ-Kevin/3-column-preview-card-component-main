# Frontend Mentor - 3-column preview card component solution

This is a solution to the [3-column preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/3column-preview-card-component-pH92eAR2-).  

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

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements

### Screenshot

![](./screenshot.jpg)

### Links

- Solution URL: [https://github.com/Christ-Kevin/3-column-preview-card-component-main.git]
- Live Site URL: [https://christ-kevin.github.io/3-column-preview-card-component-main/]

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- [Styled Components](https://styled-components.com/) - For styles

### What I learned

I used button tags for the first time in this project. I feel confortable with buildin the DOM.
I also feel like if my CSS file would have been shorter if i was able to code in javascript. 
But i'm not yet able to build web-apps witth javascript(still to come ;)).
(Update: a tutor from Frontendmentor [@Grace](https://www.frontendmentor.io/profile/grace-snow) 
told me it was'nt a good idea to use button tags so I used anchor tags instead.
I have to add that the min-width and max-width was used to resize the button(or anchor). 
If that's was not done, once the user resize the window of his browser the anchors move in different direction
and it does'nt look good at all.
I also learned in this project how to make layout fluid. I used calc values for the fluidity of my boxes. 
The calc values can be used to describe every properties that can be described with px values.
and example would be the following expression.  
calc(17px + 1vw) means that for every increased width(+100px) of the viewport, 1px is added to the initial value 
of the propertie.

I'm happy that i could use the following CSS
````
article div:last-of-type {
        display: flex;
        flex-direction: column;
        justify-content: space-between;
        flex: 1 0 auto;
    }
````
This CSS helped me to make that all the buttons stay in the same row. By pushing them at the end(position) of the articles(main-child).

### Continued development

- Improve my flexbox skills
- Improve responsive design
- Learn and use my grid skills

### Useful resources

- [Flexbox - CSS Tricks](https://css-tricks.com/snippets/css/a-guide-to-flexbox/) - This is a complete flexbox guide
- [Fun with Viewport Units](https://css-tricks.com/fun-viewport-units/) - describes viewport units and uses for typographie, images, containers, footer and aspect ratio

## Author

- Website - [Christ Touga](https://www.linkedin.com/in/christ-k%C3%A9vin-touga-watat-32026712a?lipi=urn%3Ali%3Apage%3Ad_flagship3_profile_view_base_contact_details%3BjJWnqFGfRGyI%2FPm5Rzm0dw%3D%3D)
- Frontend Mentor - [@Christ-Kevin](https://www.frontendmentor.io/profile/Christ-Kevin)
- Twitter - [@WatatK](https://www.twitter.com/WatatK)

## Acknowledgements

A special thank to [@Grace](https://www.frontendmentor.io/profile/grace-snow) who gave me some advices when I submitted my solution of this challenge
