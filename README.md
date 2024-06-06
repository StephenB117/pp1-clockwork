# Clockwork 

Clockworks website is intended for management and HR professionals seeking time and attendance solutions as well as an all in one HR management platform. 

The site breaks down some of the features the product offers hoping to sell the user on the software.

The site will open on the main page which explains a little about the company and what it offers. 

From there the users can explore the solutions page to see what we offer and what they can benefit from. 

Lastly if they wish to make any enquiries or organize a follow up call they can submit their details through the contact us page.


![Picture of the website on different devices](/assets/images/responsive-design.jpg)

## WireFrames and UX design

### Design thought process
My thought process on the general design of the website was to keep it simple. 

Using a black header and footer to frame the content as well as contrasting with the navigation and social links well. 

The header and footer have been kept consistent throughout scrren sizes with the only difference being the burger menu on small screens. 

Naviagtion between the pages to be done using the links contained in the header with the current page highlighted so the user knows what page they're on.

When hovering over any links the background changes color for visual clarity on what the user is mousing over when on desktop. 

![Picture of the website wireframe](/assets/images/pp1-website-view.png)
![Picture of the Tablet wireframe](/assets/images/pp1-tablet-view.png)
![Picture of the Mobile wireframe](/assets/images/pp1-smartphone-view.png)
## Features

### Features in all pages
The header features a burger icon on mobile devices that opens a navigation menu to direct users to the other pages. with the current page being highlighted in inverse colors to the rest of the menu.
On larger devices the links to the other pages are displayed on the left of the page again with the current page being highlighted in inverse colors to the header. 
The name of the company in the header will also link back to the home page from any of the other 3 pages. 
The footer displays the copyright of the company and link icons to facebook, X and Linkedin.

![Picture of the header on mobile devices](/assets/images/mobile-header.jpg)

![Picture of the header on larger devices](/assets/images/large-header.jpg)

![Picture of the footer on all devices](/assets/images/footer.jpg)


### Home 
The home page tells users a little about the company, its goals and why perspective customers should choose us. 

![Picture of how the Home page looks on mobile devices](/assets/images/mhome.jpg)

On mobile devices this will only show text content.

![Picture of how the Home page looks on larger devices](/assets/images/thome.jpg)

On larger devices this will show the text as well as two images above and below the text

### Solutions
The Solutions page tells users about the solutions the company offers, Time tracking, Roster management and scheduling, HR management and Skills management and documentation. 

![Picture of how the Solutions page looks on mobile devices](/assets/images/msolutions.jpg)

On mobile devices this will only show text content.

![Picture of how the Solutions page looks on larger devices](/assets/images/tsolutions.jpg)

On larger devices this will show the text as well as two images above and below the text

### Contact Us
The Contact Us page allows users to request someone from the company to call them to answer any questions they may have about the product and the next steps to implementing the product in their business.
This page requests the users name, Phone number, email, company name and what solutions they are interested in implementing to their company.  

![Picture of how the main content looks on the Contact Us page on both mobile and larger devices](/assets/images/mcontact.jpg)

## Testing: 

### Validator Testing: 
HTML: Code was run through the official [W3 Validator](https://validator.w3.org/nu/). No errors were returned. 

CSS: Code was run through the official [Jigsaw Validator](https://jigsaw.w3.org/css-validator/). No errors were returned. 

Regression Testing: 

|Action|Expected Outcome|Pass/Fail|
|:---------|:----------:|----------:|
|Opening the link to the website|Website opens on the index.html page|Pass|
|Mousing over links|Each page link, main heading and social media icons inverts the color of text and background|Pass| 
|Clicking on the Solutions link|Opens and loads solutions.html|Pass|
|Clicking on the Contact Us link|Opens and loads contact.html|Pass|
|Submitting form on contact us with no information entered|User should be promoted to enter their name|Pass|
|Submitting form on contact us with only name entered| User should be prompted to enter their email|Pass| 
|Submitting form on contact us with name + email entered| User should be prompted to enter their phone number|Pass| 
|Submitting form on contact us with name + email + phone number entered| User should be prompted to enter their company name|Pass| 
|Submitting form on contact us with name + email + phone number + company name entered| User should be prompted to enter which solutions they are interested in|Pass| 
|Submitting form on contact us with all information entered| Users should be redirected to Code Institues formdump page and see the information they entered|Pass| 
|Clicking on the Home link| Opens and loads index.html|Pass|
|Clicking on the company name in the header|Opens and loads index.html|Pass|
|Clicking on Facebook icon in footer|Opens and loads facebook.com|Pass|
|Clicking on X icon in footer|Opens and loads x.com|Pass|
|Clicking on LinkedIn icon in footer|Opens and loads linkedin.com|Pass|

Lighthouse report: 

Desktop index.html

desktop solutions.html

desktop contact.html

Mobile index.html

Mobile solutions.html

Mobile contact.html

## Deployment: 
This site has been deployed to GitHub Pages.
The steps to deploy the site are as follows: 
 - In the GitHub repository go to settings. 
 - Click on the pages tab under "Code and automation"
 - Under "Build and deployment" for the source select deploy from branch
 - Under "Branch" select main and /(root) and click save
 - The page should refresh and the link to the website should be at the top of the page. 
 - If like me this did not happen you can find the link to the website by doing the following. 
    - In the repository at the top of the page select actions
    - Click on the most recent "pages and deployment"
    - This will give you the status of the deployment as well as the link to the deployed site


If you wish to clone this repository you can do so by doing the following: 
- Go to the code page in the GitHub repository
- click on the down arrow on the code button next to "add file" 
- Copy the url given under HTTPS to clone using a web URL
- On your desktop open the command line. 
- In the command line type "git clone" and then paste the copied URL 
- If Git is installed on your computer it will initiate a download of the files from the repository

The link to the deployed site is https://stephenb117.github.io/pp1-clockwork/

## Credits: 
### Content
Code content: 
- Navigation menu code was taken and edited from the Love Running project.

Form submission: 
- Submitting the form takes the users to Code Institutes form data dump to show the data was recieved and the form is working 

Social Media Links:
- Link for Facebook taken from [Facebook](https://www.facebook.com/)
- Link for X taken from [X](https://x.com/)
- Link for LinkedIn taken from [LinkedIn](https://www.linkedin.com/)

### Media 
Images:
- Stock images taken from [Pexels](https://www.pexels.com/)
- Stock images taken from [Adobe](https://stock.adobe.com/ie/)

Icons: 
- The three social media icons as well as the copyright icon used in the footer were taken from [FontAwesome](https://fontawesome.com/)

Fonts:
- The fonts selected for this site were taken from [Google Fonts](https://fonts.google.com/)

Wireframes:
- Wireframes were created in [Balsamiq](https://balsamiq.com/)
