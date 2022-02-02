# Coding Challenge Markdown.

## This is a coding challenge to build a responsive site based on a reference PSD file. 

### Notes for the build were as follows

- Ignore the custom fonts and use Arial as the base font
- Use HTML5 and CSS3
- Use media queries in your SASS for breakpoints
- Do not use bootstrap


### My Steps:

1. Because I needed to extract the images, text, logo, I opened the file in photoshop to extract those items from their respective layers. I saved them in .png format.
2. I created an appropriate file structure for the site folder and linked all css, scss, js. 
3. I blocked out the html code linked the images and copy and pasted the text.
4. Because different browsers have their own default formatting, I used a CSS reset by [meyerweb.com](https://meyerweb.com/eric/tools/css/reset/) to put them all on the same playing field.
5. I styled with Sass (.scss) as Sass code can be structured better.
6. I used a screen color picker to get the correct RGB colors from the reference file and saved them into Sass variables.
7. I made sure to make the site as responsive for both Desktop and Mobile devices by using techniques such as flexbox and Media Query. The reference file showed that the largest image I could extract was 1280px. I forced to image to expand and shrink with browser resizing.
8. The reference for the mobile version spanned 320px. I added an @media break at 600px to split the 3 images that were horizontally stacked and have them stacked vertically. I added another @media break at 420px to change the main banner photo to a more appropriate size as the original scales down too small.
9. I added alt text to img tags for screen readers. Cleaned up the code.
10. I tested all major mobile devices from apple and samsung tables to phones as well.


## Reference Files:

![Desktop Reference Image](/images/reference/desktopReference.png)

<img src="/images/reference/mobileReference1.png" alt="Mobile Reference 1" width="321" height="696" />
<img src="/images/reference/mobileReference2.png" alt="Mobile Reference 1" width="321" height="1123" />
