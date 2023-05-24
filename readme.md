# Note:
Please run this command to install node modules.
- npm install

# Design
- Implemented pixel perfect design for desktop and mobile using your provided assets
- Used LESS for CSS (as Magento 2 uses LESS for CSS)
- Installed and configured Grunt (a JavaScript compiler for LESS/SCSS) to compile LESS files into CSS
- Configured Grunt watch task so LESS files are immediately compiled to CSS
- If you want to see how Grunt is actually working, you may install this on your local server/machine
- Use command - 'grunt watch' or 'grunt' to run the compiler

# Followed these coding practices:
- Casing: kebab-case
- Use BEM syntax for custom CSS classes.
- Use Bootstrap utility classes mainly for layout and spacing, (see the Layout and Utilities sections of the documentation).
- Do not create custom utility classes (see custom Bootstrap variables and what can be overwritten from Bootstrap defaults for other options).
- Use CSS instead of utility classes for reused components. But this doesn't mean you can't use both, consider what will always be the same (CSS) and what may change e.6- spacing around the element (utility classes).
