## Lightning Exercise One
1. Create an `index.html` file
2. In your `index.html` file, use the shift + ! shortcut to generate boilerpalte html
3. In your HTML file, between the body tags, create an h1 element and give it the text of "My Blog"
4. Give your html element a class of "header"
5. Give it an id of "page-title"
6. Create a file called `style.css`
7. Link your CSS file to your HTML document.
8. In `style.css`, select your `h1` element by its tag name and give it a `background-color` of blue.
9. Select the same h1 element by its class of "header". This time give it a `background-color` of green.
10. Select the same h1 element by its id of "page-title". Give it a background-color of red.

## Lightning Exercise Two
1. In your index.html file, copy and pate the following code:
```html
 <article>
    <h2>How to Write Really Good HTML</h2>
    <p>This is the first paragraph.<a href="#">Click here for more details</a></p>
    <p>This is the second paragraph</p>
    <p>This is the third paragraph</p>
    <img src="" alt="">
    <a href="#">Another link that's a child of the article!</a>
    <p>This is the final paragraph</p>
  </article>
```
2. Select any `a` elements that are inside a `p` element. Make their font color black.
3. Select any `p` element that is a direct sibling of an `h2` element and give it a `background-color` of `lightblue`.
4. Select any `img` element that is a sibling of a `p` element and give it a `border-radius` of `30%`.

## Lightning Exercise Three
1. Use the same HTML you copied and pasted before.
2. Use `:first-child` to select the h2 element that is the first child of the article element.
3. Use `:nth-child()` to select the paragraph element that's third child of the article element.