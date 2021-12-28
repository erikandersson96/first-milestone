# Andersson's 

A website for people to get in touch with Andersson's, a business that focuses on service wristwatches. Give their customers older wristwatches a fresher look and with a movement in better condition. 

Take a look [here](https://erikandersson96.github.io/first-milestone/index.html) 

![Am I Responsive, to show the website on different screen sizes]()





## Milestone Project One 

---

### Intention 

This website is a fictional website for the purpose of my First Milestone Project for Code Institute’s Full Stack Software Developer Course. I created this website with the knowledge I gained from the HTML and CSS modules. 

The main goal of this project was to create a website for people to easily get in contact with a professional wristwatch company that services and cleans used watches for their customers. 

* Features I aimed to achieve with this project: 

 * To make the site easy to read. 
 * Create good contrast between the background and text (Only use Black and White colors).
 * Use Text Overlay for my text to create a “stand out” feeling and catch the attention of the user. 
 * Use a Navigation Bar that is easy to understand and easy to navigate between the three pages. 

---


## Table of Contents 
---

* UX 
  * Visitor Goals 

* Website Design 
  * Color Scheme 
  * Fonts 

* Existing Features 
  * Navigation Bar 
  * Landing Page (Hero image)
  * Footer 
  * About us 
  * Get in touch 

* Future Features 
  * Learning Points 

* Testing 
  * Devices 
  * Validator Testing 
  * Lighthouse - Dev Tool 
  * Wave Page 
  * Fixed Bugs 
  * Unfixed Bugs 

* Deployment
  * Creating My Website 
  * GitHub Pages 

* Credits 
  * Content 
  * Media 

* Support 

---


## UX 
---

### Visitor Goals 

* To quickly understand what the website is all about and to easily navigate between: Menu I About us I Get in touch. 

* To collect visitors' contact information to give them a quote that includes a better understanding of what Andersson’s can offer for them since every wristwatch is unique. 

* To be accessible on all devices. 

---


## Website Design 
---

Every Page on the website contains a Navigation menu at the top left of the Webpage. It is used to easily navigate between Menu I About us I Get in touch. It is featured on all three pages. 

Logo design - Because this website was created with the intention to keep it clean and simple. I decided to go with only “Andersson’s” instead of “Andersson’s Watch Restoration” or “Andersson’s Watch Service”. It also gave a better visual experience on smaller screen size devices. 

Background Image (Hero image) - I downloaded this image from pixabay.com which is a website with free images. The background image is used on all three pages and I used a black background color to it in case the image wouldn't load. 

Website Colors - I went for only Black and White to keep it clean and simple. 

Text Overlay - I used Text overlay for all text and the contact form on the page to let the Background image stand out and make it look better. 


### Color Scheme 

* I chose four different colors for the website. Black, White, and medium-light grey for the Text Overlays to give it a good contrast to the background image. 

**#fff - White (HEX-color)** 

![A white box with a thin grey border around it]('../assets/images/white-box.png')

**#000000 - Black (HEX-color)** 

![A black box]('../assets/images/black-box.png') 

**rgba (6, 6, 8, 0.753) - Medium light grey (RGB-color)**
This represents the Text Overlays, notice that it is transparent. 

![A transparent box]('../assets/images/transparent-box.png')


### Fonts 

* I used three different fonts for the website. Oswald for all h1 and h2 and “Open Sans” for all body elements with sans-serif as a backup if “Open Sans” wouldn’t work. The submit button and the call to action button on the About us page are both using Arial. The Oswald and “Open Sans” fonts were taken from Pairfonts. Arial is a default font. 

**Oswald, h1, and h2:** 

![Image that displays how font Oswald look]('../assets/images/oswald-image.png') 

**Open Sans, body:** 

![Image that displays how font Open Sans look]('../assets/images/open-sans-image.png') 



## Existing Features 
---

### Navigation Bar 

* Used for all three pages. Consisting of one Unordered List containing 
  Home | About us | Get in touch. 

![Screenshot of the Navigation bar]('../assets/images/navbar-image.png')

---
### Landing Page   

* The landing page includes an image of a watch with a black background to make it stand out. The Background image is used for all three pages. I used Text Overlay to create a nice effect to the background containing a text with: “Life is too short to waste on a great watch. - So give it all the love it truly deserves!”. 

* This creates an eye-catching animation to grab the user's attention. 

![Screenshot of Landing Page]('../assets/images/landing-page.png')

---
### Footer 

* The footer includes all the social media links to the relevant social platform. The links will open in a new tab to not confuse the user, or open each social platform application on the device if the user interacts on a mobile device or tablet. 

![Screenshot of Footer]('../assets/images/footer-image.png')

---
### About us  

* The about us page is to inform the user about the business and what we aim to achieve in the services we provide to our customers. This is also created with Text Overlay to make it stand out from the background image without hiding it.

* I also added a Call to Action Button underneath the About us information to direct the user to the contact form directly. 

![Screenshot of About us page]('../assets/images/about-us-page.png')

--- 
### Get in touch 

* The Get in touch page includes two Text Overlays. The first one holds information about pricing and what services we offer. The second one is the contact form used to get the user’s contact information. The user has to fill in: First Name, Last Name, E-mail, Brand of the watch, Budget, and additional information about their watch as Year, Condition, and if it is functional. All text boxes are required to be filled in order to hit the Submit button underneath. 

* The Contact form is refreshed when clicking on the Submit button. It will also show the user that he or she needs to fill in all of the input fields that are * required with a warning text. 

* The input field for Budget only accepts numbers. 

![Screenshot of Get in touch Page]('../assets/images/get-in-touch-page.png') 



## Future Features 
--- 

### Learning Points 

* I'd like to include feedback to the user so they are aware that the information was submitted from the Contact Form. I didn't have the knowledge to include a “Thank you for Submitting” pop-up or redirect to a new page. But I will include this as soon as I have the knowledge required to do so in the next projects. 

* I made some mistakes when positioning each element: the text on the first page, the About us page, the Price information, and the Contact form on the third page. I used “absolute” instead of “relative” position which forced me to create a total of 13 Media Screen size breakpoints. This is a mistake that I will take with me into the next project and improve upon to increase the amount of breakpoints. I will also start with creating the website for my next project on a mobile device first because it's much easier to expand the screen size than increase the screen size as I did with this project, which resulted in a lot of time waste. 

* I also learned when git commit a message in Gitpod I should have only included what was relevant to that commit. I may have committed a message which included more changes than I added in that exact commit message, not only once but a couple of times. This is something that I will improve in my next project to be more consistent and correct with my commit messages. 

* The way I structured my Media Screen size breakpoints will improve for future projects. When I ran the W3C CSS Validator I got a ton of errors because I had included attributes in every @media query even if they were not changed between screen sizes which resulted in 287 parse errors, but they are all fixed now. 
