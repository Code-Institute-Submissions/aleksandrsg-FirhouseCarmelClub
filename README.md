# Firehouse Football Club #

This project is developing for a real football club.
The original version of web site you could find by the following link http://www.firhousecarmel.com.
Firhouse Carmel Football Club was founded in 1974 to cater for Schoolboys and girls in the local area.
In this project you will find the new web site design for Club.

### UX ###

The main goal is help to find for  parents (site users / local community) information about  local football club for kids and youth.
On the other hand, the web sites owners will get more recognition and advertisement via
world wide web.

Projects wireframes are located in the directory https://github.com/aleksandrsg/FirhouseCarmelClub/tree/master/assets/wireframe
##User stories##

New to the website I am looking for local football club;

As user, I could find out contact information;

I want to be able to phone or write an email to the football club and receive feedback;

As user, I could find out club location;

I want to be able to fill registration form and send it;

As parent, I could see photographs and videos from the club matches;

As sponsor I could find the club for financial support;

As viewer, I want to find links to other club social media resorces like Instagram, Facebook, Twitter.

### Features ###

The web site consists from four conected with each other web pages.
The site developer could add new pages to this web site if necessary.
Page 1 is Home. from this section user could go to any sites sections or pages.
Page 2 is About, in this section the user will find information about club main aims and goals.
Page 3 is Contact, in the third section user will find all contact information such as phone number, email
and location map.
Page 4 Registration, in this section user will fill the registration form.
There is a extra link called Version 1.0 for visiting original web site.
Added Page 5 called Gallery with three fotos. 

### Testing ###

Project testing was carried out manually in Web browser. 

To remove horizontal scroll from all pages I added for Tag <Body> style (overflow-x:hidden;) and horizontal scroll line disappeared.
  
Added sticky-top class for header section to sticky menu on the top while scrolling page down.

Project CSS file called style.css have checked by online Validator https://jigsaw.w3.org/css-validator/ and all critical errors were removed. Also HTML code of each page was checked and approved by online Validator by following link https://validator.w3.org/#validate_by_input.

Testing Home Page.

I begun testing from the first page of the project, Home. 
Most critical errors from this page was:
At the beginning of the project site Logo was located in the top-middle of page and had a big size, after that Logo had been moved to the left-top and minimized in size; 
Logo was not displayed as incorrect source link, fixed logo source link;
The same problem was with the background image source link, internal link was change to external link https://www.essentiallysports.com/wp-content/uploads/football-2518982_960_720.jpg and image started to display;
Menu toggle button worked incorrectly. When toggle button was pushed the main menu overlapped the image, the problem was fixed and now menu opens correctly and background image go down.
On some pages footer section was high in mobile version, have made some adjustments to move it down. 

Testing page About.

Page main text was displayed too much to the left side, it was fixed by moving it to center.

Testing page Gallery.

Text inside the image was too small, fixed by increase of the text size.
Side arrows inside image was too small, fixed by increase of the arrows size.
The photos for Gallery have been taken from free resource https://ru.freeimages.com/
Particular attention during development and testing was given to the mobile version of the site so that all elements do not go over each other or behind the screen. Many testing with fonts-sizes, elements colors, margins and paddings to make page looks good.

I have made the following improvment for Project re-submition:
* Applied linear-gradient for backround image to make it darker, that front text looks better.
* For MENU applied position sticky-top, that it always stays on the top.
* Each page has unique <Title>.
* Added user stories and wireframes.
* Images in Gallery now have correct size and response according screen size.
* Added comments in CSS file.
* Added more detailed description about project deployment.
* HTML and CSS codes checked via Validators.
* Created folder Assets for better file organization.
* Added more micro commits with correct messages while working on improvemets.
* Added others improvenments.

### Deployment ###

This project was started in 13th of October and finished till 10th of December 2019.
Each project step was developed in GitPod IDE, tested in Google Chrome browser with web developers tools and commited to GitHub. Totally for this period was made 31 commits to GitHub from GitPod IDE. 
All developing process you could track by visiting this source: https://github.com/aleksandrsg/FirhouseCarmelClub/commits/master.

Deployment steps:

1. Open github.com;
2. Find plus symbol on the top right conrner and click it;
3. Choose function New Repository;
4. Fill section Repository name - FirhouseCarmelClub;
5. Choose Public (Anyone can see this repository. You choose who can commit);
6. Push Create Repository;
7. The Repository created https://github.com/aleksandrsg/FirhouseCarmelClub.git;
8. Press GitPod green button on the right side;
9. Create first Document index.html;
10. In terminal window command line type - git add . ;
11. In terminal window command line type - git commit -m "Comment";
12. In terminal window command line type - git push;
13. Go back to https://github.com/aleksandrsg/FirhouseCarmelClub;
14. Click settings;
15. Find below section GitHub Pages and choose Master branch;
16. Your site is published at https://aleksandrsg.github.io/FirhouseCarmelClub/

### Technologies Used ###

To complete this project the site developer uses HTML, CSS languages and framework BOOTSTRAP.
The project was developed and tested in Gitpod IDE and transferred from Gitpod to Github external repository.

Project css file was minified. To minify css file I have used online resource:
http://minifycode.com/css-minifier/

You could see the favicon in the page title. To do favicon.ico file I used:
https://www.icoconverter.com/

Thank you and enjoy!
