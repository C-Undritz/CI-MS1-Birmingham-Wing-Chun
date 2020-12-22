# Birmingham Wing Chun Website - Readme document

<img src="assets/images/readme-header.png" style="margin: 0;">

# Overview.
The Birmingham Wing Chun clubs have been operating since 1982 and in that time has seen the club profile increase with the opening of more clubs round the West Midlands.  At the same time competition has increased with four dedicated Wing Chun organisations opening clubs in the area.  

Student numbers continue to grow, however questioning these students it has been revealed that the interest in the club was not mainly driven via the website, but mainly through social media platforms and word of mouth.  This is reflected in the website stats.  

The existing website is old and does not reflect modern website design ethos in terms of layout and responsive design across devices.  It has therefore been determined that the clubs online profile is in need of an update with this new and modern website that is focused on getting more potential students in through the door and training.

---
# Strategy.
The strategy behind the website is to deliver key information through a streamlined experience where the potential student feels informed and will the opportunity to question further at club locations or via an interactive contact form hosted on the website.  The website is not designed to be an extensive and detailed resource about the club and Wing Chun.  

## Organisation Goals.
* Increase the profile of the club in the face of increased competition
* Have a slick modern online presence which can be controlled
* Inform and attract potential students.

## User Stories.
* *I want to be able to have a good user experience on a mobile or tablet as I do not have access to a desktop PC or laptop out of the workplace.*
* *I want to be able to easily navigate the site on any platform.*
* *I want to know what Wing Chun is.*
* *I want to get an idea about what it would be like to train at West Midlands Wing Chun Kuen.*
* *I want to know the location(s) of the Wing Chun club where I can train.*
* *I want to know what the training schedule at each club so I can determine if the club is an option for me.*
* *I want to know, as a new student, what is the cost of training and are there any payment options.*
* *I want to know if I need insurance to train and if so, how much will it be?*
* *I want to be able to contact the club to ask any questions that I may have about a specific club location if required.*
* *It would be good to be able to easily check out the clubs presence on social media to give me a further idea as to who trains there.*

---
# Scope
## Content
The information presented in the site has been purposefully kept minimal and focused to keep the user attention so as to reduce the risk of overloading the user; potentially driving them away to another club/martial art.  

### The content has therefore been designed to keep the user attention by:
1.	Providing enough information so an informed choice can be made.
2.	Ensuring that the experience across a number of devices is satisfying.

### The information presented is concerned with:
1.	Being the first place the users will land if searching online for Wing Chun in the West Midlands
2.	Engaging users with an impactful landing page promoting the club
3.	Informing the users about the club, where to train and costs
4.	Informing the users about Wing Chun and its history

### Functional Requirements.
1.	Responsive design; assumption is that most users will browse through to the site from a mobile or tablet, therefore Bootstrap grid was used to ensure that the website is responsive.
2.	Permanent top Nav bar on every page to aid navigation.
3.	Link to home page/landing page from logo positioned left in the Nav bar
4.	A clear and intuitive contact form for further questions to be asked
5.	Clear and obvious links to the clubs presence on social media platforms
6.	Feedback animations to provide user with clear interaction cues for buttons, media boxes and links

---
# Structure
The website consists of five pages:
1. Home/landing page
2. Classes
3. About
4. Contact Us
5. Gallery

## Navigation
Navigation between and within the five pages will be facilitated by:
1. Navigation background
2. Six links from the landing page to the six main section in the 'Classes' and 'About Us' pages.

This is in line with current website design and UX trends.

## Consistent Features between pages.
Each page has a responsive fixed Navigation bar with five links justified to the right to link to each of the five pages.  A logo is present in the top left that links to the home page.  A footer is present on every page with social media icons linking to the Facebook, twitter, Instagram and YouTube.

Each page features an appropriate banner image with text, apart from the home page that has a hero image filling the screen so as to present an impactful first impression of the site and so encourage the user to explore further.

#### Possible additions:
* For Mobile and tablet UX only: have a 'hub and spoke' design between content and discover section with introduction of a permanent function/button for ‘back to discovery’ section.

---
# Skeleton
## Wireframes
Current version(v0.3):
* [Mobile](assets/readme/LearnWingChun_mb_wireframes_v0.3.pdf)
* [Desktop](assets/readme/LearnWingChun_dk_wireframes_v0.3.pdf)

Archive Wireframes - original design(v0.2).  
The design in these wireframes was changed following initial user testing.  The changes are 
detailed in the section 'Noted design changes' later in this document.
* [Mobile(v0.2)](assets/readme/LearnWingChun_mb_wireframes_v0.2.pdf)
* [Desktop(v0.2)
](assets/readme/LearnWingChun_dk_wireframes_v0.2.pdf)

## Home/landing page.
To have the most impact, the home screen features a full screen hero image with text leaving the user in no doubt as to what is offered by the organisation.  On tablet and mobile the hero image is muted so that the text remains clear.  There is a call to action button, which prompts the user to ‘find out more’.  Selecting this moves the page down to the ‘discovery section’ which is the third section of the home page.

The second section is for promotion of Wing Chun and the club; bullets points detailing benefits and testimonials.  I wanted here to have an image of a woman training so as to point out that this is a martial art for women as well.  I wanted this image to be the second one on the home page after the impact of the hero image.

The third section represents a hub second of the site a ‘discovery section’ which consists of 6 boxes which link directly to sections featured the ‘about’ and ‘classes’ pages.  

The six sections linked from here are:
* What is Wing Chun?
* History of Wing Chun
* About the Club
* Training Schedule and Prices
* Club Locations
* What to Expect.

All six boxes have relevant images, icons and text so that the user is clear what they are navigating to from each box.  User feedback animations have been applied consistently across all six boxes for hover and select for the desktop experience.  This is disabled for the tablet and mobile experience.

## Classes
The Classes page hosts three sections from the ‘discovery section’:
* Training Schedule and Prices
* Club Locations
* What to Expect.

Below the banner image the three boxes from the discovery section for these are replicated so as to act as quick links to the respective section on this page. Each section features text and images relevant to the subject matter.

### Training Schedule and Prices section……
### Club Locations section……
### What to expect section……

## About
The About page hosts three sections from the ‘discovery section’:
* What is Wing Chun?
* History of Wing Chun
* About the Club

Below the banner image the three boxes from the discovery section for these are replicated so as to act as quick links to the respective section on this page.  Each section features text and images relevant to the subject matter.

## Contact Us
The contact page features a contact form which requests:
* Users name
* Users email address
* Details of their query

These are all required input for the query to be sent

It also features a radio button where the user can detail which club their query is about.  It is not required that the user use these as there query may be a general query.  It is planned that the query can be directed to a specific person within the club depending on the radio button selected.

The form finishes with a ‘Submit’ button.

## Gallery
The gallery images are presented as a page of images that resize to fit the screen size for various devices and fulfil the requirement for responsive UX.

Each images can however be selected which then opens a fancy box window to view the image and then to move onto the next image, the previous one or return to the gallery page in the background.

---
# Surface.

## Colours
The club colours are blue and yellow and so I wanted to incorporate these throughout the site to break up the sections.  

Palette:

![alt text](assets/readme/palette.png "Proposed palette of five colours to be used on the site for all design elements")

## Fonts:

---
# Technologies used:
* HTML5
* CSS3
* Bootstrap
* Gitpod
* GitHub
* GoogleFonts
* Fontawesome
* Balsamiq
* Fancybox (http://fancyapps.com/fancybox/3/): Used for the gallery.
* Canva (https://www.canva.com/): Used as a quick and easy way to crop images to pixel specific dimensions
* Microsoft PowerPoint: used to create a transparent background for images for the browser tab and Chinese symbols on homepage banner.


Bootstrap technology used:
* Container
* Grid
* Buttons
* Card
* Carousel
* Modal
* Navbar
* Flex
* Spacing

---
# Testing
Testing to be completed is detailed in the [TESTING.md](TESTING.md) document

---
# Noted design changes
* User testing was done on the website in a 70% completed stated with all of the main navigation elements in place including the 'discovery' section at the bottom of the index (home) page, which the user was encouraged to access via the 'learn more' button on the landing page.  It was found that the users liked the experience of the 'discovery' section and therefore wanted to get back to it to continue navigating from there.  However as they had used the 'learn more' button to access the 'discovery' area, they did not know that it was at the bottom of the home page and so they quickly got lost.  They were further confused when they then used the top nav menu to access the pages directly to then discover that they had already seen the content by using the 'Discovery' section.  This lead to an overall bad user experience navigating the site.  This was remedied by changing the navigation elements at the bottom of the home page to three links to the ‘about us’, ‘classes’ and ‘gallery’ pages which can be seen in the updated [wireframes](#wireframes).  This mirrored the navigation of the top navigation bar and offered a better UX with multiple ways to navigate the site depending on the user habits and expectations.

* The above lead to a further removal of the links to the three sections on the ‘about us’ and ‘classes’ pages as it was determined that these did not add to the user experience.  The user tended to use them once (if at all) however as they had to scroll up to get back to them they were not used again and they chose to scroll instead of using these links.

* Change in the way the club locations and schedules displayed.  The wireframes show against each club location a 'GoogleMap' and then the address of the club to the right/left.  The final implementation was completed with Bootstrap 'cards' which allowed an image of the club to be shown which would be helpful to students.  The GoogleMap was then linked from a button within the card.  It was thought that also adding the club training times here would make for a better user experience, however in order to avoid extending the height of the cards further, an additional button was added which causes a 'modal' to display with the club training times. 

* An issue was experienced with the design of the contact us page and the display of the form over the banner.  Please see the Problems and fixes section in the TESTING.md document for details.  This issue along with the need for this page to look more like the other pages lead to the design change to move the form to a position on the page that was below the banner.  This change was more in keeping with the presentation across the site and solved the issue.


* Change in the colour blue used.  The orginal chosen blue colour (#195ACC) when applied to the website elements (navigation bar, footer and section headings) looked too light *in situ*.  Therefore it was changed to the clubs original blue colour (#000066), which while dark in large areas, was thought to be well suited to the mentioned website elements. 
---
# Deployment

---
# Credits
* Anna Greaves for the code for enabling FancyBox to work at Mobile resolutions.
* Thanks to members of the Slack community for their support and help, particularly Mr_Bim_alumni, JimLynx_lead and Daisy Mc Girr.

## Code:
1. Simple one, but I had to look it up: [how to hide an image for responsive design](https://www.thesitewizard.com/css/hide-images-on-mobile-website.shtml)
2. [How to insert a space in text](https://www.wikihow.com/Insert-Spaces-in-HTML)
3. CSS Image styling for some responsive design: [w3schools CSS Styling Images](https://www.w3schools.com/css/css3_images.asp) 

## Help:
* Thanks to my fellow students who were on hand to lend wisdom and knowledge during in-it-together 11am coffee calls and other times when I had run out of hair!  special thanks to Jim Lynx for pointing out the obvious and not-so-obvious, and for the help with the Gitpod GUI as well as helpful tips like 'putting media querys at the end of your css' (something I would never have figured broke my footer!).