# Frontend Mentor - FAQ accordion solution

This is a solution to the [FAQ accordion challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/faq-accordion-wyfFdeBwBz). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 


### Screenshot

![](/design/desktop-design.jpg)

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox




### What I learned

I lerned how to make FAQ accordion without Javascript. I use semantic html such as:

```html
<details>
  <summary>
    <p>Is Frontend Mentor free?</p>
    <img src="/assets/images/icon-plus.svg" alt="" aria-hidden="true"> 
  </summary>
  <p>
    Yes, Frontend Mentor offers both free and premium coding challenges, with the free 
    option providing access to a range of projects suitable for all skill levels.
  </p>
</details>
```

To change the image icon when the details are opened, i use css. Like that:
```css
summary {
  position: relative;
  padding-right: 2em;
  cursor: pointer;
}

summary::after {
  content: url('/assets/images/icon-plus.svg');
  position: absolute;
  right: 0;
  top: 0;
}

details[open] summary::after {
  content: url('/assets/images/icon-minus.svg');
}
```

We have to remove the images in the HTML.

## Author

- Website - [Nitiema Allassane](#)
- Frontend Mentor - [@NitiemaDev](https://www.frontendmentor.io/profile/NitiemaDev)


## Acknowledgments

Thanks to frontend Mentor !