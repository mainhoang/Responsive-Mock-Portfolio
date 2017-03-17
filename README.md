# Responsive-Portfolio

UCLA Extension Bootcamp - Homework # 2.1

### Overview

In this assignment, you'll create two different portfolios. The first will be an update of the one you made last week&mdash;you'll enhance this one with a mobile-responsive layout. For your second portfolio, you’ll build a layout with the Bootstrap CSS framework.

### Instructions

1. Create two new GitHub repositories and name them `Responsive-Portfolio` and `Bootstrap-Portfolio`.
2. Clone these repositories to your computer.
3. Copy the contents of `Basic-Portfolio` (your first homework solution) and paste the mentioned files into `Responsive-Portfolio`.
  * Note: Be sure not to include any dot files (e.g .git, .gitignore for example) from the `Basic-Portfolio` repo.
  * If you chose the `Skeleton` exercise for your first homework assignment, contact a TA, who will provide you with a template for your portfolio.
4. Inside your `Responsive-Portfolio` folder, find your `styles.css` file. You will write your media queries at the bottom of `styles.css`.
  * Use three `@media screen` tags, each with one of these `max-width`s: `980px`, `768px` and `640px`.
    * You use `980px` because you never want any of the content to be cut off. Since the desktop layout is about 960px wide, you want the media queries to kick in before your content gets cut off.
    * `768px` is about the width of a tablet and `640px` is about the width of a phone in landscape.

5. Make the layout match the following screenshots:
  * `index.html`: [980px](Images/980-index.jpg), [768px](Images/768-index.jpg), [640px](Images/640-index.jpg)
  * `portfolio.html`: [980px](Images/980-portfolio.jpg), [768px](Images/768-portfolio.jpg), [640px](Images/640-portfolio.jpg)
  * `contact.html`: [980px](Images/980-contact.jpg), [768px](Images/768-contact.jpg), [640px](Images/640-contact.jpg)

6. Make the position of the header `static` (the default positioning) when the screen is `640px` wide. The header design takes up a lot of room; you don't want it to stick to the top of a small screen and leave no room for the rest of your site.

7. Be sure to include the `viewport` tag in all your HTML files, otherwise your media-queries won't function as expected on mobile devices.

8. **Protip**: Use the Chrome extensions [Window Resizer](https://chrome.google.com/webstore/detail/window-resizer/kkelicaakdanhinjdeammmilcgefonfh) and [Browser Width](https://chrome.google.com/webstore/detail/browser-width/mlnegepkjlccabakompdmbcmdieaideh) to see the browser dimensions in Chrome.

### Technologies Used

* HTML
* CSS
* Responsive Web Design w/Media Queries

