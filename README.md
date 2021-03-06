# Frontend Mentor - FAQ accordion card solution

This is a solution to the [FAQ accordion card challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/faq-accordion-card-XlyjD0Oam). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

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

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements

### Screenshot

Mobile:

![mobile](https://user-images.githubusercontent.com/70554280/129533113-b179d521-0f02-42c9-8041-458b1399f08e.png)


Desktop:

![desktop](https://user-images.githubusercontent.com/70554280/129666819-3b549985-0eb1-42fe-9bbe-0000ea3ced06.png)


### Links

- Solution URL: [Github repository](https://github.com/Mauricio2802/faq-main)
- Live Site URL: [Website](https://faq-main-mauricecl42.vercel.app/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CCS Grid
- Mobile-first workflow

### What I learned

I learn a lot of things about manipulate the DOM with Javascript. Check my unique script file to check the JS code.

I implement a transition in the answer appearing with CSS:

I put the transition in margin because I think is a easy way to do that.
```css
/* article response style*/
.article__response {
  margin-top: 0px;

  visibility: hidden;
  position: absolute;
}

/* Response transition */
.article__response {
  transition: margin 0.5s ease;
}

.response-appear {
  margin-top: 12px;

  visibility: visible;
  position: static;
}
```

### Continued development

I finished this project, and I learned a lot of things. The project finished here, but I'll go ahead with more projects :D

### Useful resources

- [hidden vs visibility](https://cybmeta.com/display-none-vs-visibility-hidden-y-tu-como-escondes-las-cosas) - This article was helpful to have a better idea on how to disappear an element in HTML.
- [Select DOM elements with JS](https://lenguajejs.com/javascript/dom/seleccionar-elementos-dom/) - This article was helpful to have a better idea on how to manipulate the DOM.
- [MDN](https://developer.mozilla.org/) - This incredible website helped me a lot with the properties of CSS and JS.
- [W3C Schools](https://www.w3schools.com/) - This was helpful too.
- [Response about shadow svg](https://es.stackoverflow.com/questions/287386/aplicar-sombra-a-contorno-de-objetos-svg-con-css)
- [Article about transition property CSS](https://cybmeta.com/animaciones-basicas-con-css-transition)
- [How to overlap images](https://es.stackoverflow.com/questions/174400/c%C3%B3mo-superponer-dos-im%C3%A1genes)
- [CCS Grid](https://lenguajecss.com/css/maquetacion-y-colocacion/grid-css/) - This resource helped me to remmember basic CSS Grid.
- [How works the property background](https://css-tricks.com/almanac/properties/b/background/) - This was helpful to deepen the property background.

## Author

- Website - I don't have a website yet
- Frontend Mentor - [@Maurice2802](https://www.frontendmentor.io/profile/Maurice2802)
- Twitter - [@maurice_cl42](https://www.twitter.com/maurice_cl42)
