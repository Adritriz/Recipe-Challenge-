# Frontend Mentor - Recipe page solution

This is a solution to the [Recipe page challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/recipe-page-KiTsR8QQKm). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Frontend Mentor - Recipe page solution](#frontend-mentor---recipe-page-solution)
  - [Table of contents](#table-of-contents)
  - [Overview](#overview)
    - [Links](#links)
  - [My process](#my-process)
    - [Built with](#built-with)
    - [What I learned](#what-i-learned)
    - [Continued development](#continued-development)
 

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview


### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox

### What I learned

Use this section to recap over some of your major learnings while working through this project. Writing these out and providing code samples of areas you want to highlight is a great way to reinforce your own knowledge.

To see how you can add code snippets, see below:


```css
ul li::marker,
ol li::marker {
    color: var(--NUTMEG-COLOR);
    font-weight: bold;
}

.section:not(:has(table)) {
    border-bottom: var(--BORDER-BOTTOM);
}

.table tr >* {
    text-align: left;
  /*   border: 1px solid red; */
    padding: var(--TABLE-PADDING);
}

.table tr:not(:last-child) >* {
    border-bottom: var(--BORDER-BOTTOM);
}
```


If you want more help with writing markdown, we'd recommend checking out [The Markdown Guide](https://www.markdownguide.org/) to learn more.

### Continued development

I struggled the most with figuring out how to do the table for the nutrition info, I am not satisfied with how I coded it. It works, but I can improve to make it responsive in all devices. There was many things I was unsure of, but it worked out well in the end. I am especially proud of my coding for changing the marker colors for the ul and ol, and figuring out how to make the certain areas not have a border bottom without creating a class (I used the :not and the :has pseudo classes). I also did not code for mobile design first so that's something I want to focus on for future projects in order to make responsive layouts. 


