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
The nav element was loosely adapted from the example given on the [bootstrap navbar page](https://getbootstrap.com/docs/4.0/components/navbar/)
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
