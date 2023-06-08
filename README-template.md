# Frontend Mentor - Product preview card component solution

This is a solution to the [Product preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/product-preview-card-component-GO7UmttRfa). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover and focus states for interactive elements

### Screenshot

![](./screenshot.jpg)

Add a screenshot of your solution. The easiest way to do this is to use Firefox to view your project, right-click the page and select "Take a Screenshot". You can choose either a full-height screenshot or a cropped one based on how long the page is. If it's very long, it might be best to crop it.

Alternatively, you can use a tool like [FireShot](https://getfireshot.com/) to take the screenshot. FireShot has a free option, so you don't need to purchase it. 


Then crop/optimize/edit your image however you like, add it to your project, and update the file path in the image above.


**Note: Delete this note and the paragraphs above when you add your screenshot. If you prefer not to add a screenshot, feel free to remove this entire section.**


## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow

**Note: These are just examples. Delete this note and replace the list above with your own choices**

### What I learned

Use this section to recap over some of your major learnings while working through this project. Writing these out and providing code samples of areas you want to highlight is a great way to reinforce your own knowledge.

To see how you can add code snippets, see below:

```html
<div class="image">
  <img src="./images/image-product-desktop.jpg" alt="">
</div>
<div class="text">
  <p class="head">PERFUME</p>

  <h1>Gabrielle Essence Eau De Parfum</h1>

  <p>A floral, solar and voluptuous <br>
  interpretation composed by <br>
  Olivier Polge, Perfumer-Creator <br>
  for the House of CHANEL
  </p>

  <div class="price">
    <p class="price1">$149.99</p>
    <p class="price2">$169.99</p>
  </div>

  <button><img src="./images/icons8-cart-32.png" alt="" height="32" width="32"> Add to Cart</button>
</div>

I'm quite proud of this part of my code mainly because i was having quite an issue with the <img> tag, i was debating between using <picture> tag but it wasn't working but this was the closest thing to what i wanted.
```

```css
@media screen and (max-width:375px) {
  body {
    width: 375px
  }

  .container {
    height: 900px;
    width: 300px;
    display: block;
    margin: 40px;
  }

  button { display: block;
   justify-content: center;
    width: 95%;
  }

  button img {
    margin-bottom: -10px;
  }
}

I'm not really proficient in media queries and all I know about it is from the internet but from my little knowledge I was able to accomplish this.😊
```

If you want more help with writing markdown, we'd recommend checking out [The Markdown Guide](https://www.markdownguide.org/) to learn more.

**Note: Delete this note and the content within this section and replace with your own learnings.**

### Continued development

Use this section to outline areas that you want to continue focusing on in future projects. These could be concepts you're still not completely comfortable with or techniques you found useful that you want to refine and perfect.

-I want to work more on Media Query.- 

**Note: Delete this note and the content within this section and replace with your own plans for continued development.**

### Useful resources

- [Example resource 1](https://www.example.com) - This helped me for XYZ reason. I really liked this pattern and will use it going forward.
- [Example resource 2](https://www.example.com) - This is an amazing article which helped me finally understand XYZ. I'd recommend it to anyone still learning this concept.

**Note: Delete this note and replace the list above with resources that helped you during the challenge. These could come in handy for anyone viewing your solution or for yourself when you look back on this project in the future.**

## Author

- Frontend Mentor - [@yeyelovep2](https://www.frontendmentor.io/profile/yeyelovep2)
- Twitter - [@yeyelovep](https://www.frontendmentor.io/profile/yeyelovep2)
- Github - [@yeyelovep2](httpsc://github.com/yeyelovep2)
**Note: Delete this note and add/remove/edit lines above based on what links you'd like to share.**

