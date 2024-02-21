# FullStack Anderson

Welcome,

This repository contains the codebase for my personal CV website. This website serves as an online resume showcasing my skills, experience, and projects. It's designed to provide visitors with a comprehensive overview of my professional background and expertise as well as highlighting a interest in making websites accessible.

## Technologies Used
**HTML:** Used for structuring the content of the web pages.
**CSS:** Used for styling the web pages and making them visually appealing.
**JavaScript:** Used for interactivity and dynamic content.
**Git:** Version control system for tracking changes and collaborating with others.
**GitHub Pages:** Hosting platform for deploying the website.

## Wireframes
![index-mobile](https://github.com/LaurieAnderson92/FullStack-Anderson/assets/155463443/0f70177f-5218-404e-a4d1-dc176310f497)
![index-pc](https://github.com/LaurieAnderson92/FullStack-Anderson/assets/155463443/c3ae0d10-76c9-49b4-ae5c-791b63da4271)

## Structure
index.html: The landing page of the website, containing an overview of my profile and links to different sections in the header
experience.html: The page detailing all of my learning and professional experience 
references.html: The page listing two of my most recent references publicly available on my l, and links to their linked in pages
callback.html: the page to submit a callback request regaring a project
404.html: A page made to alert the user they have gone into an inactive link.

assets: Directory containing CSS stylesheets, JavaScript files, images, and other resources used in the website.

## Color Pallate:
A7BDCE
677B7F
1F262D
4C78AA
69B6C4

## Setup:
A section was used rather than a footer so that it can move up the screen in browser view and from the contacts section

## Deployment:
Git Hub Pages

## Testing:
Test the website locally by opening the HTML files in multiple web browsers to ensure everything displays correctly, in testing with myself and others a number of enhancements were suggested:

Enhancement1: Make the download button the complete anchor
Status: Done

Enhancement2: Image position on each content could be better
Status: Disagree, happy with current image placements

## Validation
all .html pages pass official W3C Validator: https://validator.w3.org/#validate_by_input
styles.css passes the oficial W3C CSS validator (Jigsaw): https://jigsaw.w3.org/css-validator/

## Bugs/Issues:

Bug1: The Title box displays over the nav-toggle window
Fix: deployed a Z Axis and moved nav toggle window to be inline with convention

Bug2: The title-picture is displaying above the title-box
Fix: Used flex box and absolute positioning

Bug3: title-picture seems to be cut off, not a perfect circle
Fix: Unable to reproduce as of 20/02/2024

Bug4: title-picture was being overlapped by conact bar on large screens
Fix: moved title picture to left and into title more to appear more like a profile

Bug5: Sensitive information in contact menu
Fix: Replaced with Placeholder text

Bug6: Website not responsive for 4k resolution
Fix: added divs to either side to keep site compact on 4k screens, limited the centre div to 1440px max, the left and right divs are using Flex Grow

Bug7: Hover colour not contrasting enough
Fix: changed colour to stronger contrast

Bug8: Hover colour appearing
Fix: Changed order in style.css, made color inherit

Bug9: CV link broken
Fix: changed name of file to fit convention, replaced path with valid directory

## Future Features:
- Diffrent CSS for lightmode/darkmode

## Acknowledgments
Google Fonts: https://fonts.google.com/
Currently haven't choses a font yet, But i plan to once I build less and design more

Font Awesome: https://fontawesome.com/
For the comprehensive collection of icons used throughout the website.

GitHub Pages: https://pages.github.com/
For hosting the website for free.

Pexels: https://www.pexels.com/photo/data-codes-through-eyeglasses-577585/ https://www.pexels.com/photo/code-on-a-screen-4383298/
photos uploaded by users to the free imaging hosting website pexels:
Kevin Ku 
Brett Sayles
Anete Lusina
Pixabay
Mikhail Nilov

Colormind: http://colormind.io/image/
Helping create a colour sceme based off my hero image

Coloring for Colorblindness: https://davidmathlogic.com/
Helping me choose a color scheme for each content page that's fulkly accessable

Favicon IO: https://favicon.io/emoji-favicons/nerd-face
software to make a freeuse favicon

Kim Britnell: https://www.linkedin.com/in/kimbritnell/
For proof reading and suggesting edits to the text content