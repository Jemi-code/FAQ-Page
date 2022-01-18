# Frontend Mentor - FAQ accordion card solution

This is a solution to the [FAQ accordion card challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/faq-accordion-card-XlyjD0Oam). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

### Screenshot

![](Screenshot.png)

### Links

- Solution URL: [Add solution URL here](https://github.com/Jemi-code/FAQ-Page)
- Live Site URL: [Add live site URL here](https://jemi-code.github.io/FAQ-Page)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow


### What I learned

Use this section to recap over some of your major learnings while working through this project. Writing these out and providing code samples of areas you want to highlight is a great way to reinforce your own knowledge.

To see how you can add code snippets, see below:

```css
summary{
    display: block;
}

summary::marker {
    display: none;
}

summary::after{
    margin-left: 5rem;
    display: inline-block;
    transition: 0.2s;
    -webkit-transition: 0.2s;
    -moz-transition: 0.2s;
    -ms-transition: 0.2s;
    -o-transition: 0.2s;
    content: '\203A';
    font-weight: bold;
    color: hsl(14, 88%, 65%);
    transform: rotate(90deg);
}

.third > summary::after{
    margin-left: 7.7rem;
}

.fourth > summary::after{
    margin-left: 7.5rem;
}

.fifth > summary::after{
    margin-left: 5.8rem;
}

details[open] summary::after{
    transform: rotate(270deg);
    -webkit-transform: rotate(270deg);
    -moz-transform: rotate(270deg);
    -ms-transform: rotate(270deg);
    -o-transform: rotate(270deg);
}

details[open] > summary{
    font-weight: bold;
    color: hsl(237, 12%, 33%);
}
```

## Author

- Frontend Mentor - [@Jemi-code](https://www.frontendmentor.io/profile/Jemi-code)


