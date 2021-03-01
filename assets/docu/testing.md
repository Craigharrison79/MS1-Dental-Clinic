# **Testing Dental-Clinic**

Here is the stories of testing history....

# In the development process, the issues and solution that came up.

## Navigation issues

- **Issue:** Toggle button is not opening when click on.

    > **Solution:** I must of accidentally deleted part of the code when copying it for [Bootstrap](https://getbootstrap.com/docs/5.0/components/navbar/).
    I just read through and debug the code.

    ![sample-code-toggle-buttom](testing-code/toggle-btn.png)


- **Issue:** Toggle button moving over to the left side on smaller screen size.

     > **Solution:** To change you branding size on different screen sizes.

     ![sample-branding-name](testing-code/branding-name.png)

## Landing Page

- **Issue:** Brand and massage covering the hero image face, which was making it harder to see the text.

     > **Solution:** To build a jumbotron to help which helped improve readability.

     ![sample-welcome-msg](testing-code/welcome-msg.png)


## About Page

- **Issue:** Having issues with getting the two cards to align/float next to each other.  

     > **Solution:** I started by trying different things with the code like flexbox, grids 
     till I know noticed I had added an extra row in the code.

     ![sample-added-row](testing-code/added-row.png)


- **Issue:** Lining issues with profile photo and H3 Name.  As the screen change size the photos start to cover up the H3. 

     > **Solution:** To write some media quoted to move the photo to the center, top of the card.

     ![sample-profile-photo](testing-code/profile-photo.png)
     ![sample-profile-photo2](testing-code/profile-photo2.png)


## New Patient (model)

- **Issue:** Align issues with check marks on second model "If uncheck please enter the last time you visit the dentist?".

     > **Solution:** Had to add a little padding in CSS.

     ![sample-model-check](testing-code/model-check.png)


## Footer social media links

- **Issue:** Social media links - on safari the icons drop out of alignment with hover over.  

     > **Solution:** This is something I try to fix by myself and serching on the internet. I added some webkits 
     [Stack Overflow](https://stackoverflow.com/questions/21767037/css-transitions-not-working-in-safari) but this didn't help. 
     It was code I found on youtube [CodingNepal](https://www.codingnepalweb.com/2020/07/awesome-social-media-buttons-with-hover-animation.html). 
     I talk to my mentor and he saying it was to do with compatibility with safari.

     ![sample-webkit](testing-code/webkit.png)

     This is something I will need to come up to and fix.  Thinking I could possible do it will Javascript.

     ![sample-can-I-use](testing-code/can-I-use.png)


## Padding on Anctor

- **Issue:** Page was not lining up with each section when using the navbar controls.  

     > **Solution:** Was to add padding to each section with the use of [Bootstrap](https://getbootstrap.com/docs/5.0/utilities/spacing/#notation)
     and CSS to fix the problem.

     e.g.

     ![sample-padding](testing-code/padding.png)


## i-frame

- **Issue:** Was slowing down the web loading time and also need to change the code in HTML (3rd party) to CSS

     > **Solution:** Remove the unwanted code and create a CSS class.

     ![sample-css](testing-code/)


# Testing on devices

Testing was done on different elements to see how the site preform and the responsiveness of the site.

Browsers:

- Chrome, Firefox and Safari.

Devices:

- Mac (Macbook), Ipad and Iphone 11 and using developer tools in Chrome: (Moto G4, Galaxy S5, Pixel 2, iPad Pro,
Surface Duo).

### Responsive on devices.

With the responsive being veiw through different device and different screen sizes. Change had to be made.

- **Issue:**
> - toggle button.
> - call button on Navbar.
> - navbar brand name, font-size change.
> - changing from three cards to two cards on the service section (iPad).
> - profile photo in the about section.
> - about section heading 1, font-size change.
> - social media links in footer section.
> - jumbotron on landing page.
> - some padding and margin changed to help with alignment and look on smaller screen.


# Accesibility

Wave Report showed the following issues:

![sample-wave](testing-code/wave.png)

Click here to [view](testing-code/wave.jpg)


# Google lighthouse

Lighthouse report showed the folloing issues:

![sample-lighthouse](testing-code/lighthouse1.png)

### To improve the rating scores

#### Performance

- 


# HTML & CSS Validation

Using W3C CSS validation service I paste the URL and 18 errors and lot of warnings.
When looking at the code all errors and warnings are from bootstrap issues.

![sample-w3c](testing-code/w3c-css-1.png)

I them paste the whole of my CSS code from the project and end up with no errors and 1 warnings.

![sample-w3c](testing-code/w3c-css-2.png)

The one warnings is about transition kits uses to help fix the social media links in the footer.

![sample-warnings](testing-code/w3c-css-warnings.png)