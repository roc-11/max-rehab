# Max Rehab Physiotherapy - Testing 

[Main README.md file](/README.md)

[View live project](https://roc-11.github.io/max-rehab/)

[View GitHub repository](https://github.com/roc-11/max-rehab)

***
## Table of contents
- [Max Rehab Physiotherapy - Testing](#max-rehab-physiotherapy---testing)
  - [Table of contents](#table-of-contents)
  - [Browser Compatibility](#browser-compatibility)
  - [User Testing](#user-testing)
  - [Testing User Stories](#testing-user-stories)
    - [Current User](#current-user)
    - [New User](#new-user)
  - [Manual Testing](#manual-testing)
  - [Validator Testing](#validator-testing)
    - [HTML Validation](#html-validation)
    - [CSS Validation](#css-validation)
  - [Performance](#performance)
  - [Accessibility](#accessibility)

***

## Browser Compatibility

The website has been tested on a range of browers: Google Chrome, Safari & Microsoft Edge. The results were satisfactory.

## User Testing

The entired project was manually tested by the developer to ensure all it appears correctly on a range of devices/screen size, and to ensure that all links work as expected.

The project was manually tested and reviewed by my mentor Koko during three separate mentor sessions. Her expert opinion was greatly appreciated and small changes were made to the site after each session.

The project was also user tested by a some class colleagues on the [Slack](https://slack.com/intl/en-ie/) Code Institute community, and some of my family members. Their helpful advice and suggestions led to a few small UX changes in order to create a better experience.

## Testing User Stories

### Current User 

1. As a current user, I want to be able to contact/book a physiotherapy session easily.
   - The Home Page has a "Book Now" button under the main hero image. Users can simply click this to take them to the contact us form and make a booking. If the site were real, an integrated booking system would also exist.
   - The user can click on the "Contact Us" link in the main navigation bar to take them to the contact us/booking form.
   - The user can find contact details in the form of an email address & phone number in the main footer. Both of these are clickable and perform actions.
 
2. As a current user, I want to easily navigate through the site and access the information I require.
   - The navigation bar is clearly defined and easily navigable for users to find and use.
   - The footer menu is easy to use with appropriate icons for easy identification.

3. As a current user, I want to easily navigate to content I have previously viewed within a small number of steps.
   - On all site pages there is a naviagtion bar with links to each required page.

### New User 

1. As a new user, I want to easily navigate the entire site intuitively. 
   - The navigation bar is clearly defined and easily navigable for users to find and use.
   - The footer menu is easy to use with appropriate icons for easy identification.
  
2. As a new user, I want to easily understand the main purpose of the site.
  - The main purpose of the site is clear on the home page (hero image of physio, site slogan).
  - The "how can we help you" section on the homepage clearly defines the services offered to clients.

3. As a new user, I want the information I seek to be easily accessible and relevant.
  - The navigation bar is clearly defined and easily navigable for users to find and use.
  - The footer menu is easy to use with appropriate icons for easy identification.
  
4. As a new user, I want attractive and relevant visuals and colour schemes that work with the content.
   - An attractive colour palette was created inpsired by the theme 'Close to Nature' on [Visme.com](https://visme.co/blog/website-color-schemes/).
   - Relavant images were found using [Pexels](https://www.pexels.com/ "Link to Pexels.com"), [Pixabay](https://pixabay.com/ "Link to Pixabay.com") and [Adobe Stock](https://stock.adobe.com "Link to Adobe Stock").
   - An attractive, professional logo image was created using [Looka.com](https://looka.com/onboarding "Link to Looka Home Page").

5. As a new user, I want to be able to contact/book a physiotherapy session easily.
- 

## Manual Testing

## Validator Testing

### HTML Validation

All pages of the website were tested using the [W3C official HTML validation tool](https://validator.w3.org/). No errors were shown when the site was passed through this tool.

A previous pass through this tool showed multiple errors related to 'trailing slash on void elements'. An autoformat option has to be changed on the CodeAnywhere IDE in order to rectify these.

![Screenshot of W3C HTML Validation - Home Page](assets/readme-files/html-validation.png)
![Screenshot of W3C HTML Validation - About Us Page](assets/readme-files/html-validation-about.png)
![Screenshot of W3C HTML Validation - Our Services Page](assets/readme-files/html-validation-services.png)
![Screenshot of W3C HTML Validation - Contact Us Page](assets/readme-files/html-validation-contact.png)

### CSS Validation

The Cascading Stylesheet code was tested using the [W3C CSS Validator](https://jigsaw.w3.org/css-validator/). No errors were found when the CSS was passed through this tool.
![Screenshot of W3C CSS Validation](assets/readme-files/css-validation.png)

## Performance

[Lighthouse](https://www.webpagetest.org/lighthouse) Google Webdev tools were used to test the performance of the website.
![Screenshot of Lighthouse Peformance Testing](assets/readme-files/max-rehab-performance-testing.png)

## Accessibility

[Wave](https://wave.webaim.org/) Web Accessibility Evaluation tool was used to check accessibility. It detected a minor alert where table is used for the opening times in the footer. The contrast check passed, as did all other accessibility checks.

Semantic markup was used when developing the site to ensure the site is readable for the visually impaired/those using screen readers and other forms of assistive technology. Alt text descriptions are included for all images and aria-labels for all links.

![Screenshot of Wave Accessibility Testing](assets/readme-files/wave-accessibility-testing.png)
