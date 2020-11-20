# Wagged Out Walkies
## Dog Walking Site 

[View website in Github Pages](https://github.com/svickery/waggedoutwalkies)

![alt text](https://github.com/svickery/waggedoutwalkies/blob/master/assets/img/screenshotwagged.jpg "Website Screenshot")

A comprehensive website for a dog walking company based in Warwickshire, Midlands in the UK. The website includes a parallax effect scroll to show pictures of dogs. There is a home page with contact details on, a services & pricing section, a review section and a contact form section. The purpose of the website is to advertise services offered and to get the user to contact the company that owns the website. In turn this hopefully converts the user of the site to a user of the service. 

For a dog walking site, the user of the site has to feel comfort and assurance. When employing somebody to look after your dog, you want to know you can trus them and allow them into your home when you are not there. This is why the parralax effect was used, to create some warmth in seeing pictures of dogs and also the reason that reviews were such an important part of the site. The website addresses not only the 'feel' that a customer needs to have but also the business side of things also. There are clear and concise services offered and the pricing structure is simple and easy to see. 

The business goals of the website are as follows:
 
* Build trust of the website user and potential client
* Provide examples of clients 
* To show a potential client the services offered
* High quality UX to keep the client on the site
* Ensure the layout is simple and not take up unnecessary space

The customer goals of the website are as follows:

* To feel they can trust the service provider
* To have clear pricing
* To ensure contact is easy with service provider
* Feel that their needs are being met by the service provider

## UX

#### Ideal Client for the business:

* Owns a dog
* Lives in the Warwickshire area
* Works during the day
* Goes on business trips regularly 
* Has disposable income

#### Visitors to the site will be looking for:

* A dog walker for their dog
* Someone to dog sit while away
* A reliable service provider
* Local service provider

#### This website is best to help them because:

* Other dog walking websites are visually unappealing and have poor UX
* Other dog walking websites have too much information and it can be an overload
* This Website is:
   - Easy to navigate
   - Simple and efficient with information
   - All leads to contacting the service provider
   - Professionally designed and looks trusthworthy
   
#### User Stories

1. As a new visitor to the site, I want to be able to navigate the site easily
2. As a new visitor to the site, I want to see what the business offers immediately
3. As a new visitor to the site, I want to see a clean, professional and trustworthy service being offered
4. As a potential client, I want to know the services offered in a concise and precise presentation
5. As a potential client, I want to see previous client's opinions of the service provider
6. As an interested client, I want to know the pricing and what I get for this price
7. As an interested client, I want to be able to contact the service provider in the way I feel is best for me
8. As an interested client, I want to be able access the service providers social media, so I can keep up with relevant news
9. As a returning client I want to be able to access the contact details easily 


#### Wireframes

[View Wireframes here](https://www.figma.com/file/VcE19zWTDz8YgJAg8wT44P/Wagged-Out?node-id=28%3A18)


## Features

The entire website is one scrolling parallax effect. Therefore there are no need for separate pages. This means that to use the site more efficiently the navigation bar the top of the page was made sticky. This means that wherever you scroll or click on the page, then the navigation bar moves with it and stays at the top. In the scrolling page, their is a hero image on the front page, and images between each other page, which are at a height of 70%, so there is less scrolling time of the site visitor. There are four sections to the page in total. A home page, services page, reviews page and a contact page. There is also a footer, where the social link icons are and copyright information. 

#### Home

The Home page features one large photography covering the entire page. The photo has a callout wrapper over the top of this with a sentence about the services offered and two forms of contact in phone number and email. The name of the company also appears as a header and there is no logo used for the site. 

#### Services and Pricing

The Services and Prices page had 3 cards from bootstrap as it's layout. In these cards it contains the options available to the client: *Dog Walking*, *Puppy Care* and *Dog Sitting*. In each section there is a short description of the service available and then different pricing options below. The navigation bar stays at the top. There is also a paragraph beneath the title of Services and Prices stating that the services are only available in Warwickshire at this time. This is a simple layout with no pictures, so only the information comes through. 


#### Reviews

There is a photograph from the parallax design before the reviews section if using the scrolling effect of the page. With the navigaton bar once again always at the top. Underneath the title there is another card layout design from bootstrap. It gives each review its number, then the quote, the name of the client and what service the client uses from the company. This is a simple layout with no pictures, so only the information comes through. 

#### Contact Us

Once again there is a picture between Reviews section and Contact Us section using the parallax effect. The navigation is again at the top as always. This is just a simple form with a call to action button at the bottom to allow a potential client to send through their query to the service provider. There is a name, email and message section for the form. 

#### Footer

In the footer is copyright information and links to the social media sites. 

#### Possible Future Features

* GDPR compliant pop up screen. 
* A FAQ's section
* Blog from the service provider

## Technologies Used

* The project uses HTML and CSS languages. 
* [Github](https://github.com/) - I used this for all coding (IDE) while building the website.
* [Bootstrap](https://getbootstrap.com/docs/4.5/getting-started/introduction/) - Used for grid layouts and cards on my page. Also allowed me to use Font Awesome icons for my social media links. 
* [Font Awesome](https://fontawesome.com/) - Used for social link icons in conjuction with bootstrap. 
* [Google Fonts](https://fonts.google.com/) - Used for entire website fonts.
* [Stack Overflow](https://stackoverflow.com/) - Used for the JavaScript necessary to get my stick navigation bar to work. 
* [Web Formatter](https://webformatter.com/) - Used to make my code cleaner and easier to read.
* [W3Schools](https://www.w3schools.com/) - Used to help with contact form and other various coding questions.
* [JSfiddle](http://jsfiddle.net/QN9cH/1/) - This was to help with parallax scrolling effect on iOS mobile devices. 

## Testing

To test the website, the project code was run through both a Markup checker and a CSS checker, below are the links to the sites and the results. 

[Markup Validator](https://validator.w3.org/#validate_by_input) [Results](https://validator.w3.org/nu/#textarea)

As can be seen in the Markup Validator, there were 5 warnings and 4 errors. The warnings are just for the comments and these are necessary for guidance for whoever is reading the HTML. The errors are only there because this is a Bootstrap navigation bar and after speaking with some colleagues, this can be a common error for validators. They do not seem to recognise Bootstrap code correctly.

[CSS Validator](https://jigsaw.w3.org/css-validator/#validate_by_input) [Results](https://jigsaw.w3.org/css-validator/validator)

There are no errors in the CSS Validator.

#### Testing User Stories

 * ##### New Visitor Goals
   
    i. *As a new visitor to the site, I want to be able to navigate the site easily*
    
     a. As soon as the website is clicked there is a navigation bar at the top of the page.
     b. Scrolling down the page, navigation is still easy as the navigation bar stays at the top of the page.
     c. The site uses a parallax effect and therefore navigation is always smooth. There is no need to keep going back and forth through pages, all information is       on one scrolling page. 
  
    ii. *As a new visitor to the site, I want to see what the business offers immediately*
  
     a. The home page has contact details in a callout wrapper on the top right. 
     b. Navigation link to contact us form.
    
    iii. *As a new visitor to the site, I want to see a clean, professional and trustworthy service being offered*
   
     a. Site is differently built to many other dog sites. Scrolling effect takes away any clunky page loading. 
     b. Site not filled with dog paw icons etc, a lot more professional.
     c. Reviews are marked in the navigation bar for the visitor to use immediately.
    
 * ##### Potential Client Goals
 
    i. *As a potential client, I want to know the services offered in a concise and precise presentation*
    
     a. Navigation shows "Services" page immediately after the home page, and same with scrolling effect. 
     b. Service cards have to the point information and pricing is actioned underneath. No confusion for the visitor.
    
    ii. *As a potential client, I want to see previous client's opinions of the service provider*
    
     a. Navigation bar shows "Reviews" section
     b. "Reviews" section has a short quote, clients name and which service they use. There is a quote for each service. 
 
 * ##### Interested Client Goals
 
    i. *As an interested client, I want to know the pricing and what I get for this price* 
    
     a. Pricing is shown in the "Services and Prices" section after the home page. 
     b. Pricing is shown after concise description of service offered.
     c. There is more than one pricing option for each service offered. 
    
    ii. *As an interested client, I want to be able to contact the service provider in the way I feel is best for me*
    
     a. Contact options are Phone and Email on the home page and Contact Us form in the "Contact" section. 
    
    iii. *As an interested client, I want to be able access the service providers social media, so I can keep up with relevant news*
    
     a. Social media icons are located at the bottom of the page in the footer. 
     b. All Social Media icons are clickable and take you straight the the business social media page. 
 
 * ##### Returning Customer Goals
 
    i. *As a returning client I want to be able to access the contact details easily*
     
     a. There won't be much call for returning customer, as once converted to customer, they will be in contact however they best choose. 
     b. If they do return however, all options of Phone, Email and Contact Form are available. 
     

#### Further Testing

 * Testing was completed on desktop browsers Google Chrome, Safari and Microsoft Edge.
 * Testing was completed on numerous devices iPhone X, iPhone 12, iPad, Google Pixel, Laptop and Desktop.
 * All testing went well until iOS mobile devices. The parallax images were 'Zoomed in' and made the site look awful. Issue was rectified with CSS code. 

#### Known Bugs

 * Only one known bug. The mobile number on the home screen is active on iOS mobile devices. 

## Deployment

This site is hosted by GitHub pages and deployed directly from the master branch. The site updates automatically from updates that are new commits from the master branch. For the site to deploy on GitHub pages the landing page must be correctly named 'index.html'.

I deployed the site by following the next steps:

1. Logged into GitHub and located the correct repository
2. Went into Settings at the top of my Wagged Out Walkies repository
3. Located GitHub "Pages" in settings
4. Selected "Master Branch" from the "Source" dropdown
5. Page automatically refreshed, I scrolled back to "Pages" section to find the newly published site

To make a clone of this site, please follow these steps:

1. Log in to GitHub and find the repository required
2. Click "Clone or download"
3. Use the "Clone with HTTPS" option and copy the link
4. Open Git Bash
5. Edit the working directory to a location you want it to be cloned in
6. Type `git clone` and paste the url you copied previously which should look as follows:

`https://github.com/YOUR-USERNAME/YOUR-REPOSITORY` 

7. Press enter and the repository should be cloned


## Credits

#### Content

All text and content on the page was written by myself

#### Media

All images used on this page were taken from [pexels.com](https://www.pexels.com/).

#### Code

Code for the navigation bar, service cards and review cards were taken from [Bootstrap](https://getbootstrap.com/docs/4.5/getting-started/introduction/).

My Contact form was a putting together of code from [Bootstrap](https://getbootstrap.com/docs/4.5/getting-started/introduction/) and [W3Schools](https://www.w3schools.com/). However it was written by myself. 


## Acknowledgments

Inspiration from this came from my dog! 
A big thank you has to go to Jim Lynx, the channel lead on slack for the user centric frontend group. He spent way more time helping me on this project than he needed to. Without him, I would have missed my deadline.
