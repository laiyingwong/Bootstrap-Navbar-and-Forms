# Bootstrap Navbar and Forms

This project is a simple responsive demo that illustrates the use of a sticky navbar, a form layout and some basic utilities in Bootstrap.


## 🎉 Demo 

![app demo](Assets/navbar-forms.gif)


## ✨ What I Have Learned

With Bootstrap, a navbar can extend or collapse, depending on the screen size. A standard navbar is created with the `.navbar` class, followed by a responsive collapsing class: `.navbar-expand-xl|lg|md|sm` (stacks the navbar vertically on extra large, large, medium or small screens). To make a navbar stick to the top when scrolling, simply add `sticky-top` class as an addition.

To create a form, wrap labels and form controls in `<div class="form-group">` and add class `.form-control` to all textual `<input>`, `<textarea>`, and `<select>` elements. `form-row` can be used to optimize the default spacing/gutter size.

Padding (`p`) in Bootstrap has six sides: `t|b|l|r|x|y` (`x` represents left and right, and `y` represents top and bottom). Padding sizes ranging from `0` to `5`. The classes are used in the format: `p{sides}-{size}` for `xs` and `p{sides}-{breakpoint}-{size}` for `sm`, `md`, `lg`, and `xl`. The size will be applied to all four sides if no side is specified.

## 👏 Credits

This project is based on the <a href="https://getbootstrap.com/docs/4.6/getting-started/introduction/">Bootstrap Documentation<a/> and the Bootstrap tutorial of <a href="https://www.udemy.com/course/the-web-developer-bootcamp/">The Web Developer Bootcamp</a> by Colt Steele.
