# IVolunteer #
_A non-profit organization devoted to rescue, protect, rehabilitate and release African elephants back into their natural habitats._

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

## Design ##

- **Primary colors:**

  - Bright Orange #ffa500 not only because it's my favorite color but also as it is eye-catching, invokes a warm & happy feeling and to me depicts the vibrant continent of Africa. 

  - Ivory #e8dfc1 background to provide a light neutral setting contrast.

- **Non primary color:**
  - Dark grayish/black #212529 for text content 
 
- **Typography:**
  - "Bree Serif" used as primary font throughout the whole website with Sans Serif as fallback font in case for any reason the font isn't imported into the site correctly. I choose "Bree Serif" as i felt it had a suitable playful look and feel.

- **Images:** 
  - Showcasing the beautiful elephants in their natural habitats and at organization site.

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

---
## Issues and Resolutions ##

**Errors encountered and resolved during development process**

- Display issue with the two depart forms on the Get Involved page merging horizontally on smaller devices.

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
- [JavaScript](https://en.wikipedia.org/wiki/JavaScript)-

### Frameworks & Tools ###
* [Bootstrap](https://getbootstrap.com/) -  Used to assist with the responsiveness and styling of the website.

* [FontAwesome](https://fontawesome.com/) - Used for social media links.

* [Google Fonts](https://fonts.google.com/) - Used for Typography.

* [balsamiq wireframes](https://balsamiq.com/) - Used to create wireframes

### Workspace, version control, and repository storage ###

* [GitHub](https://github.com/) - A cloud based version control service that stores the repository and various changes made.

* [Gitpod](https://www.gitpod.io/) - IDE (Integrated Development Environment) used for writing code to develop website.

* [Git](https://git-scm.com/) - Version control system to track changes and store file versions.



---
## Deployment ##
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
Website image content sourced from - [Pexels](https://www.pexels.com/sv-se/) & [Pixabay](https://pixabay.com/sv/)

### Acknowledgements ###