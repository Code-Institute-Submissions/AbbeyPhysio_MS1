# Abbey physiotherapy

### Code Institute - Milestone Project One: User Centric Frontend Development

For my project I decided to build a template website for my brother's business, a private physiotherapy clinic. He currently has just a landing page and wanted to increase the business's online presence. At the moment he relies on word of mouth and often has feedback from patients that they couldn't find him online. 

The live website can be accessed [here](https://allanahmurphy.github.io/AbbeyPhysio_MS1/).
 
## UX

#### Project Objective
The business goal of the website was to provide an increased presence online, similar to or better than that of competitors, providing information to patients and potentially attract new patients. 
 
#### User Stories
I created a number of user stories to help inform the requirements of the website, as detailed below. 

* As the business owner, I want to promote my business online so that I can attract new customers.
* As a user, I want to read about what treatments are available so I can decide if it's the correct treatment for my injury.
* As a user, I want to contact number for the clinic so that I can arrange an appointment.
* As a user, I want to send a query to the clinic to find out more information.
* As a user, I want to see available appointments and request an appointment so I don't have to call to book.
* As a user, I want more information on the location so I can easily find the clinic when visiting.
* As a user, I want to find out where the clinic is so I can plan where to park when visiting.
* As a user, I want to know about the physio's experience so I can decide if they are the right physio for me.
* As a user, I want to information on the classes offered so I can see if the time suit me.

#### Design Choices

I wanted the website to look professional and appropriate for type of business, i.e. clinical practice. I read about [colour psychology](https://neilpatel.com/blog/psychology-of-color-and-conversions/) and the preferences of different users for different types of websites. Based on this I decided on a blue/white colour scheme with accent colours for calls to action/emphasis. I choose blue as its perceived as safe, dependable and trustworthy colour and is preferred by both men and women. The palette of colours used on the website including accent colours is outlined below. 

<img src="./assets/images/colourpalette.png" width="100%" >

In terms of the overall design, I wanted the website to feel modern but not overally stylised or minimalistic. One of the main cohorts of the business's client base is older people so I wanted something easily accessible and readable with obvious calls to action (i.e contact or email business). The initial wireframe for the home page is shown below and while the design evolved during detailed design I think it still gives a strong sense of the final website. 

All wireframes created for the project can be found [here](https://github.com/allanahmurphy/AbbeyPhysio_MS1/wireframes). The wireframes were created using [Balsamiq](https://balsamiq.com/).  

<img src="./wireframes/wireframelandingpage.png" width="50%">

## Features

### Existing Features

#### Header, Navbar and Footer

Every page shares the same header, navbar and footer with the active tab changed to reflect the current page. Below outlines the features included in the header and navbar.

- Company logo and name linking back to home page;
- Two call to action 'buttons' linking to contact and booking form (only visible on larger devices as clutter smaller devices);
- Active page highlighted in navbar;
- Dropdown menu for subsection of services page;
- Accent colour on hovering over nav items;
- Collapsed hamburger navbar on smaller devices. 

Within the footer the following is included.

- Opening hours;
- Contact details with links to the contact page;
- 'Find us' info with address and google map image linking to the Find Us webpage and google maps (in another in window). 

#### index.html

Within the home page the following features are included (as well as the above):

- Hero image;
- Callout with important information related to recent reopening;
- 'Call Us' button which tiggers a modal call out with phone number;
- Three subsections providing brief overview of 3 of the other pages with links to read more.

#### about.html

- Brief history of the clinic history with link to services page;
- Bio of the head phyio with circular image;
- Bio of personal trainer with circular image.

#### services.html

- Overview of physio treatments offered for a range of conditions;
- Conditions presented in a collapsable text boxes as not to overwhelm user with unwanted text;
- Overview of personal training and yoga services with appropriate images.

#### contact.html

- form to send query with required fields;
- modal popup when submitted to with 'message sent' alert;
- form for booking app with date picker and time choices and another popup after submitting.

#### location.html

- directions to clinic;
- coloured card with address (only visible on larger devices to simplify UX on mobile);
- interactive google maps api with marker on clinic location. 

### Future Features

- 'Call us' button on home page hero image should link to actual call function on mobile devices;
-  Forms should connect to email;
-  Booking form is currently for show only with unconstrainted dates and random times shown this could be connected to or replaced by an online booking system in the future.

## Technologies Used

### Languages Used

* [HTML5](https://en.wikipedia.org/wiki/HTML5)
* [CSS3](https://en.wikipedia.org/wiki/Cascading_Style_Sheets)

A small amount of [JavaScript](https://www.javascript.com/) was used to implement Google Maps Api on location page. This was copied from Google developer tools [tutorial](https://developers.google.com/maps/documentation/javascript/adding-a-google-map).

### Frameworks, Libraries and Programs Used

- [Bootstrap v4.5.0](https://getbootstrap.com/) - Used for the responsove layout as well as custom components such as forms, modal popups, navigation bar, footer, cards and collapsable element.
- [jquery](https://jquery.com/) - Used in some of the clickable elements such as collapsable 'hamburger' nav bar.
- [popper.js](https://popper.js.org/) - Used in some of the clickable elements such as collapsable 'hamburger' nav bar.
- [Font Awesome](https://fontawesome.com/) - Font Awesome was used to add social icons throughout the site and improve overall design and legibility.
- [Google Fonts](https://fonts.google.com/) - Google Fonts was used to import 'Roboto' and 'Exo' fonts in the style.css stylesheet.
- [Git](https://git-scm.com/) - Git was used to allow for tracking of any changes in the code and for the version control.
- [GitPod](https://www.gitpod.io/) - GitPod, conected to GitHub, hosted the coding space and allowed the projected to be commited to the Github repository.
- [Github](https://github.com/) - GitHub is used to host the repository and publish the live website by using Git Pages.
- [Google Chrome developer tools](https://developers.google.com/web/tools/chrome-devtools) for testing and troubleshooting.
- [W3C Markup Validation](https://validator.w3.org/) used to validate HTML.
- [W3C CSS validation](https://jigsaw.w3.org/css-validator/) used to validate CSS.
- [Tiny jpg](https://tinyjpg.com/) used to reduce hero image size.

## Testing

#### Code Validation

Each page was ran through the W3C HTML validator and the stylesheet through the CSS validator. The following errors were flagged and corrected:

- Originally had anchors within buttons in the header which produced an error, changed to style anchors to look like buttons instead;
- Placeholder for form input for type date;
- Incorrect character escape on whitespace, removed this whitespace and created gaps with margins instead;
- arialabelledby related to no element ID, changed this to arialabel to solve.

There was additional warnings in relation to the date which flagged the date type would not be recognised on all browsers types. When tested it worked in each browser bar Safari. There were no errors or warnings flagged in the CSS validator. 

#### Browser Compatibility

The live website, hosted on gitpages, has been opened and tested on multiple browsers for responsives and intended appearance. Browers tested included:

* Google Chrome
* Safari
* Microsoft Edge
* Internet Explorer
* Firefox

Overall the website worked well and appeared as intended on different sizes across different browsers with the exception of IE where a number of elements were unexpectedly displaced. Firefox and IE were also slower than other browsers, I reduced the image sizes to improve this. Below is a summary of the browser testing. 

<img src="./assets/images/browerstest.jpg" width="100%" >

#### Responsiveness

The website has been tested across multiple screen sizes using [Google Chrome developer tools](https://developers.google.com/web/tools/chrome-devtools) for a range of screen sizes, portrait and landscape, including:

- Moto G4
- Galaxy S5
- Pixel 2
- Pixel 2 XL
- iPhone 5 SE
- iPhone 6/7/8
- iPhone 6/7/8 Plus
- iPhone X
- iPad
- iPad Pro

The screen was also adjusted through various sizes and breakpoints with the responsive option in developer tools. The website was also opened and checked on Huawei P10 and Samsung A20 mobile devices as well as Dell xps 15 and Apple Macbook. The responsiveness was also tested on the browsers outlined above with no noted issues. Overall the website appeared as intended across each screen type. There were some intial errors particularly on iPhone5 screen size (320px width) with overflows of titles and off center imagery. However, an additional media query was added to address this and all screens less than 400px approximately. 

### User experience & Usability

Multiple users of different ages (friends, family members, CI peer review group) were asked to open the devices on mobiles and laptop to sense check the layout, readability and usability of the site. Comments back included the below:

- One user found initial colour chosen for button hover difficult to read (this was changed);
- One user expected 'Call Us' to provide phone number instead of leading to contact page (this was updated to include pop up with phone number);
- One user didn't like initial border circles (too PowerPoint 2003!). I agreed in reflection and amended image styling. 
- One user expected some event when hitting send message button on forms, even if forms weren't techically required to work. I addressed this by providing the popup boxes. 

A thorough review was also done across all pages and links to ensure they were mapped correctly and no unexpected errors were thrown up. 

### Overflow

[Unicorn Revealer](https://chrome.google.com/webstore/detail/unicorn-revealer/lmlkphhdlngaicolpmaakfmhplagoaln/related) was also used to test all pages for overflows with none found. 

### Performance Testing

Chrome developer tools was used to undertake a performance audit of each page. Generally the pages performed well with the main issues relating to loading time of external scripts and stylesheets from Bootstrap & Font Awesome. The loading of Google Maps on the 'Find Us' page had the biggest impact on load times. Other issues which were addressed were images sizes which were reduced using Tiny jpg and the addition of meta description to the head for each page. 

### Known issues

I've fixed the header to the top of the screen as I think this makes website easier to navigate. I dropped the content below this so there is no content blocked. However, when navigating to one of the in page anchors (Personal Training/Yoga and Pilates classes) the header blocks the heading. I've tried various fixes for this with no success. I've still left the navbar fixed as I believe the benefit of it outweighs the minor error. 

## Deployment

There is  one branch of this project (master) and the [deployed version](https://allanahmurphy.github.io/AbbeyPhysio_MS1/) of this site is the most current.

### Deployment Steps
To deploy this page to GitHub Pages from its repository, the following steps were taken:

1. From the menu items near the top of the repository page, select settings;
2. Scroll down to the GitHub Pages section;
3. Under source click the drop-down menu labelled None and select Master Branch;
4. On selecting Master Branch the page will be automatically refreshed and the website is now deployed;
5. Return to the GitHub Pages section in settings to retrieve the link to the deployed website. It may take a short time for the deloyment to go live. 

### Cloning Locally
To clone this project from GitHub:

1. Under the repository name, click Clone or download;
2. In the Clone with HTTPs section, copy the clone URL for the repository;
3. In your local IDE open Git Bash;
4. Change your current working directory to the location where you want the cloned directory to be made;
5. Type git clone, and then paste the URL you copied from the https section of the repository;
6. Press Enter to create your local clone.

More information on cloning from github can be found [here](https://help.github.com/en/github/creating-cloning-and-archiving-repositories/cloning-a-repository).

## Credits

#### Code

Code was taken directly from the following sources and adjusted to fit the website:

* [Bootstrap Collapse Navbar](https://getbootstrap.com/docs/4.1/components/navbar/);
* [Bootstrap Modal Popups](https://getbootstrap.com/docs/4.1/components/modal/);
* [Bootstrap Forms](https://getbootstrap.com/docs/4.1/components/forms/);
* [Code Institute Whiskey Pages Example](https://github.com/Code-Institute-Solutions/BootstrappingYourNextBigIdea-BS4/tree/master/04-BeyondBootstrap/03-cleaning_up_our_content);
* [Google Developer-Adding embedded google maps with marker](https://developers.google.com/maps/documentation/javascript/adding-a-google-map);
* [Horizontal Rule with fade styling](https://codepen.io/ibrahimjabbari/pen/ozinB**/).

#### Content
 I, or the business owner, wrote the majority of the content with some text copied from the sources below:

* [World Health Organisation](https://www.who.int/news-room/fact-sheets/detail/musculoskeletal-conditions);
* [Irish Society of Chartered Physiotherapists](https://www.iscp.ie/maintain-your-health/sports-injuries);
* [UK Society of Chartered Physiotherapists](https://www.csp.org.uk/conditions/chronic-pain).

### Media

The following is all images used on the website and the source, most were found using google image advanced search with 'free to use, even commercially' criteria applied.

* The Hero Image was purchased from istock and can be found [here](https://www.istockphoto.com/ie/photo/therapist-treating-injured-knee-of-athlete-male-patient-gm952643772-260070904);
* Picture of Head Physiotherapist, Paul Murphy, is the business owner and provided by him;
* Picture of personal trainer was found via google free image search and can be found [here](https://pxhere.com/en/photo/435643);
* Picture of man lifting weights was found via google free image searcg and can be found [here](https://www.wallpaperflare.com/man-lifting-weights-photo-fitness-men-sports-gym-exercise-wallpaper-aaumd);
* Picture of woman doing yoga pose can be found [here](https://www.pickpik.com/yoga-asana-pose-hatha-woman-white-53488).

### Acknowledgements

I'd like to thank my mentor, Precious Ijege, for his time, advice and patience on this project. I should also thank various friends and family member who took time to review and provide feedback as well as the Code Institute Peer Review Slack Channel. 



