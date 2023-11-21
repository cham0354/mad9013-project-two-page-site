# Grade
HTML Code Quality: 1/5
CSS Code Quality: 3/5
Responsive Design: 1/5
Assignment Requirements: 2.5/5
Subtotal: 7.5/20

Late Penalty: -10% (-2pts)

Total: 5.5/20

## Comments

### HTML
There are numerous very serious errors in your html on both pages.
- You have extra `<!DOCTYPE html>`, `<html>`, `<head>` and `<body>` open/close tags. This will prevent content from being displayed correctly and break your site completely.
- You need to improve your indentation and spacing within your html. It is very challenging to read and understand your code.
  - This is likely leading to a number of the errors because it is difficult to see how elements are matched up and organized.

Search for `prof comment` in individual files for specific comments.


### CSS
- You should have one shared CSS file for both pages. By having separate files, you are unnecessarily repeating code and are making more work for yourself to maintain your styles and keep things consistent between pages.
- You should be using `min-width` media queries only. We work mobile-first in this program.
- Do not use `text-align: center;` on large blocks on content. It is more challenging to read. Stick with standard left aligned.

Search for `prof comment` in individual files for specific comments.

### Responsive Design
- There is no consistency in the width and alignment of different section's content. Ideally all sections should have the same width of container, and the same padding on the left and right, applied through the `.container`, to ensure everything lines up perfectly.
- Layout is not responsive

### Assignment Requirements
- A new Google font was not used.
  - You applied `Lato` (a Google font, but not properly linked, so not used) and `Arial` (not a Google font)
- CSS Variables should be used for applying colours.
  - Colour scheme was not fully changed from deliverables. The old colours are frequently seen in CSS file.