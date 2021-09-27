# Professor Feedback

## Week 2B ----------------------

Overall, great start! A few small changes:

- You do not need the HTML folder. You `index.html` file should be immediately inside of your main project folder.
- `href` and `src` are case sensitive. Folders and files should all be lowercase to avoid case related errors in linking. 
- You <nav> should be inside the <header>. You are also missing the closing tag for the <nav>
- the <h1> should be wrapped around the <img> inside the <header>, the "Community feel" heading should be an <h2>
- The logo bar <ul> should be in its own separate <section> from the main banner
- the "Join now..." banner should be in a separate <section> from the "design your brand..." content
- The white logo should be in the footer
- The logos in the header/footer should be wrapped in an <a> linking to the home page
- The `alt` attributes on <img> are going to be read by screen readers and some users. You should use proper capitalization in them.

## Week 3 ----------------------

Great work! Here are a few tips to help simplify things up and improve consistency:

- You can simplify your button styles. You've created two separate classes and have duplicated a number lines of code. To simplify, create on `.btn` class that creates the basic button styles and then create a second `.btn-white` that changes to colour to white. This will help keep things consistent as well.
  - also, numbering your classes will end up being confusing. You should use descriptive class names to make it easier to understand such as `.btn-white`
- The same concept can be applied to the banners as a whole. create a basic `.banner` class that applies basic styles like alignment, color, etc. Then use a secondary class to apply overrides for padding and image.
- You can simplify your use of selectors and classes as well. You've created classes `.banner-h2` and `.banner-p`, which works, however a selector of `.banner h2` and `.banner p` would work as well and then not require adding classes in your HTML.
  - NOTE: there is nothing wrong with your version. There are different philosophies for how to name elements with classes and this is totally valid. I am just pointing out if you want to simplify things, you can.