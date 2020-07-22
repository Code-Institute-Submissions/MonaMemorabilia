![Monachese Photography](assets/images/logo-readme.png "Monachese Photography")

# Monachese Photography
The purpose of this site is to showcase an independent photographer's gallery, demonstrate their ability to digitally enhance photos, to advertise photo session/editing packages,
and services to meet client photography needs. A majority of images showcased cater to the needs of parents and grandparents, however this sit also has appeal to a smaller market 
of young adults seeking business portraits and clients who wish to digitally enhance photographs.


# UX Choices
### Home
+ Shows off four eye catching photos in bootstrap carousel
+ Gives a brief description of general services offered in four boxes that make use of negative space

### Main Nav 
+ Includes a clean, responsive bootstrap nav bar 
+ Provides a clear display of the company logo in top left corner

### Main Footer
+ Uses Fontawesome icons paired with text to display a contemporary link design 
+ Added social links that would most likely be used by an independent photographer

### About Us
+ The Hero image used is a half edited and half unedited photo that shows the difference of an idependent photographers brand of digital enhancement
+ Features a no-frills text section emphasizing the above and beyond work offered by the company 

### Gallery
+ Utilizes negative space to draw the eye to four sub-gallery image links
+ Images on the page include a "hover" and "scale" feature to provide the appearence of conventional links

### Sub-Galleries (all pages that are linked from within gallery)
+ Includes a back button to main gallery and a two way in page nav for user convience
+ All images have an added "border" and "box-shadow" to give a three-dimensional effect

### Contact us
+ Contains a simple submission form that prevents users from accidental submittion without completing contact information
+ The final box (Describe Your Session needs...) includes plenty of space for users to submit a substantial and well-thought out response

### Brand Identity
+ The Headers font-familiess match the Style of the logo
+ The main page color scheme uses the monochromatic coloration of the logo
+ The pictures used maintain themes of family, digital enhancement, and photographers artistic brand 

## Potiental Client Examples
+ A: Is looking for a "candid" photo
    + Client sees the home page carousel and describes a business portrait in the "Describe your session needs..." on Contact Us page

+ B: Wants a frameable photo of child to give to grandparents  
    + Client sees the home page text describing photo enhancement, looks at the Gallery, and finds the photo enhancement sub-gallery where they see artistic photos and decide they want to hire this photographer for his 
    artistic brand 

+ C: Has an idea for a photo session that doesnt fit into any standard photo session
    + Home page has a section about custom projects with button to submit custom ideas and decides to reach out to photographer with an e-mail link found in the footer

+ D: Is looking for previously taken photos to be fixed from a previous photo editors poor work 
    + Client sees an artistic photo on the home page carousel they appreciate, decides to learn more about what the independent photographer and looks at the About Us section, after seeing the half edited and half original
    photograph they decide to use the session inquiry from found on the footer to submit a custom project 

## Live Protype Demo and Wire Frame
+ An active prototype can be found [here](https://richardaeld.github.io/MonaMemorabilia/ "Web Page") at github. 
+ The wire frame png's can be found [here](https://github.com/Richardaeld/MonaMemorabilia/tree/master/assets/wireframe "Wire Frame") also embedded at github.


# Testing
## Previous and Current Bugs
+ During the programming of this webpage, there were numerous graphical misalignments. These were primarily generated by Bootstrap creating padding and margins with as a result of using rows and container-fluid commands.
    These were easily taken care of with appropiate padding/margin removal and the use of "!important".
+ Various pages were not filling the entire screen on specific interface devices when using the inspect function in chrome. By giving the body the default color of the footer it gives the illusion that the footer background
    color extending to the bottom of the screen.
+ The file "Core.python3.2641.1592707923" will crash GitPod when attempting to delete it.
+ When viewing all sub-galleries at an i5 resolution in landscape (568px x 320px) while using the chrome inspect function, the top and bottom borders of photos cannot be seen due to the size of the nav bar and the 
    physical limitation of pixals on the screen.

## Not supported determined by BrowserStack and version of Bootstrap 
+ internet explorer 9 and older
+ opera 12.15 and older
+ firefox 3.6 and older
+ safari 8.0 and older

## Web Browsers that support transition effects used 
+ Chrome 26.0 and newer
+ Internet explorer 10 and newer
+ Firefox 16 and newer
+ Safari 6.1 and newer
+ Opera 12.1 and newer

## Scalability 
+ Adding a user operable slide bar to change images from edited to original could offer better repenstation of the digital enhancment section and About Us hero image (Would be neat but outside of scope of project)
+ The use of a modal in sub-gallery pages would allow for pictuers to pop up instead of relying on a clunky in-page nav 
+ Changing px to rem in css would help reduce code length in css and add better responsiveness to all pages on smaller devices 

## Web Programs used
+ pingdom results can be found [here](https://github.com/Richardaeld/MonaMemorabilia/tree/master/assets/pingdom)
+ browserstack results can be found [here](https://github.com/Richardaeld/MonaMemorabilia/tree/master/assets/browserstack)
+ W3C Validator was used to help identify errors in HTML and CSS


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
+ TinyPNG - Minimizing KB load per image
+ Fontawesome - Icons used
+ Google fonts - Fonts used 
+ Bootstrap - Used as framework
+ W3C Validator - Used to identify errors in code

## Web based references and code used from
+ [webaccessibilitychecklist](http://webaccessibilitychecklist.com/) - Helped with making web page ARIA accessible
+ [MDN web docs](https://developer.mozilla.org/en-US/docs/Learn/Accessibility/What_is_accessibility) -  Helped with understanding of when and how to use ARIA
+ [w3schools](https://www.w3schools.com/) - Helped with fine-tuning CSS and provided examples of advanced tricks involving *transition*, *hover*, and *scale*.  These can be seen in:
    1. Index (*Hover* button effects are found under "Custom Project" and *text-shadow* is used on the busisness name, Monachese Photography) 
    2. Main footer(*Hover* effect used for the social media icons)
    3. Gallery and sub-galleries (All nav images use the *scale* effect and a *box-shadow*)
    4. Sub-galleries (The clickable images use a *scale* and *transition* effect.  The other images use *box-shadow*)
+ [stack overflow](https://stackoverflow.com/) - Helped in understanding how to correct visual bugs with Bootstrap's automatic padding and margins
+ [bootstrap](https://getbootstrap.com/) - 
    1. Main nav (Used responsive design nav bar) 
    2. Index (Image carousel) 
    3. Contact us (Form) 
    4. Sub-Gallery(scrollspy was used for the in-page nav and the "invisible" properity was used to hide placement of in-page nav snap-to points)
+ Code Institute (Class) - Used footer design based on golden ratio and made social links like the examples shown in class
+ Used a visual reference from a classmate (Simon "jumboduck") for the About Us section. The idea that was used is a large hero image followed by the golden ratio of three text boxes that share 
    the background color of the page.

# Acknowledgements 
+ The idea for this website came from Micheal Monachese because of his photography forte
+ The photos and logo were all created by Micheal Monachese
+ Felipe Souza Alarcon for guidence and providing a plethoria of information and web-based applications
+ Emily Grooms for her wordsmithing skills





