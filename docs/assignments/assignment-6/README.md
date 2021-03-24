# Responsive: Assignment- 6
### Due March 31

In this assignment, you will incorporate CSS media queries into your current web project. Also, feel free to begin a new project.

Media Queries will allow your page to change based on whether a visitor to your site is using a smartphone, tablet, or desktop computer. With media queries, you can anticipate and design for a variety of viewing experiences. Next week, will add more sophisticated layout to your projects so don't save layout issues for next week.

Each of the web pages should include images and/or text and there should be clear navigation between each of the pages.

### Fluid Widths and Responsiveness

Making your content and images flexible is fairly straightforward. Use the following style rules to make images and content respectively scale to fit the size of their container.

e.g. `img {max-width: 100%;} or img {width: 100%;}`

e.g. `#about {width: 75vw; margin: 0 auto;}`

Try and focus on designing and developing for mobile first. This means using the developer console to control the look and feel of your content on smaller screens. We will be revisiting this in the next lesson when we learn more sophisticated methods of layout.

The resolution of computer displays also varies across devices. To optimize your raster graphics for screens with higher resolutions, you can offer larger alternates. To that end, create 2x versions at double the width and height of all your standard website images. Rather than scaling up the smaller image (which would result in lower quality), you should work with original image files to create the 2x versions. Then, use the HTML <img> element’s `srcset` attribute along with the src attribute to offer these to compatible browsers.

If you need to art direct some of your photos, feel free to use the `<picture>` element to supply and alternatively cropped image.

### Media Queries

Begin to integrate at least one media query with the `@media` rule into your code to set breakpoints for the layout and style changes: mobile devices, tablets, and/or desktop. This could also simply be mobile and desktop. It's up to you.

Since you’ll be optimizing your layout for different screen sizes, you should set the viewport on all pages to an initial scale of 1 to prevent smartphones and other devices from scaling pages down.

`<meta name="viewport" content="width=device-width, initial-scale=1.0">`

### Publishing Your Website

Upload your website to the i6 Unix server in its own directory. Test your files again once they are “live” on the Web server to make sure they are accessible. Update your assignments directory to link to this page.

### Submitting Your Assignment
Submit the following via NYU Classes. More information on submitting files with NYU Classes is also available here.

- The URL to your website on i6
- A compressed archive containing all the files of your website

### Grading
This assignment is worth 10 points.

- A fully optimized website for mobile devices (3 points)
- Mostly percentage or relative units should be used for all CSS widths (1 point)
- The viewport should be set on all pages and the CSS should include at least one `@media` query with a breakpoint to optimize the layout for different browser widths, including mobile and desktop (3 points)
- Images should be flexible with higher-resolution versions of all raster graphics offered in conjunction with the HTML `srcset` attribute (3 points)


**Extra credit**

- Website demonstrates extra effort and thoughtfulness (3 points)
- Website is well prepared for advanced layout techniques. (2 points)
