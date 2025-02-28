# Frontend Mentor - Blog preview card solution

This is a solution to the [Blog preview card challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/blog-preview-card-ckPaj01IcS). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Frontend Mentor - Blog preview card solution](#frontend-mentor---blog-preview-card-solution)
  - [Table of contents](#table-of-contents)
  - [Overview](#overview)
    - [The challenge](#the-challenge)
    - [Screenshot](#screenshot)
    - [Links](#links)
  - [My process](#my-process)
    - [Built with](#built-with)
    - [What I learned](#what-i-learned)
    - [Useful resources](#useful-resources)
  - [Author](#author)

## Overview

### The challenge

Users should be able to:

- See hover and focus states for all interactive elements on the page

### Screenshot

![Mobile View (Galaxy Z Fold 5)](./screenshots/Mobile%20View%20(Galaxy%20Z%20Fold%205).png)
![Desktop View](./screenshots/Desktop%20View.png)

### Links

- Solution URL: [Github Repo](https://github.com/amadoch/FMBlogPreviewCard)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

What do you do for grow this idea?
This time I started to implement a css framework the most popular I founded was boostrap, implement atomic design in css through the class atributes in the html, easy as that. 

So I read a round a hours the docs and started to mark the necesary element the first time, my result was I just lost the afternoon so I throw out the page and started a new one, this time I simpliefied in few step:
1. first what a i falied? 
- my mark flows in great block to litle size block, and using a framework what that in mind is bad cause the framework it's in charge to do the atomic parts for you, so my first solution was: flow in great block to size block.
2. I was to much semantic?
- Yes, I was a lot and I started believe thats as problem let me explain: I put the 60% of my effort on how about the browser can detect which part its fully w-aria and 30% reading how make a good practices and last 10% about the design and the requirements. 
So this time my solution was: that I have to focus the 60% or 68% on how is the design and what need to work in html and css, and later when i almost finished this I focus a 20% on how can be more semantic and 10% how about the optimizing.
3. Tried to go more far about grid or flexbox or media-queries, Tried to just focus on layouts
- The problem is was I a lot worried that bootstrap don't have css grid (they have one in beta phase) but I cheer up a little when i come to think what I worry if x or y what if try first draw on my mind or an white paper and descomposed the look of the page, so I take almost a 15 minutes but produce the final look of my page, take a while but think is more efficient that closed the eyes and fool around with clases.

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow
- [Bootstrap](https://getbootstrap.com/)

### What I learned

I happy to know that I can just specified the width of my component, for much time I think thas was a bad pratices but i see I was incorrect. See below:

```html
<article class="container bg-light p-3 rounded" style="max-width: 320px;">
```


### Useful resources

- [Modzilla Develeper Netowrk - CSS](https://developer.mozilla.org/en-US/docs/Web/CSS) - This helped me for XYZ reason. I really liked this pattern and will use it going forward.
- [Vercel](https://vercel.com/home) - This is an amazing site for deploy static sites which helped me. I'd recommend it for hosting your's projects.

## Author

- Website - [GitHub - amadoch](https://github.com/amadoch)
- Frontend Mentor - [@amadoch](https://www.frontendmentor.io/profile/amadoch)
