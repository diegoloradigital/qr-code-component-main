# Frontend Mentor - QR code component solution

This is a solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
  - [AI Collaboration](#ai-collaboration)
- [Author](#author)

## Overview

Simple card component displaying the image of a QR Code.

### Screenshot

![QR Code Component - Mobile](./images/screenshot.png)

### Links

- Solution URL: [https://github.com/diegoloradigital/qr-code-component-main](https://github.com/diegoloradigital/qr-code-component-main)
- Live Site URL: [https://diegoloradigital.github.io/qr-code-component-main/](https://diegoloradigital.github.io/qr-code-component-main/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow

### What I learned

`<article>` tag is better used for self-contained pieces of content that could stand alone, such as a blog post, a card or a product listing. I could also use a `<div>` instead.

Using `<span class="nowrap">` to avoid text wrapping when the card shrink is a better practice than using `<br>`.

You can hide Claude Code right panel using `command + option + b`. The file tree left panel can be hide with `command + b`.

I learnt how to write properly md files, because are required to edit this README.md.

#### Simple QR Component

```html
<article>
  <img
    src="/images/image-qr-code.png"
    alt="QR code that links you to Frontend Mentor's website"
  />
  <h1>
    <span class="nowrap">Improve your front-end</span>
    <span class="nowrap">skills by building projects</span>
  </h1>
  <p>
    <span class="nowrap">Scan the QR code to visit Frontend</span>
    <span class="nowrap">Mentor and take your coding skills</span>
    <span class="nowrap">to the next level</span>
  </p>
</article>
```

#### Utility Class

```css
.nowrap {
  white-space: nowrap;
}
```

### Continued development

I want to keep practicing semantic tags and accessibility best practices with aria-label, aria-labelledby, role, and alt attributes because I understand the concept but haven't had enough project experience with more variety. Let's see in the upcoming projects how I can develop more intuition.

### Useful resources

#### Learning Materials

- [GitHub pages tutorial](https://www.youtube.com/watch?v=5XhxR9Vs6zc) - Tutorial I used to deploy this website.
- [Git and GitHub tutorial (in Spanish)](https://www.youtube.com/watch?v=mBYSUUnMt9M&t=4931s) - You will learn how to clone, push and pull a repo. Begginer friendly and there is an overview of terminology and concepts in the first part.

#### UI Tools

- [Box Shadow Generator](https://html-css-js.com/css/generator/box-shadow/) - Use for to create box shadow in a visually way instead of hardcoding pixels by guess.

### AI Collaboration

First, I tried using Claude Code, but I did not like how the interaction feels compare to Claude Chat on the desktop app. I ask in both tools the following questions:

1. What is the difference between using `<article>`, `<figure>`, `<section>`, and `<div>`? Give me examples of how to use these tags correctly and incorrectly.
2. Provide me with a theory overview of the `aria-label` and `aria-labelledby` attributes inside HTML tags.

I realize that Claude Code is not that efficient to make reviews of theory, it is good to create boilerplate code, refactor specific parts and provide cognitive friction. But chat is better as a tutor making overviews, cheat sheets and providing better visuals.

## Author

- Frontend Mentor - [@diegoloradigital](https://www.frontendmentor.io/profile/diegoloradigital)
- X - [@diego_lora\_](https://x.com/diego_lora_)
