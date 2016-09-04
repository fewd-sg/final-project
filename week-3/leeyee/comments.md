### Homework Completion
- [x] Use in-line-block or floats in your CSS to achieve a two-column layout
- [x] Use the correct Open Sans Google Font typeface to style the text denoted in the design file and according to the JPEG provided
- [x] Use proper filename conventions (lowercase, .html)
- [x] Use a single external CSS stylesheet to style all pages
- [x] Add a hover effect to all the links using pseudo-classes
- [x] Integrate drop caps using pseudo-classes
- [x] Use media queries at a 768px breakpoint
- [x] Content remains in appropriate divs
- [x] Content remains visible to the user
- [x] Fonts change size appropriately
- [x] Margins and padding change size appropriately
- [x] Content does not overlap
- [x] In the blog section, the two-column layout changes to a single-column layout when appropriate
- [x] Bonus: Add more media queries for a 1000px breakpoint and a 480px breakpoint

### Homework Comments
- Great work Leeyee, loved that you made use of `[id^="read"]` selector, figure with captions, and made use of jQuery as well.

- Some pointers: when you get to 768px breakpoint, you can modify the nav Relaxr h1 from `padding-left: 45%` to `text-align: center`. Same goes for the `nav ul li`. Another tip is that you can apply spacing between `li` like this, so that you're last `li` doesn't have margin-right:

```css
nav ul li + li {
  margin-left: 20px;
}
```

- If you would like to try a pure javascript way of making the text hide and appear, you could try this: http://codepen.io/calvintan/pen/EgajEj
