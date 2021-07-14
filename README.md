# Cookout Brand Awareness

Cookout is a brand that as been estabilished since 1984 it has gone through two new branding updates but has never had a website of it's own. It's a McLoughlinsRS own brand one of Ireland largest retail distributors of Gardening Homewares and DIY in Ireland. Cookout is sold on the B2B website but there is no information background about the product that can be shared with the customer via it's own site or being shared on retailers websites via a link. This would create more brand awarness.  

I hope this website will inspire people to get cooking outdoors and use the Cookout brand while doing so. Keeping with the brand colors and theme, a website that is easy to navigate and not taxing on the user.

# Design for More Accessibility
I wanted my site to be SEO friendly, and once you design an accessible website you will have better search results and reach a bigger audience. Navigation options that are clear and consistent, consistent naming. styling and positioning. Have clear orientation clues. Clear labelling of any forms and have them validated. Provide sufficient contrast between forground and background low luminace is needed for anyone that maybe visual impared. Use headings and spacing to group related content, use white space, dont let it be your emeny reduce clutter and make it easier to scan and understand. Create for different viewport sizes. Include 'alt' on your images. Have alternatives for images and media for example links to audio and include text along with icons and buttons. If I had included a video I would have had contols. If you design for all you get a better user experience for everyone, and it cheaper to do at the inital stage of design process.

![How site would look](assets/images/Screenshot.png)
Adobe Xd High Fedelity Wireframe Link (https://xd.adobe.com/view/c718dec8-7b3f-4b80-7464-25e5be7b8f89-b129/)

## Features 

Cookout website is five pages in total with social media links and link to retail distributors webiste and shopping portal for retailers

### Features

- __Navigation Bar__

  - Featured on all five pages, the full responsive navigation bar includes links to, Home page, Where to Buy and Recipe page giving someting free to the user in the form a BBQ recipe and digital book to download. The nav bar was made sticky so that on longer scrolling pages and mobile it was visable at all times.
  - This allows the user to easily navigate from page to page across all devices without having to revert back to the previous page via the ‘back’ button as its not always a good thing to depend on. 
  - Also added an active selector to each page on the navigation bar for users to naviagte.

![Nav Bar](assets/images/nav.png)

- __The landing page image__

  - Main landing page includes a light intro and brand logo, background image allows brand logo to stand out off page. 
  - Just to note, I used the three versions on the Cookout logo on this website for brand awareness and make impact on user.
  - Product images are shown on this page to show category offering from the brand. Information on products is short and concise.
  - This page is long, so I have included click down and up buttons. 
  - Social media icons are only included on the first page, otherwise I feel the user will go down rabbit hole. I want to keep the user on website.
  - On footer the address and telephone of distributor exsist and is clickable to be taken to distrubutors website.

![Landing Page](assets/images/landing.png)

- __Instant barbecue__

  - Image styled off page to give more interest, position was -40px changes to centered square image on mobile.

![Instant Barbeque Image](assets/images/off-page.png)

- __Where to Buy__

  - This page shows the user where to buy the products. Logo's of stores are listed here. Links could be included to retailers website were product is sold. 
  - There is a link included to Retail distributors E-Shop as the company does not sell directly to consumer. 

![Where to Buy](assets/images/were-to-buy-page.png)

- __Recipe__

  - Bright image of freshly made sauce and recipe to follow.
  - Nothing like getting something for free even if its a digital recipe book or free recipe to make sauce.
  - Maybe the next time that buyer goes into shop they remember the free 'Cookout Recipe they recived and digital book'
  - By this stage the users has seen all three version of the Cookout logo.
  - Crips clean and uncluttered. 

![Recipe](assets/images/recipe-page.png)

- __The Footer__ 

  - The footer section includes links to the relevant social media sites for the retail distributor of the brand 'Cookout'. The links will open to a new tab to allow easy navigation for the user. 
  - Social media icons are only on main index.html page. The idea behind this is to direct the user around the website finding out about the brand.

![Footer](assets/images/footer.png)

- __Form for Digital Book__

  - Allowing the user to recieve a free digital recipe book connected with Barbeques. The user will be asked to submit their full name and email address. How they heard abou the brand. 

![Form for free Recipe Book](assets/images/book-form.png)

- __Thank-you__

  - A message to signify to the user the process has been complete and the digital Cookout cook book its on its way to them.

![Form for free Recipe Book](assets/images/thnak-you.png)

### Features Left to Implement

- Adding more new products and new recipe ideas. Once the user signs up for the recipe book, they are not a cold call anymore and can be contacted with new products and more recipe ideas.
- Links can be added to 'Where to Buy' page on logo's to take user directly to purchse page for product.
- Add a little background softly playing cowboy music. 
- Add video tutorials on cooking using Barbeques.

## Testing 

While in the Dev Tools I used the responsive tools to view site on iPad and iPhone 5. I also opened on my own Samsung 6
as well as seeing it my iMac. I left one or two items uncentered and this created a nice pause for the eye and flow 
of reading.(you can get bored travelling in a straight line all the time i.e motorway driving) I also sent to two alternative phone.

All my links work to other websites opening in new windows not to draw the user away The links open on themselves. Screen shots of all testing available in Testing folder.

It has performed the way I wanted it to on different browsers and screen sizes. Quite amazed at the power of flexbox from the little information I know baout it.

### Validator Testing 

- HTML
  - I have passed all my html pages on W3 HTML Validator and all pages have finally received a document checking completed with no errors or warnings to show. Main errors were rogue tags and alt information added into links that did not need to be there. [W3C validator](https://validator.w3.org/nu/?doc=https%3A%2F%2Fcode-institute-org.github.io%2Flove-running-2.0%2Findex.html)
- CSS
  - I also used W3 Jigsaw Validator to pass my css file, I had 9 errors and 1 warning which all have been resolved. [(Jigsaw) validator](https://jigsaw.w3.org/css-validator/validator?uri=https%3A%2F%2Fvalidator.w3.org%2Fnu%2F%3Fdoc%3Dhttps%253A%252F%252Fcode-institute-org.github.io%252Flove-running-2.0%252Findex.html&profile=css3svg&usermedium=all&warning=1&vextwarning=&lang=en#css)
- Lighthouse
  - I used Lighthouse from the dev tools to show up any issues with performance, accessibility, best practice, SEO, and perforamnce these can be found in the testing folder as screenshots.

### Unfixed Bugs

I did not center a heading on the recipe page as I think the page reads better, it has a nice flow. White space can be important.
Unfixed bug was a user agent stylesheet that I believe is in chrome. More research needed on that.

## Deployment

In order for someone to access I must deploy site to Github from Gitpod the container-based development platform I have been using: 
  - Make sure that I have "git added", "git commit -m" & "git push" to Github
  - Once in Github, I navigated to my sites repository - https://github.com/nedduc
  - Under my repository name, to the right of the screen click  Settings.
  - In the left sidebar, click Pages.
  - Under “GitHub Pages”, use the None or Branch drop-down menu and select a publishing source.
  - Optionally, use the drop-down menu to select a folder for my publishing source.
  - Waited for page to refresh.
  - Scroll back down to Github pages section to get my deployed link.

The live link can be found here - https://nedduc.github.io/Cookout-Brand-Awareness/

## Credits 

I would like to thank my Cohort Facilitator Kasia and my mentor Maria Hynes, two very kind and patient people. My mentor gave me some great advice.
My code was helped along by W3 Schools https://www.w3schools.com/

https://www.freecodecamp.org/learn

https://css-tricks.com/pseudo-class-selectors/

http://ami.responsivedesign.is/

https://flexboxfroggy.com/ 

### Content 

- The text for the website was taken from a data base in work. Recipe courtesy of BBC Good Food Guide.
- The icons in the footer were taken from [Font Awesome](https://fontawesome.com/)
- The Video by <a href="https://pixabay.com/users/xiaoskitchen-1319509/?utm_source=link-attribution&amp;utm_medium=referral&amp;utm_campaign=image&amp;utm_content=11679">Peter &amp; Xiao Harris</a> from <a href="https://pixabay.com/?utm_source=link-attribution&amp;utm_medium=referral&amp;utm_campaign=image&amp;utm_content=11679">Pixabay</a>

### Media

- The main photos used on each page are from Adobe stock. Product images are from work.
- The images used for the form page taken from open source site Unsplash https://unsplash.com/s/photos/bbq
- Cookout logo designed by myself as well as the packaging and digital book.


______________________________________________________________________________________________________________