# Frontend Mentor - Huddle landing page with single introductory section solution

This is my solution to the [Huddle landing page with single introductory section challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/huddle-landing-page-with-a-single-introductory-section-B_2Wvxgi0).

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
- [Acknowledgments](#acknowledgments)

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the page depending on their device's screen size
- See hover states for all interactive elements on the page

### Screenshot

![](./screenshot.jpg)

A screenshot of my solution.

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process
Day 1 - 6/25/2021
- Starting off with the HTML. Building the skeleton of the page first. Making sure everything is semantic. Using the reference photos as a guide.
- Found some free icons to use for the social media links via [bootstrap](https://icons.getbootstrap.com/).
- After finishing the HTML, I contemplated using sass but I don't really know how to start using sass. I downloaded it a while ago but I haven't figured out how to use it... So I'm just going to use basic CSS for this project. I really just want to finish something today!
- After starting the css and checking my progress vs the reference image, I realized I forgot to add the illustration mockups lol.
- Changed the color of the social media and logo SVGs to match the font color I set.
- I forgot to start the css with a mobile media query. I honestly forgot how to use media queries so I'm reading a guide from [css tricks](https://css-tricks.com/a-complete-guide-to-css-media-queries/).
- Deleted the Bootstrap icons and replaced them with Font Awesome icons so I can change the color on hover. Gave the icons a border, but for some reason facebook's border looks weird. I'm not sure how to fix that but I have a headache so I'm gonna finish here for now. I finished the mobile css! I forgot to update this log as I was working though. I'll keep a better log next time.
Day 2 - 6/26/2021
- Today I'm going to start and finish the css for the desktop view. I'm moving the html,body, main, h2, p, button, icon, and about/attribution css styles outside of the media queries because it makes sense. The only thing that should be inside the media queries is css specifically for that targeted viewport. So the mobile background SVG and desktop background SVG should be in the mobile and desktop media queries respectively.
- In the main section, I moved the illustration and text + button in their respective divs since I'm using flexbox.
- I finished the desktop css. Now I'm focusing on responsiveness. Making sure the imgs and text shrinks when I resize my window.
- I'm creating a gh-pages branch so I can check the responsiveness using [browserstack](https://www.browserstack.com/).

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow

### What I learned

Before I start my next project, I need to look at the images and style guide first then plan how I'm going to complete it. I just started this project without properly planning and ended up very disoriented. Also need to ask someone to help me figure out how to use sass.

```html
<h1>Some HTML code I'm proud of</h1>
```
```css
.proud-of-this-css {
  color: papayawhip;
}
```

### Continued development

Use this section to outline areas that you want to continue focusing on in future projects. These could be concepts you're still not completely comfortable with or techniques you found useful that you want to refine and perfect.

### Useful resources

- [CSS Reset](https://piccalil.li/blog/a-modern-css-reset/) - I searched the Frontend Mentors slack looking for a css reset and found this one that Grace recommended.
- [Media Queries](https://css-tricks.com/a-complete-guide-to-css-media-queries/) - I forgot how to use media queries and this helped!

## Author

- Website - [Add your name here](https://www.your-site.com)
- Frontend Mentor - [@yourusername](https://www.frontendmentor.io/profile/yourusername)
- Twitter - [@yourusername](https://www.twitter.com/yourusername)

## Acknowledgments

This is where you can give a hat tip to anyone who helped you out on this project. Perhaps you worked in a team or got some inspiration from someone elses solution. This is the perfect place to give them some credit.
