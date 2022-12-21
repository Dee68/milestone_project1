# Lamad
The Lamad website is a tailoring website that is the dream of a group of Ukrainian ladies that are aspiring to show off their talents by rendering tailoring services in Cahersiveen. Lamad offers services not only to people in cahersiveen but also to nearby towns such as Balle Skellig, Port Magee and its environs.


Users of this website will be able to find all the information they need to know about Lamad:Buisness hours, services and contact information.This site is targeted towards anyone that is in need of a unique dress or needs dress to be altered also for those who are looking for innovation in the tailoring buisness.

![lamad responsive image](readme_images/lamad-responsive-white.webp)


## Features
#

- Featured at the top of the page,the navigation shows the logo image with the name Lamad at the left upper corner which links to the home page.
- The other navigation links are to the right: Home, About, Services and Contact which links to different corresponding pages.
- The navigation is in a font and color that contrasts the background.
- The navigation clearly tells the user the name of the tailoring website and makes the information of different pages easy to find.

## Technologies Used
# 
### Languages used
- [HTML](https://en.wikipedia.org/wiki/HTML5)
- [CSS3](https://en.wikipedia.org/wiki/CSS)

### Frameworks, Libraries & Programs Used
- [Google Fonts](https://developers.google.com/fonts)
  - Google fonts were used to import the 'Lato' and 'Oswald' font into the style.css file which is used on all pages throughout the project.
- [FontAwesome](https://fontawesome.com/)
  - Font Awesome was used on some pages of the website to add icons for aesthetic and UX purposes.
- [Git](https://git-scm.com/)
  - Git was used for version control by utilizing the Gitpod terminal to commit to Git and Push to GitHub.
- [GitHub](https://github.com/)
  - GitHub is used to store the projects code after being pushed from Git.


#

## Testing
- I tested that the home page works in different browsers : Chrome, Firefox and Safari
- I confirmed that the navigation, header, about, services and contact pages all have readable texts and are easy to understand.
- I have confirmed that these forms work correctly validating all input elements and the submit button works.
![contact page](readme_images/contact.png)
![newsletter](readme_images/newsletter.png)
### Bugs
#### Solved bugs
- When I tested my web pages with lighthouse I discovered that the upload time of the pages was very slow.
- I discovered that this was due to the size of the images.
- Reducing the size and converting the images to a more modern web format(.webp) fixed the problem.
- In my contact page I embedded google map but had issues with setting the width of the obsolete iframe.
```
<iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d2459.2640832509846!2d-10.228465123398758!3d51.947375571916716!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x484ff31ceb50d033%3A0xbf4459f40fc381a4!2sSkellig%20Accommodation%20Centre!5e0!3m2!1sen!2sie!4v1670701740436!5m2!1sen!2sie" title="Lamad tailors Cahersiveen" allowfullscreen width="100%" height="700" ></iframe>
```
- Adding a parent div to the iframe and enabling the iframe to get its width and height from the parent solved the problem.

### Validator Testing
- HTML
  - No errors were returned when passing through the official [W3C validator](https://validator.w3.org)
  ![index page](readme_images/w3c-html.png)
  ![about page](readme_images/W3C-about.png)
  ![services page](readme_images/W3C-service.png)
  ![contact page](readme_images/W3C-contact.png)
- CSS
  - No errors were returned when passing through the official [CSS Valdation Service](https://jigsaw.w3.org/css-validator/)
  ![stylesheet](readme_images/W3C-css.png)


## Google Developer Tools
- I made use of the built-in **Chrome Dev Tools** to experiment and debug while coding, in addition to testing simulated responsive behaviour across a wide range of mobile and desktop devices, and finally checking all pages Performance using **Lighthouse**.
![Lamad performance](readme_images/performance-sucks.png)
- I spent too much time trying to improve the performance of my pages, eventually changed all the images to .webp format.
![Lamad better performance](readme_images/lamad-performance.jpeg)


- Accessibility
  - I confirmed that the colors and fonts chosen are easy to read accessible by running through lighthouse in devtools.


### Unfixed Bugs
No unfixed bugs

# Deployment
- The site was deployed to Github pages. The steps to deploy are as follows: 
  - In the Github pages, navigate to the settings tab
  - From the source section drop-down select the Main Branch
  - Once the main branch has been selected it provides link to the website.



  The live link can be found here [Lamad](https://dee68.github.io/milestone_project1/)

# Credits
## Content
- All content was written by the developer.
- The code to make an accordion was adapted from [W3schools Accordion](https://www.w3schools.com/howto/howto_js_accordion.asp)
- The code to make the footer was taken from the CI [Love Running](https://dee68.github.io/love-running/) project.
- All icons on the pages where taken from [FontAwesome](https://fontawesome.com)

## Media
- The logo in the header was made from [Free Logo Maker](https://logo.com/)
- All images on the web pages are taken from [Pexels](https://www.pexels.com/ru-ru/)

## Acknowledgments
  - My mentor for his extraordinary insight and continuos useful feedback.
  - My collegues here with me for their useful advices.
  - Code Institute for enabling me to better understand css.




