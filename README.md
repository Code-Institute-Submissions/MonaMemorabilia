![Monachese Photography](assets/images/logo.png "Monachese Photography")

# Monachese Photography

This site allows a photographer's company to show off their brand of photograph, ability to digitally improve photos, and provide customers with a desireable end product. 
The implied clientele is parents and grandparents, however this site also applies to a smaller market of young adults seeking business portraits and those seeking to digitally 
improve previously taken photo's.

# UX Choices

### Home

+ Shows off four eye drawing images in bootstrap carousel
+ Gives a brief description of general services offered in four boxes that make use of negative space

### Main Nav 

+ Clean, responsive bootstrap nav bar 
+ Clear display of company logo in top left corner

### Main Footer

+ Images used with minimal text to show user that text is a clickable link
+ Added social links that would most likely be used by a photo image company

### About Us

+ Hero image showing the difference with and without color grading
+ A text section emphasizing the above and beyond work offered by the company 

### Gallery

+ Use of negative space to draw the eye to four sub-gallery links
+ Scale feature when hovering over images to help confer it's a link

### Sub Gallery (all pages)

+ Back button to main gallery and a two way in page nav for user convience
+ All images have an added border and shadow to give a 3 dimensional effect to help draw the eye

### Contact us

+ Simple submission form that prevents users from accidently submitting without filling in contact information
+ Fitted with plenty of space for users to submit a well thought out idea, multiple questions or both

### Brand Identity

+ Header font-familys match the Style of the logo font-family
+ Main page uses logo's monochromatic coloration
+ Strong theme's of family and artistic photography 

# Potiental Client Examples

+ A: Is looking for a "candid" photo
    + Sees the home page carousel and describes a business portrait in the "Describe your session needs" on Contact Us page

+ B: Wants a frameable photo of child to give to grandparents  
    + Finds an artistic color graded photo in Children Gallery page 

+ C: Has an idea for a photo session that is non standard
    + Home page has a section about custom projects w/ button to submit custom ideas

+ D: Is looking for previously taken photos to be digitally edited
    + Sees the half edited photo on About us page and decides that submitting a custom reediting project in that style is what they desire

# Live Protype Demo and Wire Frame

+ An active demo can be found [here](https://richardaeld.github.io/MonaMemorabilia/ "Web Page") at github. 
+ The wire frame png's can be found [here](https://github.com/Richardaeld/MonaMemorabilia/tree/master/assets/wireframe "Wire Frame") also embedded at github.

# Testing
## Web Programs used
+ pingdom results can be found [here](https://github.com/Richardaeld/MonaMemorabilia/tree/master/assets/pingdom)
+ browserstack results can be found [here](https://github.com/Richardaeld/MonaMemorabilia/tree/master/assets/browserstack)
+ W3C Validator was used to help identify errors in HTML and CSS


## Previous and Current Bugs
+ Numerous graphical misalignments were experienced during the construction of this project.  These were primarily generated by bootstrap creating padding and margins with 
    the use of rows and container-fluid commands. Thus they were easily taken care of with appropiate padding/margin removal and use of "!important".  

+ Various pages were not filling the entire page on specific interface devices (using inspect in chrome). The fix used was giving the body a fall back color of the footer. Thus it 
    appears the footer just keeps extending to fill the page. 

+ The file "Core.python3.2641.1592707923" will crash gitpod when attempting to delete it.

+ When sub gallerys viewed at i5 resolution on landscape the nav bar and bottom cut off borders of images.

## Not supported 
+ internet explorer 9 and older
+ opera 12.15 and older
+ firefox 3.6 and older
+ safari 8.0 and older

### transition effect supported (video ref header adding a profile video 1 time before 6min)
+ Chrome 26.0 and newer
+ Internet explorer 10 and newer
+ Firefox 16 and newer
+ Safari 6.1 and newer
+ Opera 12.1 and newer

# Scalability 
+ Photo slider to change photo from before digital editing to after (Would be neat but outside of scope of project)
+ Use of a modal in sub-gallery pages to pop up a picture rather than relying on a clunky in page nav 
+ Changing of px to rem would help with code length and add better responsiveness to page on smaller devices 

# Technologies

## Languages 
+ HTML
+ CSS
+ JS (With Bootstrap)
+ JQuery (With Bootstrap)

## Framework (Bootstrap not wire frame - balsmiq)
+ [Bootstrap](https://getbootstrap.com/) - The framework used to help structure this web page
+ [Balsmiq](https://balsamiq.com/) - Helped produce the wireframe used for this web page

## Web based tools

+ GitHub - Deployment of prototype site
+ GitPod - Integrated development environment 
+ Pingdom - Checking for page load time
+ BrowserStack - Checking for platform incompatibility
+ tiny.png - Minimizing KB load per image
+ fontawesome - Icons used
+ google fonts - Fonts used 
+ bootstrap - Used as framework
+ W3C Validator - Used to identify errors in code

## Web based references and code used from

+ [webaccessibilitychecklist](http://webaccessibilitychecklist.com/) - Helpped make page Aria accessible
+ [MDN web docs](https://developer.mozilla.org/en-US/docs/Learn/Accessibility/What_is_accessibility) -  helped with understanding when to use aria
+ [w3schools](https://www.w3schools.com/) - helped fine tune css, and provided examples of advanced tricks involving transition, hover, and scale.  These can be seen in
    1. Index (:hover button effects found uder custom project and text-shadow used on busisness name) 
    2. Main footer(the buttons found under: Follow Us On)
    3. Gallery and sub-galleries (the scaling effect used on images along with box shadow)
    4. Sub-galleries (the selectable images scale and transition properities)

+ [stack overflow](https://stackoverflow.com/) - helped understand how to correct visual bugs with bootstrap's automatic padding and margins
+ [bootstrap](https://getbootstrap.com/) - 
    1. Main nav (Used responsive design nav bar) 
    2. Index (Image carousel) 
    3. Contact us (Form was put together using almost entirly bootstap code) 
    4. Sub-Gallery(scrollspy was used for in page nav, "invisible" properity was used to hide placement of in page nav snap to points)

+ Code Institute (Class) - used footer design based on golden ratio and made social links like those shown in class

+ Used a visual reference from a classmate (Simon "jumboduck") for About us section. The idea used is a large hero image followed by the golden ratio of 3 text boxes that share 
    the background color of the page.

# Acknowledgements 

+ The photos and logo were created by the same person, "Micheal Monachese" 
+ The idea for this website came from a childhood friend that has a forte for photography
+ Felipe Souza Alarcon for guidence and providing a plethoria of information and useful web based applications






