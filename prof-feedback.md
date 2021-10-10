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

## Week 4 ----------------------

Code Quality: 2.5/3
Design: .75/1
File Organization & Commits: .75/1
Total: 4/5

- The CSS should all be done in the `css/main.css` file. That way the styles will apply to all of your pages
- You `.platform-banner` and `.platform-p` both have `margin` on the sides. Because `margin` applies outside of the element, it is causing them to spill out of the container and miss-align. To create spacing on the side of elements, you should use `padding` instead as that create spacing inside the element and avoids this issue.
  - See included screenshot `feedback-screenshots/text-spilling-out.png`
- Make sure when adding the Google Font that you select all of the weights and styles you wish to use. For the `h3` & `h4` you have said you wanted to use `font-weight: 900;` but you did not include that font in you link from Google Fonts, so it cannot load it.
- Make sure to review your CSS to insure it is neat and organized, including:
  - remove empty lines inside of CSS rules
  - there should be a space between the selector and the opening curly bracket `{`
  - there should be a space between each ruleset
  - double check indentation 

## Week 5 ----------------------

Code Quality: 2.75/3
Design: .75/1
File Organization & Commits: 1/1
Total: 4.5/5

- Apply the `.container` class we created in class to the row to help create a more consistent layout. You are setting individual paddings on the header and footer, which is both inconsistent and extra repeated code from the `.container` class.
- Make sure you are double checking all the screen sizes. There are some alignment issues at the 360px with the button in the footer.