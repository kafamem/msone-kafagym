# KafaGym Website

Welcome to [KafaGym](https://kafamem.github.io/msone-kafagym)

## Project rationale

The KafaGym project aimed at creating a website for business that targets gym members as site's users.
The main idea is to provide potential members with the needed information to better know 
about the gym and what are the procedures. These procedures involve becoming members and get to 
know how the gym works.

Therefore, at KafaGym our interest is to attract members and retain them through the provision of a better service as documented on the website.<br>

## User Experience (UX)

The website seeks to attract potential members at KafaGym. It has been designed in such way that its visitors will be able to navigate the 
the content easily and with help of eye catching features to attract their attention hence motivate their participation.

### User stories<br>
<ul>
    <li>First Time User Goal</li><br>
    a. As a first time user to the KafaGym site, I want to have information on the gym services and procedures.<br>
    b. As a first time user to the KafaGym site, I want to explore more about the site content through navigation.<br><br>
    <li>Regular users</li><br>
    a. As a regular user, I want to book a training session with an instructor at KafaGym through logging in my account<br>
    b. As a regular user, I want to access the eKafaGym app to track my last performance at gym so I can improve today.<br>
    c. As a first time user to the KafaGym site, I want to be able to sign up for membership and get in touch with organisation.<br>
    <li>Returning user</li><br>
    a. As a returning user, I want to find out about training groups and their community links.<br>
    b. As a returning user, I want to get in touch with the KafaGym organisation with any questions I may need to ask.<br>
</ul> 

### Design<br>
<ul>
    <li>Colour Scheme</li><br>
    - Three main colours (white, orange and dark grey) were used throught the entire design process of the site. Their combination originated from the branding logo KafaGym
    which is a gym logo from shutterstock customized to meet the KafaGym needs with help of Ai (Adobe Illustrator) where the coined word 'Kafa' was made out of two syllables <br>
    word with 'Ka' standing for 'Karenzi' and 'Fa' standing for 'Fabrice'; the names of the site developer then the word gym.<br><br>
    <li>Typography</li><br>
    - The Roboto font is the main font used for the entire website with Sans Serif as the backup font in case Roboto font does not respond correctly.<br>
    The Roboto font looks nicer on web pages.<br><br>
    <li>Imagery</li><br>
    The site was designed with high resolution images to make it look attractive. The logo designed with help of Ai was <br>created with a transparent background
    and is a vector based logo which makes it adjustable to various 'witdh' values without losing its original resolution.<br>
</ul>

### Wireframes
* Home Page Wireframe - [wireframe](https://github.com/kafamem/msone-kafagym/blob/master/assets/images/Landing%20page.png)

## Features

### Existing Features
<ul>
    <li>The site is responsive on all device sizes.</li><br>
    <li>Cards on home page are interactive upon hovering.</li><br>
    <li>The eKafaGym app link on About Us page targets to function after learning about software develpment. For now, it <br> 
    only points to membership sign up page.</li><br>
</ul>

### Features Left to implement
<ul>
    <li>Upon completing the JavaScript module, I hope to bring the site more to life through the design and use of interactive features.</li><br>
    <li>The showcase background picture on home which is now fixed will be replaced by a JavaScript slider function to allow a quick scan of<br>
    site content but at the same time creating an interactive site function.<br>
    <li>JavaScript will all also intervene in creating an interchangeable sign up vs. log in functionalities. It should be noted that the sign up form and log in<br>
    point to nowhere at this stage as there is a need for backend design to ensure a fully functional sign up and log in form.<br> 
    <li>Contact us form does not go beyond what is displayed on Contact Us page as well since there is a need for backend design.<br>
</ul>

## Technologies used

### Languages Used

* HTML5
* CSS3

### Framework, Libraries, Websites & Programs Used

1. [Bootstrap](https://getbootstrap.com/docs/4.5/getting-started/introduction/):
    - Bootstrap was used to ensure the responsiveness and styling of the website.
1. [Font Awesome](https://fontawesome.com/icons?d=gallery&m=free)
    - Font Awesome was used to add attractive icons.
1. [Google Fonts](https://fonts.google.com/)
    - Google fonts were used to import the 'Roboto and Sans-Serif' fonts used for typography.
1. [jQuery](https://jquery.com/)
    - jQuery was installed with Bootstrap to make the navbar responsive.
1. [Git](https://git-scm.com/)
    - For version control, Git was used mainly to commit with help of Gitpod terminal and Push to GitHub.
1. [GitHub](https://github.com/)
    - GitHub is used for storing the code pushed from Git.
1. [Illustrator](https://www.adobe.com/ie/products/illustrator.html)
    - Adobe Illustrator was used to create the logo.
1. [Balsamiq](https://balsamiq.com/)
    - Balsamiq was used to create the website home page [wireframe](https://github.com/kafamem/msone-kafagym/blob/master/assets/images/Landing%20page.png) during the design process.
1. [Befunky](https://www.befunky.com/create/resize-image/)
    - Befunky was such a handy website for picture editor used to resize images used in this project.
1. [ColorZilla](https://www.colorzilla.com/)
    - ColorZilla was such a handy extension used to pick the appropriate hexadecimal during the design process.

## Testing

In order to check the validity of the website code, the W3C Markup Validator and W3C CSS Validator were used on each page of the website to check the syntax errors.
* https://validator.w3.org/
* https://jigsaw.w3.org/css-validator/ (some css issues were identified but due to time constraints, I have been able to address them).

### Testing User Stories from User Experience (UX)
1. First Time User Goal
   1. As a user to the KafaGym site, I want to have information on the gym services and procedures.
        - Once the website home page is opened, a welcoming page with different sections is displayed. There is navigation bar that includes the KafaGym logo and the links leading to various pages.
        - The showcase image welcomes the user via the gym slogan and button link calling the user to become a member by click the Getting Started button pointing to the sign up page.
        - The user can also find out more about the sport types that are offered by clicking 'Learn more' on each of these found under Our programs (card area).
   1. As a first time user to the KafaGym site, I want to explore more about the site content through navigation.
        - The website layout is clear and simple to navigate. The navigation links make it easier for the user to know what kind of content expected upon clicking them.
        - The card area give a quick piece of information about each sport type while the footer provides the information about the gym location, opening hours as well as the subscription to newsletter. The user can also see 
   1. As a first time user to the KafaGym site, I want to be able to sign up for membership and get in touch with organisation. 
        - The site provides options for sign up for potential members under the link 'Sign Up/In'. However, the form does go beyond as it is not yet linked with the back end functionalities. User can also contact the organisation by filling 
          the 'Contact Us' form under the link 'Contact Us'; this is yet to be linked to the backend functionalities as well.
1. Regular User
    1. As a regular user, I want to book a training session with an instructor at KafaGym through logging in my account
        - Regular users will have the options to log in and book sessions after the creation of login form.
    1. The developer anticipate to create an that will help gym members to track their training progress.
1. Returning user
    1. As a returning user, I want to find out about training groups and their community links.
        - The site provides social links that will allow the gym community to stay connected and at the same increasing the gym visibility.
    1. As a returning user, I want to get in touch with the KafaGym organisation with any questions I may need to ask.<br>

### Further Testing
* The website was tested with help of different browsers; Google Chrome, Mozilla Firefox, Microsoft Edge and Safari browsers.
* The website was viewed through various devices including iPhone7, large screen and laptop to check it responsiveness.
* Pages were tested to ensure that they function correctly in order to allow an effective the navigation. The back and next buttons respond correctly on the website.

### Known Bugs
* The showcase image on the home page appears to be adapted to mobile device correctly from the simulated Google Chrome view. But in reality, the same picture 
seems to be streched on the real phone view.
* Due to time constraints, the sport page under the link 'Sports' was not styled as I wanted it to appear. There is also a clear gap between the footer and the background photo on 'Sign Up/In' page.

## Deployment

### GitHub pages
The following steps were followed to deploy the project to GitHub Pages:

1. After logging in to GitHub, locate the GitHub Repository
1. At the top of the Repository (not top of page), locate the "Settings" Button on the menu.
1. Scroll down the Settings page until you locate the "GitHub Pages" Section.
1. Under "Source", click the dropdown called "None" and select "Master Branch".
1. The page will automatically refresh.
1. Scroll back down through the page to locate the now published site link in the "GitHub Pages" section.

### Gitpod workspace
In order to deal with coding, I use Gitpod workspace. 
1. After logging in to Gitpod, I choose the 'kafamem/msone-kafagym' workspace.
1. Then I click 'Start' button adjacent to the workspace name. Then the workspace name opens the project design interface. This has terminals, coding area as well as the preview mode.

## Credits

### code
* [Bootstrap4](https://getbootstrap.com/docs/4.1/getting-started/introduction/): Bootstrap Library was used to ensure the responsiveness of the website.
* The entire gallery page code to was added bootstrap was copied from [W3schools](https://www.w3schools.com/).
* The about us page design idea was from Traversy Media tutorials via Acme Web Design project.
### content
* All the text was written by the developer.
### Media
* The photos used in this project were downloaded from [Shutterstock](https://www.shutterstock.com/) and resized to meet the website needs.
### Acknowledgements
* My mentor for her helpful guidance.  
* Tutor support at Code Institute their technical intervention.
* I was inspired by a number of projects:
  * [Templatemonsterpreview](https://www.templatemonsterpreview.com/demo/58939.html)
  * Beyond Bootstrap lecture from Code Insitute mini-project.
  * Traversy Media Tutorials.


