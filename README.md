# Responsive-Portfolio
using no bootstrap
Inside your Responsive-Portfolio folder, find your styles.css file. You will write your media queries at the bottom of styles.css.


Use three @media screen tags, each with one of these max-widths: 980px, 768px and 640px.


You use 980px because you never want any of the content to be cut off. Since the desktop layout is about 960px wide, you want the media queries to kick in before your content gets cut off.


768px is about the width of a tablet and 640px is about the width of a phone in landscape.




Make the layout match the following screenshots:


index.html: 980px, 768px, 640px


portfolio.html: 980px, 768px, 640px


contact.html: 980px, 768px, 640px




Make the position of the header static (the default positioning) when the screen is 640px wide. The header design takes up a lot of room; you don't want it to stick to the top of a small screen and leave no room for the rest of your site.


Be sure to include the viewport tag in all your HTML files, otherwise your media-queries won't function as expected on mobile devices.
