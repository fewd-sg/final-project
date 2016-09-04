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
- I like that you made the navigation links responsive as well, nice!
- Also realised your ad-unit in the sidebar is not an image, sneaky...
- To make your website fully responsive at the 768px breakpoint, you can try setting the container and sidebar to have a width of 100% instead of a fixed width.
- For the sidebar, you can combine the code for the headings by targeting `sidebar h3`, instead of giving classes to each of them. Same thing for the social icons, no need for `.facebook` and `.twitter`. You can lump the same code into one class, and apply to both.
