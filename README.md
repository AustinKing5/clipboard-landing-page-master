# clipboard-landing-page-master
This is a solution to the [Clipboard landing page challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/clipboard-landing-page-5cc9bccd6c4c91111378ecb9). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
- [Author](#author)
- [Acknowledgments](#acknowledgments)


### The challenge
- The challenge is to build out this landing page and get it looking as close to the design as possible.

- To do this challenge, you need a basic understanding of HTML and CSS
Users should be able to:

- View the optimal layout for the site depending on their device's screen size
- See hover states for all interactive elements on the page

### Screenshot

![](./images/Screenshot%202023-05-12%20at%2013-43-44%20Frontend%20Mentor%20Clipboard%20landing%20page.png)

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- HTML5
- CSS custom properties
- CSS Grid
- Desktop-first workflow
- Chrome Developer tools


### What I learned

One of the things I battled with was styling the active state of the social media icons. i initially used the <img scr=""> HTML tag which made it difficult to achieve the desired results. switching to the <svg></svg> tag made is possible to achieve the results by the changing the "fill" element to 'currentColor'.

I then used the following css codes to effect the neccesary change and get the desired reults.
```css
svg {
    color: #4c545c;
}

svg:hover {
    color: #26baa4;
}
```

```html
<br class="header-line-break">

```
Also, css grid provide very important in solving this challenge.
```css
.partners {
    display: grid;
    grid-template-columns: repeat(5, 1fr);
}
```
Responsiveness is a concept I appreciate but have struggled to implement , especially, getting the syntax for media query. i was able to successfully achieve the desired results.
```CSS
@media (max-width: 375px) {

}
```

### Continued development

Learning CSS grids has been an amazing exoerience. the plan is explore more on this concept and learn various ways it can be applied in creating layout of website and other experimental ways it can applied.


## Author

- Website - [Augustine Asare](https://github.com/AustinKing5)
- Frontend Mentor - [@yourusername](https://www.frontendmentor.io/profile/AustinKing5)
- Twitter - [@aryetehasare](https://www.twitter.com/aryetehasare)


