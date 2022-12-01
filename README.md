# Frontend Mentor - QR code component solution

This is a solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [Screenshot](#screenshot)
  - [Links](#links)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)


## Overview

### Screenshot

![](QR%20Code_desktop.png)
![](./mobile-preview.jpg)


### Links

- Solution URL: (https://github.com/Noorulsaliha/qr-code-component.git)
- Live Site URL: (https://saliha-qr-code-component.netlify.app/)


### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox


### What I learned

At first, it was very difficult to understand the organized code to complete this project. As long as I know some HTML tags and CSS properties then, I mindmapped the total structure of What I'm going to code and How the outcome will be like. After Many trial and error I have done it.


```html
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="styles.css">
    <link rel="icon" type="image/png" sizes="32x32" href="favicon-32x32.png">
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Outfit:wght@400;700&display=swap" rel="stylesheet">
    <title>QR code component</title>
</head>

<body>
    <div class = "card">
        <img class="qr-code" src="image-qr-code.png" alt= "Image of QR code" width= "285" height = "285"/>
        <h1>Improve your front-end skills by building projects</h1>
        <p>Scan the QR code to visit Frontend Mentor and take your coding skills to the next level</p>
    </div>
</body>  
```

```css
.card{
    background-color: hsl(0, 0%, 100%);
    box-shadow: 5px 5px 5px rgba(0, 0, 0, 0.1);
    border-radius: 0.625rem;
    max-width: 17rem;
    padding: 1rem;
    margin-bottom: 1rem;
}

	body{
    background-color: hsl(212, 45%, 89%);
    font-size: 15px;
    font-family: 'Outfit', sans-serif;
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
    height: 100vh;
}

```

### Continued development
With the help of this project, I can able to customize and add new features to the website or apps (QR Code). It'll be very helpful for my dev journey

### Useful resources

- [W3Schools](https://www.w3schools.com/) - This website helped me to recap HTML and CSS fastly.


## Author

- Frontend Mentor - [@Noorul Saliha](https://www.frontendmentor.io/profile/Noorulsaliha)

