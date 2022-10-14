![Life Hax Logo](assets/images/logo_transparent_cropped.webp "Life Hax Logo")


# Life Hax Website

This website is for an online life hacks company called, Life Hax. Life Hax are currently offering free sign up to new members. Membership gives you access to their mailing list and mobile app. All users will receive access to content designed to save them time and money. This site is mainly targeted at male and female users between the ages of 18 to 60 years old. Once the website has built up a user base, they will add advertisments to generate site revenue. Existing members will remain ad free however new members who do not wish to see ads will need to sign up for a paid membership. The site will aim to provide tailored content for users based on their interests as the site grows. 

## Features
----

### Navigation

- The nav bar is located at the top of the screen and shows the site logo on the left hand side and the nav menu on the right hand side. 

<img style="display: inline; margin: 25px 20%;" src="readme-files/nav-wide.png" alt="Nav Bar Wide Design" width="60%" height="auto" title="Nav Bar Wide Design">

- The nav menu includes 4 links which navigate to different sections of the main page. The links in the nav bar on the home page send the user directly to the section id to avoid reloading the page. The links on the confirmation page send you back to the main page. 

- The nav bar menu has responive styling to work on devices with screen widths as low as 280px. Media queires have been added so that the menu appears aesthetically pleasing on a variety of different screen sizes. On larger screens, it shows all 4 items on 1 row. On smaller devices, such as mobile phones, the menu is displayed in 2 rows with 2 links on each row. 

<img style="display: inline; margin: 25px 37.5%;" src="readme-files/nav-small.png" alt="Nav Bar Narrow Design" width="25%" height="auto" title="Nav Bar Narrow Design">

- The home page has a link button at the bottom of the screen to send you back to the top of the page, this feature was not required on the confirmation page. 

<img style="display: inline; margin: 25px 46%;" src="readme-files/top-button.png" alt="Top of Page Button" width="8%" height="auto" title="Top of Page Button">

- The nav bar has a decorative border around the items when the user hovers over it. The styling is in line with the rest of the website. 


### Hero Image Section

- The Hero Cover Image is displayed at the top of the page. An image with a transparent background was chosen and a visual annimation effect was also added.

- Cover text is displayed in front of the image. The cover text includes a the company slogan "Life Changing, Life Hax". The first line is a heading and then the company name "Life Hax" is displayed below it. There is a button that links the user to go straight to the sign up section to encourage them to join straight away with as little time spent scrolling to the section as possible.  

- The CSS Validation logo has been included in this section with an active link for anyone who is interested in verifying the site's code. The opacity has been reduced as this is not inteded to be the focal point of the section, more of an easter egg for those interested. 

<img style="display: inline; margin: 25px 20%;" src="readme-files/hero-responsive.png" alt="Hero Image Responsive Design" width="60%" height="auto" title="Hero Image Responsive Design">

### Life Hack Examples Section

- The Life Hack Examples section includes 3 divs to highlight life hacks, three topics where chosen with examples listed below each heading. 

- A picture is included in each div. It is styled to be displayed in a circular border. 

- The sections is divided into 3 divs which are displayed on a single row on larger screen widths and 1 div per row on smaller screen widths. 

- The div is styled with a decorative border, background color etc that is in line with the styling of the site. 

<img style="display: inline; margin: 25px 20%;" src="readme-files/examples-responsive.png" alt="Life Hack Examples Section Responsive Design" width="60%" height="auto" title="Life Hack Examples Section Responsive Design">

### Why Join Section

- The why join section is divided into 4 divs and includes content on why the user should join. It also includes another semi-subtle link to send the user to the sign up section. The site objective is to sign up as many users as possible.

- All 4 divs are displayed in one row on large screens, 2 divs per row on medium screens and 1 div per row on small screens.

- The div is styled with a decorative border, background color etc that is in line with the styling of the site. 

<img style="display: inline; margin: 25px 20%;" src="readme-files/why-responsive.png" alt="Why Sign Up Section Responsive Design" width="60%" height="auto" title="Why Sign Up Section Responsive Design">

### Membership Section

- The what do you get / membership section includes 2 headings and 2 videos. The sections are displayed on one row on larger devices and 1 section per row on smaller devices.

- The div is styled with a decorative border, background color etc that is in line with the styling of the site. 

<img style="display: inline; margin: 25px 20%;" src="readme-files/videos-responsive.png" alt="Videos Responsive Design" width="60%" height="auto" title="Videos Responsive Design">

### Sign Up Section

- The sign up section includes a form with text input areas for first name, last name, email address and password with each type set correctly. There is a question with 7 radio options, first 6 are indivual options while the last option is for all so is displayed on the row below regardless of the device's screen width. The last part of the form is the sumbit button which is styled to entice the user to click the big red button when hovered over. The form will not allow the user to submit their data unless the required information has been provided. 

- The form is styled to be inline with site however all 4 corners are rounded which is intentionally different than the above sections. 

- The text input area is styled to adjust in size on smaller devices.

<img style="display: inline; margin: 25px 20%;" src="readme-files/signup-responsive.png" alt="Sign Up Form Responsive Design" width="60%" height="auto" title="Sign Up Form Responsive Design">

### Confirmation Page

- When the form is submitted correctly, it will take the user to the sign up confirmation page. This page is not accessible via the nav links. This page is included so that the user knows that their data has been submitted correctly. 

- The confirmation page is styled similarly to the main page so the experience is pleasant for the site users. 

- The confimrmation page includes a nav bar, footer, buttons and background image that are all similar to the main home page. 

<img style="display: inline; margin: 25px 20%;" src="readme-files/confirmation-responsive.png" alt="Confirmation Page Responsive Design" width="60%" height="auto" title="Confirmation Page Responsive Design">

### Social & App Section

- The footer contains 2 divs which provide links for social media and app stores. The divs are displayed in 1 row on larger devices and 1 div per row on smaller devices. 

- The colours are inversed from the above sections, this is visually appealing and provides a clear distinction between the footer and above sections. 

<img style="display: inline; margin: 25px 20%;" src="readme-files/footer-responsive.png" alt="Footer Responsive Design" width="60%" height="auto" title="Footer Responsive Design">

## Testing
----


### Initial Testing

- The intial tests were carried out by utilising the inspect feature on the Google Chrome web browser on my laptop. I also checked how the website responded on my mobile phone. I ran initial (W3C) validation tests for both the HTML and CSS alongside Lighthouse Reports on Chrome. I addressed and resolved any of the issues that arose. 


### Bugs & Solved Issues

- My image and videos were not working when the site was deployed at first as I had used a "/" in front of the file locations. 

- Initially, I uploaded high quality photos and videos. To improve page preformance, I reduced the file sizes accordingly so that they are an optimal size and format for the site. I also experimented by adding the videos to the site by embedding a youtube video using iframes. 

<img style="display: inline; margin: 25px 20%;" src="readme-files/size-warning.png" alt="Video Size Warning" width="60%" height="auto" title="Video Size Warning">

- Initially, I had 6 nav bar links and designed for the nav bar menu items to be stacked verticaly on smaller devices. This meant the clickable area on mobile devices would have been on the small side and potentially be considered as a bug or design flaw. To improve on this, I removed the link to the Social & app links in the footer and moved the "Top of Page" link into a button that is displayed at the bottom right hand side of the site insted. I then restyled the repsonive design for the menu nav bar so that it goes from 4 items in 1 row to 2 items spread over 2 rows for smaller devices. 

- At first, I created a circular div with a link inside of it that was displayed in the hero image voer text. I would have consider this as a bug as it gave the impression that by clicking anywhere inside the circle you would activate the link but the user actually would have had to click on the text to follow the url. To rectify this issue, I implemented a button enclosed in a form that sends the user to the desired location. I then implemented this button type on the confirmation page as well. 

- I was provided with a CSS validator link once the website passed the checks. Initially, this link would not work, I resolved this by using the alternative link they provided. I also removed the trailing slash and hosted the image on github instead of linking to an external resource. I also added a no opener, alt, styling etc. 


#### W3C HTML Validator

- No issues found in final tests on both the main and confirmation pages.

<a href="https://validator.w3.org/nu/?doc=https%3A%2F%2Fkc-7.github.io%2Flife-hacks-v2%2Findex.html" target="_blank" rel="noopener" aria-label="Link to the HTML Validator for Home Page (opens in new tab)">Home Page HTML</a> Validation:

<img style="display: inline; margin: 25px 30%;" src="readme-files/html-index.png" alt="HTML Validator for Home Page" width="40%" height="auto" title="HTML Validator for Home Page">

<a href="https://validator.w3.org/nu/?doc=https%3A%2F%2Fkc-7.github.io%2Flife-hacks-v2%2Fconfirmation.html" target="_blank" rel="noopener" aria-label="Link to the HTML Validator for Confirmation Page (opens in new tab)">Confirmation Page HTML</a> Validation:

<img style="display: inline; margin: 25px 30%;" src="readme-files/html-confirmation.png" alt="HTML Validator for Confirmation Page" width="40%" height="auto" title="HTML Validator for Confirmation Page">

#### W3C CSS Validator

- No issues found in final tests on both the main and confirmation pages. CSS Validator logos with links have been added to both pages. 

Home Page:

<a href="http://jigsaw.w3.org/css-validator/validator?lang=en&profile=css3svg&uri=https%3A%2F%2Fkc-7.github.io%2Flife-hacks-v2%2Findex.html&usermedium=all&vextwarning=&warning=1" target="_blank" rel="noopener" aria-label="Link to CSS Validator for Home Page (opens in new tab)"> <img src="assets/images/vcss-blue.webp" alt="Home Page | Valid CSS!"></a>

Confirmation Page: 

<a href="http://jigsaw.w3.org/css-validator/validator?lang=en&profile=css3svg&uri=https%3A%2F%2Fkc-7.github.io%2Flife-hacks-v2%2Fconfirmation.html&usermedium=all&vextwarning=&warning=1" target="_blank" rel="noopener" aria-label="Link to CSS Validator for Home Page (opens in new tab)"> <img src="assets/images/vcss-blue.webp" alt="Confirmation Page | Valid CSS!"></a>


#### Lightouse - Performance, Accessibility, Best Practices & SEO

<img style="display: inline; margin: 25px 20%;" src="readme-files/lighthouse-score.png" alt="Lighthouse Score" width="60%" height="auto" title="Lighthouse Score">

- Performance: 98%
- Accessibility: 100%
- Best Practices: 100%
- SEO: 100%

Same results for both the main and confirmation page. The preformance score can vary, above results achieved while using chrome in incognito mode to disable browser extensions. Time was spent on improving all scores by actioning the highlighted oppurtunities. 

<img style="display: inline; margin: 25px 20%;" src="readme-files/lighthouse-index.png" alt="Lighthouse Score for Index Page" width="60%" height="auto" title="Lighthouse Score for Index Page">

<img style="display: inline; margin: 25px 20%;" src="readme-files/lighthouse-confirmation.png" alt="Lighthouse Score for Confirmation Page" width="60%" height="auto" title="Lighthouse Score for Confirmation Page">


#### Visual Testing

- Visual testing was carried using <a href="https://ui.dev/amiresponsive" target="_blank" rel="noopener" aria-label="Link to my W3Schools guide to add Top Button (opens in new tab)">Am I Responsive</a> and the Google Chrome Inspect function. 


### Unresolved Bugs & Future Improvements 

#### Unresolved Bugs

- All bugs that I am aware of have been addressed and resolved. 

#### Future Improvements 

- Add <a href="https://www.w3schools.com/howto/howto_js_scroll_to_top.asp" target="_blank" rel="noopener" aria-label="Link to my W3Schools guide to add Top Button (opens in new tab)">javascript</a> to remove the "Top of Page" link button when the user is already at the top of the page. 

- Implement a <a href="https://www.w3schools.com/howto/howto_js_topnav_responsive.asp" target="_blank" rel="noopener" aria-label="Link to my W3Schools guide to responsive nave menu (opens in new tab)">responsive nav menu</a> with a "hamburger" styled menue for use on smaller devices, especially useful if additional sections are added to the site in future. 

- Review and improve on grouping styling elements where reasonably practical. 


## Deployment
----

### GitHub

- The site was deployed to my <a href="https://github.com/KC-7/life-hacks-v2" target="_blank" rel="noopener" aria-label="Link to my GitHub Repo (opens in new tab)">GitHub</a>.

- My username on <a href="https://github.com/KC-7/" target="_blank" rel="noopener" aria-label="Link to my GitHub account (opens in new tab)">GitHub is KC-7</a>.


## Credits
----

### Content

- This site was developed using information learned from the <a href="https://codeinstitute.net/" target="_blank" rel="noopener" aria-label="Link to the Code Institute (opens in new tab)">Code Institute</a> alongisde other online resources such as <a href="https://www.w3schools.com/html/html_favicon.asp" target="_blank" rel="noopener" aria-label="Link to W3Schools (opens in new tab)">W3Schools</a>. 

- The code used to annimate the hero page was learned from the <a href="https://codeinstitute.net/" target="_blank" rel="noopener" aria-label="Link to the Code Institute (opens in new tab)">Code Institute's</a> Love Running Project although the values are different to suit the Life Hax website. 

- I learned how to implement the Favicon, the picture in the browser tab, from using <a href="https://www.w3schools.com/html/html_favicon.asp" target="_blank" rel="noopener" aria-label="Link to W3Schools (opens in new tab)">W3Schools</a>.

- The social links, app download sections and the css validator logo all contain links to third party websites. 

- Font added using <a href="https://fonts.google.com/" target="_blank" rel="noopener" aria-label="Link to Google Fonts (opens in new tab)">Google Fonts</a>.

- Icons added using <a href="https://fonts.google.com/" target="_blank" rel="noopener" aria-label="Link to Font Awesome | Free V5 Icons (opens in new tab)">Font Awesome | Free V5 Icons</a>.

### Media

- Both of the videos on the homepage were sourced from <a href="https://www.rawpixel.com/public-domain" target="_blank" rel="noopener" aria-label="Link to Pexel's Home Page (opens in new tab)">Pexel</a> and are both are available for use in the Public Domain. Both video give credit to the content uploader in the index.html file. 

- All of the images were sourced from <a href="https://www.rawpixel.com/public-domain" target="_blank" rel="noopener" aria-label="Link to RawPixel's Public Domain Content (opens in new tab)">RawPixel</a> and are available for use in the Public Domain.

- The custom site logo was created using <a href="https://www.shopify.com/tools/logo-maker" target="_blank" rel="noopener" aria-label="Link to Shopify's Logo Maker (opens in new tab)">Shopify's Free Logo Maker</a>.

- The CSS image was provided by the W3 Jigsaw Validator once all checks were passed. 

