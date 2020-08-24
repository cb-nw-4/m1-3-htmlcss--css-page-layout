# 1.2 - CSS: Page Layout - Workshop

## Exercise 2

Create an `index.html` file and a `style.css` file that reproduces the following:

![exercise-2 goal](../../__lecture/assets/ex-2-goal.gif)

### Reference

Your HTML should have the following structure:

```html
<!DOCTYPE html>
<html>
  <head>
    <link rel="stylesheet" type="text/css" href="style.css" />
  </head>
  <body>
    ...
  </body>
</html>
```

- Set the body margin to 0
- Give the `<body>` a `0` margin.
- Use the Poppins font (google fonts)
  - Go to google fonts and look for it, follow the instructions.
  - You will have to add a `<link>` tag in the head of your HTML file.
- The apple icon is in the imgs folder.
- You will need to use `display: block` or the icon won't be aligned (inline elements are affected by line-height which is not 0 by default)
- The background color for the navbar is `#3a3633`
- To remove the default underline style on anchor tags you can use `text-decoration: none`
- You can use the `href="#"` attribute on `<a>` to make the anchor tags behave like links (with hand cursor). `#` refers to the current page (so the link will just reload the page)
- You will need to use the `:hover` pseudo selector on the navbar links and change the opacity.
- In order to have a smooth transition for the opacity, you will need to use the `transition` css property.
  - Recommended transition time is **0.2s** and easing function is _ease-in-out_

Note - You can use the child selector in your css to apply a style to all your links, e.g.

```css
.nav > a {
  /* CSS CODE */
}
```

### Properties Needed

```
padding
background-color
align-items
justify-content
color
margin
font-family
text-decoration
transition
display
opacity
:hover
```
