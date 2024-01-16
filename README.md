# Eden Essame Wakeboarding website

## Code Institute - First Milestone Project: User Centric Frontend Development.

This website was developed to showcase my ability to design and create a static website, using HTML and CSS.

It is a website about a fictional wakeboard park in the town in which I live in. Users of the website will be able to find all the information they need to know about the wakeboard park, services offered, prices, location and contact information. The site is targeted towards towards any potential customers who may be interested in wakeboarding.

![Website appearance on different devices](./readme-assets/wakeboard-website-screensizes.png)

## Features

### Navigation Section

* The Navigation bar is at the top of the page and fixed, so always visible and accessable wherever the user is on the page.
* The Navigation bar shows the business name in the top left corner.
* The other navigation links are to the right: Home, About Us, Prices and contact. They become a drop down menu on smaller screens where they would take up too much screen space.
* The Navigation bar tells the user the name of the business and website and the differnt sections of information are easy to find

![Navigation bar on a large screen](./readme-assets/Navigation-bar.png)

![Navigation bar on a small screen](./readme-assets/Navigation-bar-mobile.png)

### Home Section

The website opens on a picture of a wakeboarder at the park.

![Website opening image of a wakeboarder](./readme-assets/Wakeboarder-image-readme.png)

### About Us Section

* The About Us section tells users about the business and who its for.
* The About Us section lets users know what services are available.
* The About Us section lets users know that beginners and experienced riders are catered for.
* The About Us section lets people know lessons are available.

![About Us section](./readme-assets/About-us.png)

### Prices Section

* The Prices section lets users know the session prices and that there are different prices for adults and under 16's.
* The prices section lets users know how much equipment rental is, but that they can use their own.
* The Prices section lets users know how long a session lasts for.

![Prices section](./readme-assets/Prices.png)

### Contact Section 

#### Form

* The Contact section has a form that collects users name, email address and lets them ask question.
* The Contact form is useful to users as it lets them ask any questions they might have.

![Contact section form](./readme-assets/Contact-form.png)

#### Opening times and Location

* The Contact section also has the opening times, so users know when they can visit.
* The Contact section also has the address and postcode, so users know where the park is located.

![Opening times and location](./readme-assets/Opening-times-and-location.png)

### Footer

* This section includes the social media links which users can use to visit the Facebook, Instagram and twitter pages of the business.

![image of the footer](./readme-assets/Footer.png) 

## Testing

* I tested the site and it works in different browsers: Chrome, Firefox and Microsoft Edge.
* I confirmed that the site is responsive and functions on different screen sizes using devtools device toolbar.
* I confirmed that the navigation, logo, about us, prices and contact text are all readable and easy to understand
* I confirmed that the form works: it requires entries in every field, only accepts an email in the email field and the submit button works.

### Validator testing

* **HTML** 
 * The W3C validator found that in my form I hadn't added a corresponding "id" attribute to my first-name input element `<input type="text" name="first-name" required>` to link it to the "for" attribute of its corresponding label element `<label for="first-name">First Name</label>`. So I corrected that `<input type="text" name="first-name" id="first-name" class="text-input" required>`. 

 * The W3C validator also found that i had used a bad value: `role="img"` on my "aria-label" attribute. So I removed it.

 * Now no errors were returned when passing through the official [W3C Validator](./readme-assets/HTML-validator.png)

* **CSS**
 * No errors were found when passing through the official [(jigsaw) Validator](./readme-assets/CSS-validator.png) 



