### Homework Completion
- [x] Use in-line-block or floats in your CSS to achieve a two-column layout
- [x] Use the correct Open Sans Google Font typeface to style the text denoted in the design file and according to the JPEG provided
- [x] Use proper filename conventions (lowercase, .html)
- [x] Use a single external CSS stylesheet to style all pages
- [x] Add a hover effect to all the links using pseudo-classes
- [x] Integrate drop caps using pseudo-classes
- [ ] Use media queries at a 768px breakpoint
- [x] Content remains in appropriate divs
- [x] Content remains visible to the user
- [x] Fonts change size appropriately
- [x] Margins and padding change size appropriately
- [x] Content does not overlap
- [x] In the blog section, the two-column layout changes to a single-column layout when appropriate
- [ ] Bonus: Add more media queries for a 1000px breakpoint and a 480px breakpoint

### Homework Comments
- You have just media queries missing from your homework! Add a 768px breakpoint by adding the following:

```css
@media (max-width: 768px) {
  main {
    /* css styling for the layout at this breakpoint */
  }
}
```

- You can add drop caps using pseudo-classes, by adding `p:first-letter` to your CSS.

- You can also simplify your **Sign up now** button to this: http://codepen.io/calvintan/pen/GqLrbq
