# Building layouts with Flexbox and Grid

In this lesson, we're going to explore how to build multi-column websites using `display: flex;` and `display: grid;`. 

## Intro to Flexbox
Flexbox is short for "The CSS3 Flexible Box Module". From [MDN](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Flexible_Box_Layout/Using_CSS_flexible_boxes), here's a definiton:

> Flexbox ... is a layout mode providing for the arrangement of elements on a page such that the elements behave predictably when the page layout must accommodate different screen sizes and different display devices. ... The defining aspect of the flex layout is the ability to alter its items' width and/or height to best fit in the available space on any display device.

## Flex context vs block context
- Up to this point we've been working with the block context -- `display: block;`. 
- Flexbox introduces a new context: `display: flex;`.
- Elements with `display: flex;` have, largely, an external block context -- they exist in the document flow like any other kind of element.
- Internally, they create a new type of context that has its own properties.

## Flex Containers and Items
The key to understanding Flexbox is dividing elements into containers and items. The majority of the flexbox code we write will be applied to containers in order to affect the items within. 

For example, at the most basic level, if we have two or more block elements stacked on top of each other, and we want them to be next to each other, we simply wrap them in a container `div` and apply `display: flex;` to that container:

![](https://res.cloudinary.com/briandanger/image/upload/v1569400237/Screen_Shot_2019-09-25_at_4.25.05_AM_fde2wj.png)
![](https://res.cloudinary.com/briandanger/image/upload/v1569400237/Screen_Shot_2019-09-25_at_4.28.19_AM_ffw2b5.png)
![](https://res.cloudinary.com/briandanger/image/upload/v1569400238/Screen_Shot_2019-09-25_at_4.29.42_AM_r3cfpa.png)
