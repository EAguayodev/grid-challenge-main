# Frontend Mentor - Bento grid solution

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

### Links

- Solution URL: [Github]()
- Live Site URL: [Vercel](https://grid-challenge-main.vercel.app/)

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Desktop-first workflow


### What I learned

In this challenge I had to amp up using css grid to have the deiv tags span across a section while attaining outcome close to the design.

```html
<div class="grid-item side-box schedule-create">
    <h2>Create and schedule content <span>quicker</span></h2>
    <img src="assets/images/illustration-create-post.webp" alt="post creation">
</div>
```
```css
.grid-row {
    width: auto;
    display: grid;
    padding: 4rem;
    grid-template: repeat(4, auto) / repeat(1, 16rem);
    gap: 2.8rem;
}
```

### Continued development

Will use css grid in other challenges if I have to.

### Useful resources

- [cssreference.io](https://cssreference.io/css-grid/) - this helped me find other ways to get the deisgn outcome using grid-template property you see in the css code snippet above.
## Author

- Website - [Eric Aguayo](https://www.ericaguayo.com)
- Frontend Mentor - [@yourusername](https://www.frontendmentor.io/profile/yourusername)