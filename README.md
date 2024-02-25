# FullStack Anderson

Welcome,

This repository contains the codebase for my personal CV website. This website serves as an online resume showcasing my skills, experience, and projects. It's designed to provide visitors with a comprehensive overview of my professional background and expertise as well as highlighting a interest in making websites accessible.

## Setup

### Technologies Used:
* **HTML:** Used for structuring the content of the web pages.<br>
* **CSS:** Used for styling the web pages and making them visually appealing.<br>
* **JavaScript:** Used for interactivity and dynamic content.<br>
* **Git:** Version control system for tracking changes and collaborating with others.<br>
* **GitHub Pages:** Hosting platform for deploying the website.<br>

### Wireframes
![index-mobile](assets/documentation/index-mobile.png)
![index-pc](assets/documentation/index-pc.png)

### Structure
* **index.html:** The landing page of the website, containing an overview of my profile and links to different sections in the header<br>
* **experience.html:** The page detailing all of my learning and professional experience <br>
* **references.html:** The page listing two of my most recent references publicly available on my LinkedIn, and links to their linkedIn pages<br>
* **callback.html:** The page to submit a callback request regaring a project.<br>
* **404.html:** A page made to alert the user they have gone into an inactive link.<br>
* **assets:** Directory containing CSS stylesheets, JavaScript files, images, and other resources used in the website.<br>

### Color Pallate:
I used [Colormind](http://colormind.io) to create a color palete based off my hero image, then tweeked the colors to make them higher contrast of each other.
![Color Palate: #f0ffff, #5f9ea0, #00c8f4, #374a4e, #0c1e22 ](assets/documentation/color-palette.PNG)

### Deployment:
Currently the website is deployed in Git Hub Pages: https://laurieanderson92.github.io/FullStack-Anderson/<br>
To deploy this page locally, you can download the files from https://github.com/LaurieAnderson92/FullStack-Anderson and run it on a brownser in your machine.<br>

## Features

### User Stories:
* When a user first views the website, they'll want to immediately know what it is.
* When a user navigates the website, it should be obvious and intuative.
* If the user wants to find The link to the CV, it should be prominent and obvious.
* If a user views the github respository to view the quality of the code, it should be well commented and organised.
* For a user the style should be visually consistent and appealing.

### Delivery:
// List of existing features in the webpage 

### Future Features:
* Diffrent CSS for lightmode/darkmode
* Expand on the contact form and link it to an email inbox
* Expand on the projects with links to them in the portfolio
* Add visual interest in the dives in 4k resolution

## Quality Assurance

### Testing:
Test the website locally by navigating to the link: https://laurieanderson92.github.io/FullStack-Anderson/ 
in multiple web browsers and inspecting the page. Then changing the width of the page with the built in responsive design modee to ensure each page displays correctly.<br>

| **Width**     | __Chrome__ | __Firefox__ | __Edge__ | __Safari__|
| -----------:  | :--------: | :---------: | :-----:  | :-------: |
| **320px**     |     ✓     |     ✓       |     ✓    |     ✓    |
| **375px**     |      ✓    |     ✓       |     ✓    |     ✓    |
| **425px**     |       ✓   |     ✓       |     ✓    |     ✓    |
| **768px**     |        ✓  |     ✓       |     ✓    |     ✓    |
| **1024px**    |     ✓     |     ✓       |     ✓    |     ✓    |
| **1440px**    |      ✓    |     ✓       |     ✓    |     ✓    |
| **2560px**    |       ✓   |     ✓       |     ✓    |     ✓    |

### Validation
all .html pages pass [official W3C Validator](https://validator.w3.org/#validate_by_input) Lighthouse and Wave test<br>
Insert Pictures<br>
<br>
styles.css passes the [oficial W3C CSS validator (Jigsaw)](https://jigsaw.w3.org/css-validator/)<br>
Insert pictures<br>

### Bugs & Enhancements:
// Expand on this
Bug1: The Title box displays over the nav-toggle window<br>
Fix: deployed a Z Axis and moved nav toggle window to be inline with convention<br>
<br>
Bug2: The title-picture is displaying above the title-box<br>
Fix: Used flex box and absolute positioning<br>
<br>
Bug3: title-picture seems to be cut off, not a perfect circle<br>
Fix: Unable to reproduce as of 20/02/2024<br>
<br>
Bug4: title-picture was being overlapped by conact bar on large screens<br>
Fix: moved title picture to left and into title more to appear more like a profile<br>
<br>
Bug5: Sensitive information in contact menu<br>
Fix: Replaced with Placeholder text<br>
<br>
Bug6: Website not responsive for 4k resolution<br>
Fix: added divs to either side to keep site compact on 4k screens, limited the centre div to 1440px max, the left and right divs are using Flex Grow<br>
<br>
Bug7: Hover colour not contrasting enough<br>
Fix: changed colour to stronger contrast<br>
<br>
Bug8: Hover colour appearing<br>
Fix: Changed order in style.css, made color inherit<br>
<br>
Bug9: CV link broken<br>
Fix: changed name of file to fit convention, replaced path with valid directory<br>


Enhancement1: Make the download button the complete anchor<br>
Status: Done<br>
<br>
Enhancement2: Image position on each content could be better<br>
Status: Disagree, happy with current image placements<br>

## Acknowledgments
* [Google Fonts](https://fonts.google.com)<br>
* [Font Awesome](https://fontawesome.com) For the comprehensive collection of icons used throughout the website.<br>
* [GitHub Pages](https://pages.github.com/) For hosting the website for free.<br>
* [Pexels](https://www.pexels.com/) photos uploaded by users to the free imaging hosting website pexels:<br>
  * Kevin Ku <br>
  * Brett Sayles <br>
  * Anete Lusina<br>
  * Pixabay<br>
  * Mikhail Nilov<br>
* [Colormind](http://colormind.io) Helping create a colour sceme based off my hero image<br>
* [Coloring for Colorblindness](https://davidmathlogic.com/) helping me choose a color scheme for each content page that's fully accessable<br>
* [Favicon IO](https://favicon.io/emoji-favicons/nerd-face) software to make a freeuse favicon<br>
* [Kim Britnell] (https://www.linkedin.com/in/kimbritnell/) for proof reading and suggesting edits to the text content<br>
* Kera Cudmore's [guide](https://github.com/kera-cudmore/readme-examples) on making a good README. 
