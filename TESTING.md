# WeBuilder Website - Testing details

Main README.md file (https://github.com/Scorptech/milestoneone/blob/master/README.md)

View website in GitHub Pages (https://github.com/Scorptech/MilestoneOne)

### Testing

* [W3C CSS validation](https://validator.w3.org/)
* [W3C Markup Validation](https://jigsaw.w3.org/css-validator/)

The developer used W3C CSS Validation Service and W3C Markup Validation Service to check the validity of the website code.

### User Stories Testing:

#### Most common path through the website:

Home 

Each menu link navigates you to each section on the same page 

### The "Team" page offers information about the staff. The information here is kept short with a brief description.

### Testing user stories from UX section of README.md

As a new visitor to the website, I want to easily navigate the site, so I can find what I need efficiently.
No matter what page the new visitor lands on, they can easily find and use the navigation bar.
The logo image always leads back to the home page (the starting place for most customers).
    
As a visitor to the website, the customers will see profiles of staff members as this makes the site and the company more personal.
A clearly labelled "Request A Quote" is easy to find on the image carousel and further down the page.
  
As a potential customer, I want to have the opportunity to view previous work that the company have done and speak to 
existing customers as I know that some companies use library images from the internet and pass the work off as their own.

When it comes to building and construction work, I would like an estimate (based on my requirements) and also a general idea of 
the time to complete the project. 

As an interested customer, I want an easy to fill in contact form, so I can make contact with the company for general
enquiries. A clearly labelled contact page is easy to find in the website navigation on every page.

As an interested observer and/or potential customer, I want to follow the company on social media, so I can keep up with their latest news.
6 social media icons can be found in the top bar and the footer on every page of the website.

As a returning visitor to the website, who has already decided to contact the company, I want to be able to request a quote easily.
There is a clearly marked "Request quote" button in the carousel and further down the page, highlighted as a yellow button. It displays in the carousel at the top and the bottom for desktop, mobile and tablet screens.

### Manual (logical) testing of all elements and functionality on every page.

The initial build of the website was not following some of the bootstrap guidelines. After speaking to my mentor, I started again and
coded the website according the bootstrap guidelines. 

### Home Page:

#### Top bar:
Initially had problems with the alignment of inline-block elements. Changed container to a Nav section header which then made all the
inline-blocks line up.
Added website links to the social icons.  
    
####  Navigation bar:
Go to the "Home" page from a company logo.
Change the screen size from desktop to tablet to verify that the navigation bar is responsive and switches from in line menu to burger icon dropdown menu at the appropriate place.  Had to give burger icon some spacing with media queries. 
Hover over the images to verify that the alt text appears. During testing this did not happen, so I added a title attribute to all images  to fix
Click on the logo in the navigation bar and verify that it links to the home page.
Click on each navigation menu item and verify that it links to the correct page.
Hover over the "request a quote" button and verify the hover colour changes as expected.
Click on the "request quote" button and verify that it loads the modal quote page.
Change screen size to small and click burger icon, verify that the menu drops down and that the menu text is centred.
Repeat verification of functionality and responsiveness on my mobile phone and tablet.

####  Carousel:
Go to "Home" page from a desktop.
Confirm that the carousel is working and the slides are changing. 100% width of the screen.
Reduce the width of the window to confirm that the carousel and text fits on mobile and tablets.
Reduce and expand width of window to make sure the the text resizes depending on the how it is being viewed.

####  Company information section:
Reduce and expand width of window to confirm that the text on the home page responds correctly and looks good on all device widths.

####  Request A Quote button:
Hover over "Request A Quote" button and verify the hover colour change. Click the "Request A Quote" button and verify that it loads the modal form.

####  Footer:
Hover over each social media icon and confirm colour and size transitions expected.
Reduce and expand width of window to verify that the footer is responsive and looks good on all device widths.
Check email link to make sure the colour changes and the link is active.
Added website links to the social icons.  

Review all functionality and responsiveness on my mobile phone and tablet.

### The Team Page:

####  Navigation bar:
Repeat verification steps done for navbar on Home page.
Confirm that navbar code is identical on all html pages.

####  Carousel image:
Hover over images and confirm that alt title appears.
Reduce and expand width of window to verify that the carousel behaves and centres 
the way expected, and that it looks good on all device widths.

####  Page images:
Hover over each image in the content and confirm that the alt title for each appears.
Reduce and expand width of window to verify that each image behaves and centres the 
way expected, and that they look good on all device widths.

####  Page content:
Reduce and expand width of window to verify that each staff card behaves as expected and that the transitions expand and contract as
expected. Check staff cards look good on all device widths.

####  Request A Quote buttons:
Hover over each "Request A Quote" button and verify the hover colour change.
Click each "Request A Quote" button and verify that it loads the modal form.
Reduce and expand width of window to verify that the "Request A Quote" buttons spacing responds as expected.
Confirm that the buttons move to stacked on top of each other for mobile devices.

####  Footer:
Repeat verification steps done for footer on Home page.
Confirm that footer code is identical on all html pages.

Review all functionality and responsiveness on my mobile phone and tablet.

### Contact Page:

####  Navigation bar:
Navbar code is identical on all html pages. Testing already completed.

####  Carousel:
Repeat verification steps done for carousel on home page.

####  Contact form:
Reduce and expand width of window to verify that the form display 
behaves and centres the way expected, and that it looks good on 
all device widths.

####  Footer:
Footer code is identical on all html pages. Testing already completed.

Review all functionality and responsiveness on my mobile phone and tablet.

### Further Testing:

Due to a number of issues with an image in the home page content and speaking to CI tutors, mentors and slack students, I decided
to remove this from the finished site as no solution that was given seemed to work with the image, so the best and easiest solution was
to remove image. 
 
I viewed the website on several browsers and formatting was consistant.

### A note to my fellow Code Institute students

[Anna](https://github.com/AJGreaves) has done a fantastic job with her TESTING.md file and it is referred to as the "go to" file for showing the students how to "lay things out". Well as they say "Imitation is the sincerest form of flattery" so I have taken a few ideas from Anna's TESTING.md file, As it is, after all, recommended on how to write it!  

Namaste

Alan