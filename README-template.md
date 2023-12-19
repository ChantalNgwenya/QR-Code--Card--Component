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
- [Author](#author)
- [Acknowledgments](#acknowledgments)


## Overview

### Screenshot

![](./screenshot.jpg)

Add a screenshot of your solution. The easiest way to do this is to use Firefox to view your project, right-click the page and select "Take a Screenshot". You can choose either a full-height screenshot or a cropped one based on how long the page is. If it's very long, it might be best to crop it.

Alternatively, you can use a tool like [FireShot](https://getfireshot.com/) to take the screenshot. FireShot has a free option, so you don't need to purchase it. 

Then crop/optimize/edit your image however you like, add it to your project, and update the file path in the image above.


### Links

- Solution URL: [Chantal Ngwenya](https://github.com/ChantalNgwenya)
- Live Site URL: [Chantal's live site](http://127.0.0.1:5501/index.html)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow
- [Styled Components](https://styled-components.com/) - For styles

### What I learned

As a newbie in learning HTML and CSS , I'm pround that I get the hang of HTML. 
Throughout doing this project I learned how to style the image and to be at the center of the page. 
I learned how to link the font type into my stylesheet.

Always open to any comments.

```html
<h1>Some HTML code I'm proud of</h1>
  <link 
    rel="preconnect" 
    href="https://fonts.googleapis.com"
  >

<link
  rel="preconnect" 
  href="https://fonts.gstatic.com" crossorigin
>

<link
  rel="stylesheet"
  href="https://fonts.googleapis.com/css2?family=Outfit&display=swap" 
>
```
```css
body {
    font-family: 'Outfit', sans-serif;
	background-color: hsl(212, 45%, 89%);
	font-size: 15px;
	display: flex;
	flex-direction: column;
	align-items: center;
	justify-content: center;
	height: 100vh;
}

.container {
	background-color: hsl(0, 0%, 100%);
	box-shadow: 5px 5px 5px rgba(0, 0, 0, 0.05);
	border-radius: 0.625rem;
	max-width: 17rem;
	padding: 1rem;
	margin-bottom: 1rem;
}

img {
	width: 100%;
	border-radius: 0.625rem;
	max-height: 18rem;
	max-width: 18rem;
}
```

### Continued development

I want to create my own QR Generator so that this can be the standard template.

Links to documents or other content could be contained in the QR code. I am going to ponder on anything that might be helpful.

To also play arond css properties.

### Useful resources

- [Learn HTML](https://developer.mozilla.org/en-US/docs/Learn/HTML/Tables/Basics) - This is an amazing article which helped me understand HTML basics.


## Author

- Frontend Mentor - [@ChantalNgwenya](https://www.frontendmentor.io/profile/ChantalNgwenya)


## Acknowledgments

I got help on how to approach the project.
[Thomas](https://youtu.be/JFyMWwOxHYM?si=VlTKqYgJspuweGd7)

