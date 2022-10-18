# Make It Real - Single Price Grid

This is a solution to the Single Price Grid project of the Make It Real course.

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
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

- Visualize the page in desktop a mobile resolution properly.

### Screenshot

![](./screenshots/mobile.png)
![](./screenshots/desktop.png)

## My process

### Built with

- HTML5
- CSS
- CSS Grid
- Mobile-first workflow

### What I learned

In this project we learn how to use CSS Grid to change make a responsive content container.

```css
@media (min-width: 1440px) {

    #cardInfo {
        width: 650px;
        height: 400px;
        align-items: center;
        border-radius: 5px;
        display: grid;
        grid-template-columns: repeat(2, 1fr);
        grid-template-rows: 45% 55%;
        grid-column-gap: 0px;
        grid-row-gap: 0px;
    }

    #cardInfo .gridOne {
        grid-area: 1 / 1 / 2 / 3;
        height: 100%;
        justify-content: center;
    }

    #cardInfo .gridOne h1{
        margin-bottom: 15px;
    }

    #cardInfo .gridTwo {
        grid-area: 2 / 1 / 3 / 2;
        height: 100%;
        border-bottom-left-radius: 10px;
    }
    #cardInfo .gridThree {
        grid-area: 2 / 2 / 3 / 3;
        height: 100%;
        border-radius: 0 0 10px 0;
    }

}
```


### Continued development

We need to continue learning about how flexbox and CSS Grid works.

### Useful resources

- [Resource 1](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Grid_Layout) - This helped me to understand CSS Grid.

## Author

- Juan Sebastián Muñoz


## Acknowledgments

Thanks to Salomón, Camilo and the teacher.
