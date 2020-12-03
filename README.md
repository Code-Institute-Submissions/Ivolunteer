# IVolunteer #
_A non-profit organization devoted to rescue, protect, rehabilitate and release African elephants back into their natural habitats._
![IVolunteer](assets/images/Site%20image.png)

## Contents ##
---

## User Experience (UX) ##

 ### Project Goals ###
The aim of this project is to **raise awareness of Africa's endangered elephants** and **getting more people to get involved in helping to make a difference.** _Note this is a fictional site for educational purposes only._

### User Goals ###

* **Find information** about the endangered African elephants and the works of the organization.

* View organization **reviews, images and alternative social forums.**

* **Find information** on ways to contribute.

* Contact organization via **email**

### User Stories ###
* _"As a **user**, I want an informative website simple to navigate around"._

* _"As a **user**, I want to be able to get in touch regarding concerns and questions that I might have"._

* _"As a **user**, I want to learn how i can participate as **volunteer** or option to **donate**, and/or choose to do **both**"._

* _"As a **user**, I want to sign up to receive newsletters with updates about organization developments"._

### Site Owner Goals ###

* _"As a **site owner**, I want to provide a structured and effective website accessible to view on any device"._

* _"As a **site owner**, I want to increase awareness and participation"._

* _"As a **site owner**, I want to be able to **connect** with my users to **handle any queries** and obtain valuable **feedback**"._

#### Ivolunteer will achieve user/site owner requirements and expectations by: ####

* Providing an About Us page section where users will find all essential information about the organization and the work performed. Content is kept short and simple to not overwhelm user.

* Display of various images for visual support(appeal) & volunteer reviews to help potential users become more familiar with the organization.

* Providing easy navigation that helps direct user to specific parts of the website.

* Get involved page which provides the available ways to contribute with simple form fill options and progress bar to keep track on how the donation money is being used.

* Contact page where users can leave their contact information for further correspondence with organization.

* External links to associated social media accounts for users to connect with a larger community who shares similar interest.

* Providing an organized content layout and responsive web-site with mobile-first approach.

## Wireframe ##
I designed my website layout using [balsamiq wireframes](https://balsamiq.com/). Main criteria was to create a basic layout structure which also would display where content would be placed and what shape it would take on different screen sizes, such as desktop, tablet & mobile.

You can view my wireframes [here](https://github.com/yetnetbehailu/Ivolunteer/blob/master/assets/wireframe/wireframe.pdf) 

<details>
  <summary><strong>Wireframe updates:</strong></summary>
The completed site uses many of the concepts from the original Wireframe design however as this is my first project made on own there has been a few modifications made along the way. 

- Initial plan was to have a multi-page website design but then felt a single page scroll site would contribute to a simple linear navigation flow providing an intuitive user journey.

- Initially the hero image on the home landing page was not supposed to cover full height but would display a background-color and welcome text beneath. However after revising the look on mobile devices it appeared that the image would be fully covered when the nav bar collapses, therefore the decision made to make the image take full size of the screen.

- Due to visual preference and feedback received from my mentor, I also decided to change the design layout of the About page. Instead of having 4 text paragraphs surrounding 1 circle image, it now displays 1 top paragraph single row then 3 rows with text versus image and vice versa.

- Adding volunteer reviews came to me as an after-thought which i managed to add onto the image carousel on the gallery page.

- Border frame added to Get Involved forms creating a more organized structure and appeal.
</details>

## Design ##

- **Primary colors:**

  - Bright Orange #ffa500 not only because it's my favorite color but also as it is eye-catching, invokes a warm & happy feeling and to me depicts the vibrant continent of Africa. 

  - Ivory #e8dfc1 background to provide a light neutral setting contrast.

- **Non primary color:**
  - Dark grayish/black #212529 for text content 
 
- **Typography:**
  - "Bree Serif" used as primary font throughout the whole website with Sans Serif as fallback font in case for any reason the font isn't imported into the site correctly. I choose "Bree Serif" as i felt it had a suitable playful look and feel.

- **Images:** 
  - Eye-catching images showcasing the beautiful elephants in their natural habitats and at organization site.

## Features ##

**Existing Features**

- One page navigation with fixed navigation bar - easily directs to proper section of page (available on all screen sizes).

- Burger Icon as drop down navigation bar for smaller screen sizes.

 - Num stepper allowing users to increase or decrease number of guest participating (Get involved page)

 - Drop-down menus to list options (Get involved page)

- Volunteer application form with radio buttons for user to determine duration of stay and call for action button to submit (Get involved page)

- Donation form with radio buttons for user to asign donation amount and call for action button to submit (Get involved page)

- Progress bar measuring donation received (Get involved page)

- Contact form with radio buttons for user option to subscribe and call for action button to submit

- Footer with icon-links to social forums

**Features** to **implement** in the **future:**

- Search box -to quicker find specific information

- Adding functionality to submission forms where a server actually receives, registers and responds to submitted information.

- videos


---

## Testing ##

 
[Google Chrome Development](https://developers.google.com/web/tools/chrome-devtools)- Used tool consistantly to identify issues arising and to test changes made throughout site development to ensure desired appearance on different screen sizes.

[W3 CSS Validation Service](https://jigsaw.w3.org/css-validator/#validate_by_input) - Used to validate CSS; ❌ Parse error found due to missing curly brace, once corrected no errors found✅

[W3C Markup Validator](https://validator.w3.org/)- Used to validate HTML; No errors found✅  (Only a warning in regards to not having used a heading on first section page, however this warning was ignored as it was a design decision.)


- The website has been tested on a variety of devices such as Desktop, Laptop, tablet and mobile. Apart from testing on my own electronic devices got a little help from family and friends to help check responsiveness. "Am I Responsive" and Chrome dev tools was also great help for this. 

- Tested across multiple browsers; Safari, Chrome, & Firefox.

- Navbar menu links manually tested to ensure re-direction to right page when clicked. 

- Burger icon manually tested when clicked collapses on smaller devices. 

- Ivolunteer navbar logo re-directs to first page when clicked.

- Adjust width of browser window to confirm images are displayed attractively.

- Manually tested carousel arrows to make sure images swipe and display according to previous/next command when clicked.

- Ensure all text laid over on images can be easily read.

- Confirm that the overlay text on images do not display on smaller devices by adjusting the width of the browser window.

- Drop down menus & radio buttons manually tested, making sure only one of the options can get selected when clicked.

- Num stepp. tested clicking on up/down arrows, responds according to set number limits.

- Social media-link icons manually tested re-directs to social forum on a new tab when clicked.

- Try to submit contact form without having filled in the input fields to ensure that it can't be submitted empty (required fields must be met).

---
## Issues and Resolutions ##

**Errors encountered and resolved during development process**

- Display issue with the two seperate forms on the Get Involved page merging horizontally on smaller devices.

  - Issue resolved by changing the grid layout from multiple rows and cols to single row containing 2 cols with the separate form content.

- Following the above change the buttons would not align vertically as desired.

  - Issue resolved by placing the buttons outside the form content structure div.

- Difficulties trying to display the input forms on the contact page center while labels on top left side of form. 

  - Issue resolved by grouping the input form separate from the text label, then adding margin auto to input form styling whilst adding margin-left 20% to input form-label.

- Issue with the submit button on contact page not properly aligning center.

  - Issue affected by similar class name to previous buttons which added same styling to submit button. Resolved by changing class name.

- When checking the responsiveness noticed how the two depart forms on the Get Involved page was now instead merging vertically on smaller devices.

  - Issue resolved by adding media query (min-width: 0px) and structure div height 95%.

---
## Technologies Used ##

### Languages Used ###

- [HTML5](https://en.wikipedia.org/wiki/HTML5) - Used to create website content and structure.
- [CSS3](https://en.wikipedia.org/wiki/Cascading_Style_Sheets) - Used to style HTML5 content. 

### Frameworks & Tools ###
* [Bootstrap](https://getbootstrap.com/) -  Used to assist with the responsiveness and styling of the website.

* [FontAwesome](https://fontawesome.com/) - Used for social media links.

* [Google Fonts](https://fonts.google.com/) - Used for Typography.

* [balsamiq wireframes](https://balsamiq.com/) - Used to create wireframes

* [Am I Responsive](http://ami.responsivedesign.is/#)- Used to test webpage layout responsivedesign

* [jQuery](https://jquery.com/)- came with Bootstrap to make the navbar responsive.

* [Adobe Photoshop](https://photoshop.adobe.com/)- Photoshop was used to resize images and edit photos for the website.

* [Minify code](http://minifycode.com/html-beautifier/)- Used to beautify Html code 

* [online-spellcheck](https://www.online-spellcheck.com/)- Used to check spelling


### Workspace, version control, and repository storage ###

* [GitHub](https://github.com/) - A cloud based version control service that stores the repository and various changes made.

* [Gitpod](https://www.gitpod.io/) - IDE (Integrated Development Environment) used for writing code to develop website.

* [Git](https://git-scm.com/) - Version control system to track changes and store file versions.



---
## Deployment ##

To share the live website with others, I deployed my project on GitHub Pages using following steps:

1. Logged-in to my GitHub account.

2. Selects my repositories.

3. Click on my Ivolunteer repository 

4. On the top right navigation clicked on settings. 

5. Under the settings section of the GitHub repository, scroll down to the GitHub Pages section.

6. Selects Master Branch from the Source dropdown menu.

7. Once selected, this publishes the project to GitHub Pages and displays the site URL.

8. The code can be run locally through clone or download.

9. You can do this by opening the repository, clicking on the 'Code' button, and selecting either 'clone or download'.

10. The Clone option provides a URL, which you can use on your desktop IDE.

11. The Download ZIP option provides a link to download a ZIP file that can be unzipped on your local machine.
---
## Credits ##

### Code ###
  [Bootstrap](https://getbootstrap.com/): Used throughout the project to create a responsive site using the Bootstrap Grid System. Also referenced for following code;
   - The Navigation Bar
   - The Image Carousel
   - The Progress Bar

  [W3Schools](https://www.w3schools.com/): Referenced for the following code;
  - Num.stepp form
  - Radiobutton forms

  [Jsfiddle](https://jsfiddle.net/): Referenced for the following code;
  - Dropdown menues
### Content ###

The text content in the about page was sourced from other online elephant rescue sites such as [Wfft](https://www.wfft.org/about-wfft/), [Volunteerworld](https://www.volunteerworld.com/en/volunteer-abroad/elephant-conservation), [Elephantconservationcenter](https://www.elephantconservationcenter.com/releasing-elephants-into-the-wild-a-worlds-first/).

The volunteer reviews on the image carousel was sourced from [Podvolunteer.org](https://www.podvolunteer.org/elephant-care-thailand-reviews).


### Media ###
Website image content sourced from - [Pexels](https://www.pexels.com/sv-se/), [Pixabay](https://pixabay.com/sv/) & [Google](https://www.google.com/webhp?hl=sv&sa=X&ved=0ahUKEwjxxJrFhKbtAhVtxosKHfquBv0QPAgI)

### Acknowledgements ###

A special thanks to my mentor Seun Owonikoko for her time, patience and much helpful advice.

Big Thanks to classmates @JohnTrass & @Jimlynx for their guidance & honest feedback on my project.

The support from the Code Institute community on Slack.

Tutor support for their invaluable feedback and problem solving.

My family and friends for their support & encouragement.