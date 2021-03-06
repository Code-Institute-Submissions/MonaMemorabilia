# ![Monachese Photography](assets/images/logo-readme.png "Monachese Photography")  onachese Photography

The purpose of this site is to showcase an independent photographer's gallery, demonstrate their ability to digitally enhance photos, and to advertise photo 
sessions and editing packages to meet the photography needs of potential clients. A majority of the images showcased cater to parents and grandparents, however 
these may also appeal to a smaller market of young adults seeking business portraits and clients who wish to digitally enhance photographs.

# Live Prototype Demo and Wireframe
+ An active prototype can be found [here](https://richardaeld.github.io/MonaMemorabilia/ "Webpage") at GitHub.
+ The wireframe images used to help design this webpage can be found [here](https://github.com/Richardaeld/MonaMemorabilia/tree/master/assets/wireframe "Wireframe").

# UX Choices
![display-responsiveness](assets/images/display-devices.png "display-responsiveness") 

### Home
+ Shows off four eye-catching photos, in a bootstrap carousel, for potential clients to get an impression of the photographer’s style.
+ Gives a brief description of the general services offered through a responsive layout that makes use of negative space to increase readability for clients.

### Main Nav Bar
+ Includes a clean, responsive bootstrap nav bar where clients can clearly view the navigation bar on all devices.
+ Provides a clear display of the company logo in the top left corner.

### All Footers
+ Uses Font Awesome icons paired with text to display a contemporary social link design which will appeal to potential clients of all ages.
+ Added social links that an independent photographer would use so that potential clients can view their work across multiple popular social platforms.

### About Us
+ Features a Hero image which demonstrates the photographer’s ability to digitally enhance photos. This shows potential clients the photographer's skill and artistic style.
+ Features a no-frills text section which emphasizes the exceptional work offered by the photographer and will assure potential clients that they will receive 
    the best treatment.
 
### Gallery
+ In order to make the four sub-gallery links stand out, the page utilizes negative space and a gray background color which emphasizes and draws the eyes toward the image links.
+ Images on the page include a hover and scale feature to make it clear to clients which gallery they are selecting.

### Sub-Galleries (All Pages That Are Linked From Within Gallery)
+ To provide a more convenient navigation experience, clients can click on a picture which will jump to the desired photo. Below each photo, another link allows the clients to jump back up to the top of the page.
+ To navigate easily between galleries, a back button to the main gallery was included in each sub-gallery.
+ To make each image stand out to potential clients, all images have an added border and box shadow to give a three-dimensional effect that provides contrast with the page background color.

### Contact Us
+ Contains a simple submission form which prevents clients from accidentally submitting the form without completing the contact information.
+ The final box (Describe Your Session needs...) includes plenty of space for clients to submit a substantial, well-thought out response.

### Image Compression
+ After using [TinyPNG](https://tinypng.com/) image compression, roughly 51% of the kb load from images was eliminated.
+ According to [Pingdom](https://tools.pingdom.com/) the reduction in image size allowed the pages to load in approximately 0.250 seconds.

![Tinyify differrence image](assets/images/tiny-ping-combo.png "Displays the minification done to image")

# Brand Identity
+ The header tags, h1, h2, and h3 match the font family style of the logo.
+ The main page color scheme uses the monochromatic coloration of the logo.
+ The pictures used maintain themes of family and digital enhancement, which demonstrate the photographer’s artistic style.

# Client Stories And Experience Provided 
## Client Stories 
+ As a client, I'd like a framable photograph for a gift.
+ As a client, I'd like a portrait photograph for a work portfolio.
+ As a client, I'd like a photograph that I already own to be digitally improved. 
+ As a client, I'd like a photographer to attend a family event to capture candid photos.
+ As a client, I'd like a photo session for a non-conventional project. 
+ As a client, I'd like a studio photo session with my family.

## Experience Provided
+ The Hero carousel on the index page provides a guide to the artistic style, skill, and the overall quality of the photography provided by this company.
+ The sub-galleries provide a wide-range of styles and professional ideas for clients to discover the perfect photograph session to request.
+ The sub-gallery digital enhancement section shows the multiple color enhancements and digital effects that can be added to a picture.
+ The paragraphs found on the index page describe the different types of sessions offered and the standard amount of session time to book. 
+ The about us section emphasizes the personalized services offered and the willingness to accept custom projects.
+ The contact us section has a form where the client can enter the specifics of any project with ample space.

# Testing
## Checking Responsiveness 
#### Expectation(s):
1. All Pages, regardless of resolution, should have good UX, no visual bugs, or misalignments.

#### Assumption(s):
1. Using the latest version of Chrome. 
1. Using a monitor that supports 1080p resolution or greater.

#### Testing Steps:
1. Open the index page of the website to test in Chrome.
1. Open **Inspect mode** in Chrome browser.
1. Click the **Responsive tab** (that is located underneath the browser address bar) and select an untested device type.
1. Check for visual bugs, misalignments, or bad UX.
1. Document any problem area(s) or abnormal occurrence(s).
1. Select **Rotate** (which is located to the right of the Responsive tab).
1. Check for visual bugs, misalignments, or bad UX.
1. Document any problem area(s) or abnormal occurrence(s).
1. Repeat steps three through eight until all media sizes available have been tested.
1. Select **Responsive tab** and select the **Responsive** function.
1. Stretch screen width from 320px to 1920px and beyond (this may require the use of inspect's **zoom** feature).
1. Check for visual bugs, misalignments, or bad UX as the pixel width changes.
1. Document any problem area(s) or abnormal occurrence(s).

#### Documented Result(s):
1. Documentation of all bad UX and where it occurs.
1. Documentation of where visual bugs or misalignments occur.

#### Final Result(s)
1. Starting at the resolution of an i5, and going beyond 1080p this webpage automatically adjusts and provides the best UX possible on all devices.
--------------------------------
## Checking For Errors In Code
#### Expectation(s):
1. Code should not return errors.

#### Precondition(s): 
1. Website has been deployed.

#### Assumption(s):
1. Know that vendor extensions will not validate and can be ignored.
1. Know that not all warnings given will show code that requires change. 
1. Know that external resources, like Bootstrap, will return errors and warnings that do not concern this process.

#### Testing Steps:
1. Open the website that needs an html and css code check, copy its index link, and leave the tab open.
1. Open another tab in the browser and go to [W3C Markup Validation Service](https://validator.w3.org/).
1. Paste the link of a page requiring an html code check into W3C's **validation bar** and submit it to see what W3C finds.
1. Document errors and warnings that need to be corrected.
1. Repeat steps three and four until all pages have been checked in W3C.
1. Open a new browser tab and go to  [Jigsaw (CSS Validation Service)](https://jigsaw.w3.org/css-validator/).
1. Paste the index page link of the website requiring a css code check into Jigsaws's **validation bar** and submit it to see what Jigsaw finds.
1. Document errors and warnings that need to be corrected.

#### Documented Result(s):
1. List of problem code and where in the page(s) it can be found.

#### Final Result(s)
1. All problematic code has been removed from the webpage.
1. One minor error still occurs on the contact us page which is detailed in previous and current bugs section.
---------------------------------
## Checking For Browser Support
#### Expectation(s):
1. Should not return a time out, have an error, or grapical misalignment when viewed.

#### Precondition(s): 
1. Know what the index page looks like at different resolutions.

#### Assumption(s):
1. Know that the free version of BrowserStack has a limit on selection options.

#### Testing Steps:
1. Open the index page of the website that needs to have a support check, copy its index link, and leave the tab open.
1. Open another tab in browser and go to [BrowserStack Screenshots](https://www.browserstack.com/screenshots).
1. Paste the link of the index page into BrowserStack Screenshots **testing bar**.
1. Pick a device or operating system and select the most current version of browsers supported by the selected operating system.
1. Repeat step four until there are 25 browser and/or device combinations.
1. Click **Generate** and wait for the results to finish.
1. View each screenshot to check for image accuracy.
1. Document the successful browser and/or device combinations.
1. Click **Back to Devices** and clear all previous selections.
1. Repeat steps four through nine until all operating systems (with browser combinations) and devices are documented.

#### Documented Result(s):
1. List of operating system and browser combinations with support.
1. List of devices with support.

#### Actual Raw Result(s):
1. BrowserStack results for this site can be found [here](https://github.com/Richardaeld/MonaMemorabilia/tree/master/assets/browserstack "BrowserStack Results").
----------------------------------
## Checking For Webpage Load Times
#### Expectation(s):
1. Should return an accurate load time for each page.

#### Precondition(s): 
1. Website has been deployed.

#### Testing Steps:
1. Open the index page of the website that requires a latency ping, copy its index link, and leave the tab open.
1. Open another tab in the browser and go to [Pingdom](https://tools.pingdom.com/).
1. Paste the link of the index page into Pingdom's **URL bar**.
1. Select the location, North America-USA-San Francisco from the **Test from** drop down menu.
1. Click **Start Test** and wait for the results.
1. Record Results.
1. Repeat steps three through six until all pages have been tested.

#### Documented Result(s):
1. List of load times for site.

#### Actual Raw Result(s)
1. Pingdom results for this site can be found [here](https://github.com/Richardaeld/MonaMemorabilia/tree/master/assets/pingdom "Pingdom Results").
--------------------------------
## Previous And Current Bugs
+ During the programming of this webpage, there were numerous graphical misalignments. These were primarily generated by Bootstrap creating 
    padding and margins and was the result of using rows and container-fluid commands. These were easily taken care of with appropriate padding removal, 
    margin removal, and the use of the !important command.
+ During the writing of the index page, a coding error created an unintentional extra level of responsiveness at 1200px wide. However, this error resulted in
    a better UX and was left as is.
+ Various pages were not filling the entire screen on specific interface devices when using the inspect function in Chrome. By matching the 
    body’s default background color to the footer’s background color, it gives the illusion that the footer's background color extends 
    to the bottom of the screen.
+ The file "Core.python3.2641.1592707923" will crash GitPod when attempting to delete it.
+ When viewing all sub-galleries at an i5 resolution in landscape (568px x 320px) while using the Chrome inspect function, the top and bottom 
    borders of photos cannot be seen due to the size of the nav bar and the physical limitations of the pixels on the screen.
+ An error found by W3C Validator could not be corrected because of the use of an extra label tag that named the group of radio buttons in contact us.

## Operating System And Browser Combinations With Confirmed Support (According To BrowserStack)
#### All Browsers Must Be The Current Version
+ Windows 10
    + Chrome, Internet Explorer, Firefox
+ Windows 8.1, 8.0, 7 
    + Chrome and Internet Explorer
+ Mac OS X Catalina and Mojave
    + Chrome
+ Mac OS X High Sierra, Sierra, and El Capitan
    + Safari and Chrome
+ Mac OX X Yosemite and Mavericks
    + Chrome

## Scalability
+ Adding a user operable slide-bar to change images from the original to an edited version could offer better representation for the digital 
    enhancement section and in the About Us section. However, this feature is outside the scope of the project.
+ The use of a modal in the sub-gallery pages would allow for pictures to pop-up instead of relying on a clunky jump to anchor link.
+ Changing pixels to rem in CSS would help reduce code length in the CSS and add better responsiveness to all pages on smaller devices.
+ Change the input for telephone number, in contact us, to a more visually appealing and better functioning input involving JavaScript.


# Tool, References, And Code Used
## Tools
+ [Balsmiq](https://balsamiq.com/) - Helped produce the wireframe used for this webpage
+ [Bootstrap](https://getbootstrap.com/) - Used as framework
+ [BrowserStack](https://www.browserstack.com/screenshots) - Helped with checking for platform compatibility
+ [Font Awesome](https://fontawesome.com/v4.7.0/icons/) - Used icons from here
+ [GitHub](https://github.com/) - Deployment of prototype website
+ [GitPod](https://www.gitpod.io/) - Integrated development environment
+ [Google Fonts](https://fonts.google.com/) - Used font families from here
+ [Jigsaw (Validation Service)](https://jigsaw.w3.org/css-validator/) - Used to identify errors in CSS
+ [Pingdom](https://tools.pingdom.com/) - Checked for page load time
+ [Techsini](https://techsini.com/multi-mockup/) - Used for their viewable responsiveness PNG
+ [TinyPNG](https://tinypng.com/) - Minimizing KB load per image
+ [W3C Validator](https://validator.w3.org/) - Used to identify errors in markup

## References And Code Used
+ [Web Accessibility Checklist](http://webaccessibilitychecklist.com/) - Helped with making webpage ARIA accessible
+ [MDN web docs](https://developer.mozilla.org/en-US/docs/Learn/Accessibility/What_is_accessibility) - Helped with understanding of when and how to use ARIA
+ [Stack Overflow](https://stackoverflow.com/) - Helped in understanding how to correct visual bugs with Bootstrap's automatic padding/margins and general questions
+ [TestLodge](https://blog.testlodge.com/how-to-write-test-cases-for-software-with-sample/) - Used for test case examples
+ [W3Schools](https://www.w3schools.com/) - Helped with fine-tuning CSS and provided examples of advanced tricks involving transition, hover, and scale:
    + Index - Hover button effects are found under "Custom Project" and text shadow is used on the busisness name, Monachese Photography
    + All footers - Hover effect used for the social media icons
    + Gallery and Sub-Galleries - All nav images use the scale effect and a box shadow
    + Sub-Galleries - The clickable images use a scale and transition effect. All the images use box shadow<br/><br/>
+ [Bootstrap](https://getbootstrap.com/) - Framework used to help speed up development and add a better UX:
    + Main nav bar- used responsive design nav bar
    + Index - image carousel
    + Contact Us - multiple pieces of form used for user inputs, radio buttons, and text area
    + Sub-Gallery - scrollspy was used for the jump to anchor links (may be unrecognizable in current form because of reductions to and personalizing of code) and the invisible property was used to hide the placement of these links<br/><br/>
+ [Code Institute (Class)](https://codeinstitute.net/) - Provided two major ideas for the website during the "Rosie" project:
    + All footers - golden ratio for the structure of all the footers
    + All footers - the style of the social links and how they use a color transition<br/><br/>
+ [Simon "jumboduck"](https://jumboduck.github.io/Polygonal-Brewing-Co/brewery.html "Page visual reference was used from") - Used as visual reference for:
    + About Us - a large Hero image followed by the golden ratio of three text boxes that share the background color of the page

# Technologies
## Languages
+ HTML
+ CSS
+ JS (with Bootstrap)
+ JQuery (with Bootstrap)

# Acknowledgements
+ The idea for this website came from Michael Monachese because of his forte for photography.
+ The photos and logo were created by Michael Monachese.
+ Felipe Souza Alarcon for guidance and providing a plethora of information and web-based applications.
+ Emily Grooms for help in revising this README document.
