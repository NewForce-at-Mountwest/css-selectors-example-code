## Lightning Exercise One

- Create a new directory called `html-day-one`.
- Inside that directory, create an `index.html` file and a `style.css` file
- Generate boilerplate HTML markup by holding down the `shift` key and pressing `!`
- Link your `style.css` file to your `index.html` file

## Lightning Exercise Two
- In your HTML file, between the body tags, create a footer element
- Give it a class of "blog-footer"
- Give it an id of "blog-footer-page-one"
- In `style.css`, select your footer element by its tag name and give it a background color of blue.
- Select the same footer element by its class of "blog-footer". This time give it a background-color of green.
- Select the same footer element by its id of "blog-footer-page-one". Give it a background-color of red.

## Lightning Exercise Three

1. In your index.html file, copy and pate the following code:

```html
<article>
  <h2>How to Write Really Good HTML</h2>
  <p>This is the first paragraph.<a href="#">Click here for more details</a></p>
  <p>This is the second paragraph</p>
  <p>This is the third paragraph</p>
  <img src="" alt="" />
  <a href="#">Another link that's a child of the article!</a>
  <p>This is the final paragraph</p>
</article>
```

2. Select any `a` elements that are inside a `p` element. Make their font color gray.
3. Select any `p` element that is a directly adjacent sibling of an `h2` element and give it a `background-color` of `lightblue`.
4. Select any `img` element that is a sibling of a `p` element and give it a `border-radius` of `30%`. (Doesn't need to be a directly adjscent sibling.)

## Lightning Exercise Four

1. Use the same HTML you copied and pasted before.
2. Use `:first-child` to select the h2 element that is the first child of the article element.
3. Use `:nth-child()` to select the paragraph element that's third child of the article element.
