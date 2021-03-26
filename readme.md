# Belltini

![Logo with belltini page](assets/images/images-readme/readmeheader.jpeg "belltini header")
[View the page on github here](jdygard.github.io/belltini "Belltini Homepage")

# Table of Contents

1.[Introduction](#Introduction)  
2.[UX](#ux)  
3.[User stories](#user-stories)  
4.[Planes of UXD](#planes-of-uxd)  
5.[Strategy](#strategy)  
6.[Scope](#scope)  
7.[Structure](#structure)  
8.[Skeleton](#skeleton)  
9.[Surface](#surface)  
10.[Current Features](#Current-Features)  
11.[Nav Bar](#nav-bar)  
12.[Footer](#footer)  

## Introduction 

This streamlined website is built for Belltini Pastas, an Indianapolis, Indiana based business selling bespoke fresh formed and stuffed pastas. The primary focus of this site is as a portal to sell pasta, but will also serve to expand knowledge and web-presence of the Belltini brand.
Belltini currently sells pastas intermittently to local restaurants and a limited set of local private consumers. With this site, the purpose is to expand the pool of customers and provide a professional face for the brand.
Additionally, this is built as the first of four "Milestone Projects," building the developer's portfolio and as a demonstration of the developer's understanding of HTML5 and CSS components.

[Back to Top](#belltini)
***
## UX
### Users:
1. Current commercial customers
2. New commercial customers
3. Current private consumers
4. New private customers

[Back to Top](#belltini)

***

## User Stories
### Current commercial customers
1. As a current commercial customer, I want to find pictures and information about new products, or review and purchase current products not yet on my restaurant menu.
2. As a potential new commercial customer, I want to see the commitment to quality and easily find information about products and expanding my own inventory.
### Personal visitors
3. As a current private consumer, I am interested in finding products I haven't yet tried or preview new products.
4. As a new private customer, I want to see why I should choose to buy fresh, handmade pasta for a premium price rather than machine-made from the grocery store. I want to see product images or learn about fresh pasta in general.

[Back to Top](#belltini)
***
## Planes of UXD
### Strategy
#### Who is this website for, and what does it do?
1. Audience
    1. New and current commercial customers, new and current private customers
    2. Fresh, handmade pasta has a short shelf-life, and a high cost per portion. This means that it is less practical and more expensive.
        Private consumers will likely either be young (20-29 years old) and sporadic, or 30+ years old. The target audience is thus older and accustomed to professionalism and clean, modern UI.
        Commercial customers will be high-end restauranteurs with expectations of clean, modern UI with concise information about the products.
2. Functional requirements
    1. Easy access to information, like new products, flavors, styles and biography.
    2. Ability to order the product.
    3. Ability to contact the business.
3. Benefit to Belltini
    1. The website should present a professional public face.
    2. The website should provide access to the product.
    3. The website should attract new customers.

![alt text](assets/images/images-readme/readmestrategy.jpg "Logo Title Text 1")

### Importance/Feasability curves (graphic above)
1. Increase web presence: Developer gives this a 4/4. Having a web presence is important but not the central goal of the business. Through search engine optimization and accessible design, this goal is very achievable for the the developer.
2. Attract new customers: Developer gives this a 5/3. The core goal of the business is to sell pasta, and the website should serve this goal as centrally as possible. However, the site is only part of the business strategy for the attraction of customers. The owner will be distributing business cards, courting businesses and relying on some amount of "word of mouth" business. The site and developer will serve this goal by providing an accessible website that advertises the product and business as attractively as possible.
3. Include general information: Developer gives this a 3/5. This serves the site's goal of attracting new customers by teaching them the benefits of the product and familiarizing them with the business and owner themselves. Though it isn't crucial to the site's goals, it is "low-hanging-fruit."
4. Direct sales on-site: Developer gives this a 4/1. The developer has little skill in JS and Python and thus no ability to provide this service. The live version of the site passed on to the actual business owner has a page with simple contact information and instructions. The version of the site submitted for grading at Code Institute (and the version available on github) has a mockup of what the order form might look like.
***
### Scope
#### What's on the table in terms of features?
1. User is able to purchase the product.
2. User is able to learn about the product.
    i. Through highlighting the benefits of fresh pasta in general and Belltini in particular.
    ii. Video and images that intrigue and tempt the user to purchase.
3. User is able to learn about the business and the chef.
### Structure
#### How is the information structured and grouped?
1. A splash home page with small bits of easily-digestible information and direct links to the order page.
2. Multiple pages with deeper dives into each avenue of information
    i. A "Learn More" page with a video of fresh pasta being made by a master chef.
    ii. A gallery page featuring pastas made by Belltini
    iii. A biographical page with information about the chef.
3. An explicit and structured page with an order form.
### Skeleton
#### How do we represent this information? How does the user find it?
1. The home page features snippets of information with links to learn more at each step.
2. The nav bar is clear and explicit about the information to be found on each page.
### Surface
#### What does it look like?
1. Customers of this page will expect a clean, light, modern design with clear, simple features arranged intuitively. 
    1. In working directly with the owner of Belltini, a color scheme of off-white colors and backgrounds featuring the products was    used.
    2. Font: Montserrat was chosen for most informational features for its clean, modern look. Roboto was used for buttons, forms and hero image boxes because of its high visibility while retaining some modern tone.

[Back to Top](#belltini)
***
## Current Features
### Nav bar
A navbar that appears on each page. On smaller screens, the nav elements condense to an accordion menu. The nav bar sticks to the top of the screen when scrolling.

### Footer
Footer contains a link to a restaurant that features Belltini pastas and a link to the chef's instagram. It appears on every page.

### Splash page
1. A hero image with a centrally featured call to action.
2. A "Why Fresh Pasta?" section highlighting the benefits of fresh pasta over dry, with images that clarify each point.
3. A "Why Belltini?" section that briefly says why you should pick Belltini pasta. The background image is from Pexel. The image chosen elicits the idea of handcrafted pasta. There is also another call to action here.
    
### Learn More Page
Features a video of fresh pasta being made by a professional.

### Selection Page
A gallery page featuring some of the products made by Belltini. Lightbox2 was used, with custom alignment and responsiveness.
    
### About Page
A simple biography page with a picture of the chef and a couple of blurbs about her background in food.

### Order Page
A hero image with a semi-transparent box containing the order form. Order form contains the only explicit javascript on the site. When selecting a stuffed pasta, the menu for fillings is revealed. If an unstuffed pasta is chosen, the menu is hidden again. There is a comment box present for special orders. There is a form for the email and name.

[Back to Top](#belltini)
***
## ISSUES AND BUGS


## CREDITS
### Technologies used
1. JQuery
2. Javascript
3. Lightroom
4. CSS
5. HTML5

### Code credits
1. The nav element was loosely adapted from the example given on the [bootstrap navbar page](https://getbootstrap.com/docs/4.0/components/navbar/)
2. The gallery page was adapted from a free code snippet provided by [Bootstrapious](https://bootstrapious.com/p/bootstrap-photo-gallery).

### Acknowledgements
* Seun Owanikoko
* My friends and family who patiently looked at multiple iterations of my site.

[Back to Top](#belltini)
