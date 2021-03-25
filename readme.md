![Logo with belltini page](assets/images/images-readme/readmeheader.jpeg "belltini header")
[View the page on github here](jdygard.github.io/belltini "Belltini Homepage")

#Table of Contents

[Introduction](#Introduction)
---
[UX](#ux)
---
-[User stories](#user-stories)

[Planes of UXD](#planes-of-uxd)
---
--[Strategy](#strategy)

--[Scope](#scope)

--[Structure](#structure)

--[Skeleton](#skeleton)

--[Surface](#surface)

[Current Features](#current-features)
---
--[Nav Bar](#nav-bar)

--[Footer](#footer)

--[Nav Bar](#nav-bar)


***
## Introduction

This streamlined website is built for Belltini Pastas, an Indianapolis, Indiana based business selling bespoke fresh formed and stuffed pastas. The primary focus of this site is as a portal to sell pasta, but will also serve to expand knowledge and web-presence of the Belltini brand.
Belltini currently sells pastas intermittently to local restaurants and a limited set of local private consumers. With this site, the purpose is to expand the pool of customers and provide a professional face for the brand.
Additionally, this is built as the first of four "Milestone Projects," building the developer's portfolio and as a demonstration of the developer's understanding of HTML5 and CSS components.
***
## UX
### Users:
1. Current commercial customers
2. New commercial customers
3. Current private consumers
4. New private customers

***

## USER STORIES
### Current commercial customers
1. As a current commercial customer, I want to find pictures and information about new products, or review and purchase current products not yet on my restaurant menu.
2. As a potential new commercial customer, I want to see the commitment to quality and easily find information about products and expanding my own inventory.
### Personal visitors
3. As a current private consumer, I am interested in finding products I haven't yet tried or preview new products.
4. As a new private customer, I want to see why I should choose to buy fresh, handmade pasta for a premium price rather than machine-made from the grocery store. I want to see product images or learn about fresh pasta in general.
***
## Planes of UXD
### Strategy: Who is this website for, and what does it do?
1. Audience
    i. New and current commercial customers, new and current private customers
    ii. Fresh, handmade pasta has a short shelf-life, and a high cost per portion. This means that it is less practical and more expensive.
        Private consumers will likely either be young (20-29 years old) and sporadic, or 30+ years old. The target audience is thus older and accustomed to professionalism and clean, modern UI.
        Commercial customers will be high-end restauranteurs with expectations of clean, modern UI with concise information about the products.
2. Functional requirements
    i. Easy access to information, like new products, flavors, styles and biography.
    ii. Ability to order the product.
    iii. Ability to contact the business.
3. Benefit to Belltini
    i. The website should present a professional public face.
    ii. The website should provide access to the product.
    iii. The website should attract new customers.
### Scope: What's on the table in terms of features?
1. User is able to purchase the product.
2. User is able to learn about the product.
    i. Through highlighting the benefits of fresh pasta in general and Belltini in particular.
    ii. Video and images that intrigue and tempt the user to purchase.
3. User is able to learn about the business and the chef.
### Structure: How is the information structured and grouped?
1. A splash home page with small bits of easily-digestible information and direct links to the order page.
2. Multiple pages with deeper dives into each avenue of information
    i. A "Learn More" page with a video of fresh pasta being made by a master chef.
    ii. A gallery page featuring pastas made by Belltini
    iii. A biographical page with information about the chef.
3. An explicit and structured page with an order form.
### Skeleton: How do we represent this information? How does the user find it?
1. The home page features snippets of information with links to learn more at each step.
2. The nav bar is clear and explicit about the information to be found on each page.
### Surface: What does it look like?
1. Customers of this page will expect a clean, light, modern design with clear, simple features arranged intuitively. 
    i. In working directly with the owner of Belltini, a color scheme of off-white colors and backgrounds featuring the products was    used.
    ii. Font: Montserrat was chosen for most informational features for its clean, modern look. Roboto was used for buttons, forms and hero image boxes because of its high visibility while retaining some modern tone.
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

### Acknowledgements
* Seun Owanikoko
* My friends and family who patiently looked at multiple iterations of my site.

***
***
***
***
***


# Belltini Pastas
Belltini pastas is an Indianapolis based business selling handmade pastas to local restaurants or individual consumers. It is run by the dev's sister.

## Intended audience
High-end restaurants or high-budget consumers.

## Pages and development
The site will be separated into four pages:
### Index
Homepage with a hero image and prominent call-to-action, followed by a "Why Fresh Pasta?" section, highlighting the benefits of fresh pasta. At the end, a short "Why Belltini?" section, reiterating the bespoke nature of the service with an additional call-to-action.
### Gallery/menu
A gallery page with images of the product in block format, that will serve the additional purpose of being a menu of style, color and flavor.
### About
A short bio page about the chef.
### Order
An order form.

## Code attributions
### Nav element
### Gallery page
The gallery page was adapted from a free code snippet provided by [Bootstrapious](https://bootstrapious.com/p/bootstrap-photo-gallery).

## Page notes
### Index
#### Nav element
I decided I liked the hamburger button on the right for thumb accessibility. I also moved the bootstrap dropdown menu to the right for the same reason, and trimmed it to not occlude the page. Full-width nav returns the links to the left for a cleaner design.
#### Hero image
I played around a lot with the background orientation and image. I chose this image because it conveys all the core elements of the page: they were clearly made fresh, with visible green herbs and flour, and a little bit of disarray. However, they're  also clean, as uniform as you'd want, professionally made and appetizing.

I wanted the box to be more translucent but I couldn't get the text readable and nice enough without a dark box. I put an order button right up front to serve the core goal of the site.
#### Why fresh pasta?
I opted for bootstrap here for easy responsiveness. There are four elements here, with the fourth omitted on smaller screens for a cleaner design. The hero image is sized to allow part of this section to peek from the bottom of the page, enticing a reader to look further. We hit on a few good reasons to use the type of product being sold here.
#### Why Belltini?
I really liked the [background image](https://www.pexels.com/photo/cook-making-fresh-dough-in-bakery-6287313/) I found here. It's one of two images not taken by Belltini on the site. The question asked, "Why Belltini?" is answered twice, both by the image and the words. The image and text together say "You're getting the personal service of a skilled professional, making products she's passionate about."

Because the original image is so large and I'm only using a small part of it, I've trimmed the original into three versions and created custom breakpoints, to keep legibility on the text while preserving the natural framing device in the original image.

I put another order button here for those who scrolled down.

### About page
I decided to use bootstrap to organize this page entirely. Other than the background image, all elements are on a single row. I used custom breakpoints in CSS to order and style things as they reorder in the row.
#### Profile image and text
I liked this profile image and text. I used the transform: translate() property to move the text box into the position it's in. I also added a custom breakpoint to maintain the look on smaller viewports.
#### Blurbs
I called the small blocks of about text "blurbs." I think I kept them stylish and readable on all viewports. Though I would have loved to keep the herbs in the background image visible on smaller viewports, it was difficult to keep the text readable on very small viewports without the herbs interfering. I may go back and make the background fixed on small backgrounds and have the herbs only appear near the profile picture.
