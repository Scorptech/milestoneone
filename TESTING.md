# WeBuilder Website - Testing details

[Main README.md file] (https://github.com/Scorptech/milestoneone/blob/master/README.md)

[View website in GitHub Pages] (https://github.com/Scorptech/milestoneone)

### Testing

* W3C CSS validation
* W3C Markup Validation

The developer used W3C CSS Validation Service and W3C Markup Validation Service to check the validity of the website code.

### Client stories testing:

#### Most common path through the website:

    Home > Gallery > Pricing > How to Order > Contact
    Each of these pages points clearly to the next one with a call to action button. In some places the customer may have a different question in their mind, so a second button is also provided.

The About page is not necessarily part of the flow of the site for users, but it has been included to offer information about the artist for those who are curious about her. The information here is kept short as to not overload the user.

Some pages offer two possible paths in their call to action buttons:

    From About > Gallery OR How to Order
    From Gallery > Pricing OR How to Order

Testing client stories from UX section of README.md

    As a new visitor to the website, I want to easily navigate the site, so I can find what I need efficiently.
        No matter what page the new visitor lands on, they can easily find and use the navigation bar.
        The logo image always leads back to the home page (the starting place for most client stories).
        The home page call to action button leads the client through the gallery.

    As a new visitor to the website, I want view this artist's gallery, and view their work in detail so I can decide if I want to commission their work.
        At the bottom of the Home page and About page there is a clear call to action button leading the visitor to the gallery.
        A clearly labelled Gallery page is easy to find in the navigation on every page..

    As a visitor to the website, I am curious to know more about the artist, so I can feel I connect with her as a person.
        A clearly labelled How to About page is easy to find in the navigation on every page..
        The About page contains photos of the artist in her studio, and short but compelling text about what the artist enjoys about her work.

    As a potential client, I want to know what past clients thought of their artwork and the service they received.
        On the home page, testimonials from past clients are easy to find and to read.

    As a potential client, I want to view expected prices for a portrait, so I can decide if it is within my budget to order.
        A clearly labelled pricing page is easy to find in the navigation on every page..
        Once the visitor to the website has already been led by call to action buttons from the Home page, and through to the Gallery, they are then led to the Pricing page.

    As an interested client, I want to understand the ordering process, so I know what steps to take next.
        A clearly labelled How to Order page is easy to find in the navigation on every page.
        Once the visitor to the website has already been led by call to action buttons from the Home page, and through to the Gallery, and Pricing page, they are then led to the How to Order page.
        The How to Order page clearly and intuitively explains the steps involved in placing an order, using icons to add another level of clear communication to the explanation.
        At the bottom of the How to Order page, the first step in ordering is clearly marked as a call to action button. Which leads to the contact page.

    As an interested client, I want an easy to fill in contact form, so I can make contact with the artist and place my order.
        A clearly labelled contact page is easy to find in the website navigation on every page.

    As an interested observer and/or potential client, I want to follow the artist on social media, so I can keep up with her latest news.
        5 social media icons can be found in the footer on every page of the website.

    As a returning visitor to the website, who has already decided to contact the artist, I want to be able to request a quote easily.
        There is a clearly marked "Request quote" button in the navigation bar, highlighted as a button so that it stands out from all the other menu items. It displays in the top right of desktop and tablet screens, and at the bottom of the dropdown menu on mobiles.

Manual (logical) testing of all elements and functionality on every page.
Home Page:

    Navigation bar:
        Go to the "Home" page from a desktop.
        Change the screen size from desktop to tablet to verify that the navigation bar is responsive and switches from in line menu to burger icon dropdown menu at the appropriate place.
        When checking responsiveness of navbar, verify that there is no overflow causing ugly size changes to menu items. During testing there were overflow problems here. This was fixed by reducing size of the button and logo margins
        Hover over the logo in the navigation bar and verify that the alt text appears. During testing this did not happen, so I added a title attribute to the logo to fix
        Click on the logo in the navigation bar and verify that it links to the home page.
        Click on each navigation menu item and verify that it links to the correct page.
        Hover over the "request quote" button and verify the hover colour change works as expected.
        Click on the "request quote" button and verify that it links to the contact page.
        Change screen size to small and click burger icon, verify that the menu drops down and that the menu text is centred.
        Repeat verification of functionality and responsiveness on my mobile phone and tablet.

    Hero image / video:
        Go to "Home" page from a desktop.
        Confirm video is visible, autoplays on mute and is 100% width of the screen.
        Reduce the width of the window to confirm that the video switches to static image in mobile.
        Reduce and expand width of window to confirm that the overlay on top of image / video responds correctly and does not obscure important features.

    Compelling copy section:
        Reduce and expand width of window to confirm that the text in this section responds correctly and looks good on all device widths.

    Testimonials:
        Reduce and expand width of window to confirm that 3 testimonials display on medium to large screens, but one is hidden on mobile devices.

    Call to action button:
        Hover over call to action button and verify the hover colour change.
        Click the call to action button and verify that it links to the correct page.

    Footer:
        Hover over each social media icon and confirm colour and size transitions expected.
        Click on each icon to confirm it opens a separate tab for it's link.
        Reduce and expand width of window to verify that the footer is responsive and looks good on all device widths.

    Review all functionality and responsiveness on my mobile phone and tablet.

About Page:

    Navigation bar:
        Repeat verification steps done for navbar on Home page.
        Confirm that navbar code is identical on all html pages.

    Hero image:
        Hover over hero image and confirm that alt title appears.
        Reduce and expand width of window to verify that the hero image behaves and centres the way expected, and that it looks good on all device widths.

    Page images:
        Hover over each image in the content and confirm that the alt title for each appears.
        Reduce and expand width of window to verify that each image behaves and centres the way expected, and that they look good on all device widths.

    Page content:
        Reduce and expand width of window to verify that each line of text behaves the way expected, and that the text arrangement looks good on all device widths.

    Call to action buttons:
        Hover over each call to action button and verify the hover colour change.
        Click each call to action button and verify that it links to its relevant correct page.
        Reduce and expand width of window to verify that the call to action buttons spacing responds as expected.
        Confirm that the two buttons move to stacked on top of each other for mobile devices and display next to each other for larger screens.

    Footer:
        Repeat verification steps done for footer on Home page.
        Confirm that footer code is identical on all html pages.

    Review all functionality and responsiveness on my mobile phone and tablet.

Gallery Page:

    Navigation bar:
        Navbar code is identical on all html pages. Testing already completed.

    Hero image:
        Repeat verification steps done for hero image on About page.

    Gallery:
        Hover over each gallery thumbnail and confirm the hover animation works as expected.
        Check code to confirm that each gallery thumbnail has a descriptive alt attribute. Titles were deliberately not added here because they ruin the clean look of the gallery page. Because of the alt attribute the page is still navigable for visually impaired users
        Click on each gallery thumbnail and confirm that the Fancybox gallery modal activates.
        In the gallery modal test click forwards and backwards, play and pause functions and confirm they all work as expected.
        Reduce and expand width of window to verify that each row of gallery images behave and centre the way expected, and that the grid of images looks good on all device widths.

    Call to action buttons:
        Repeat verification steps done for call to action buttons on About page.

    Footer:
        Footer code is identical on all html pages. Testing already completed.

    Review all functionality and responsiveness on my mobile phone and tablet.

Pricing Page:

    Navigation bar:
        Navbar code is identical on all html pages. Testing already completed.

    Hero image:
        Repeat verification steps done for hero image on About page.

    Pricing tables:
        Reduce and expand width of window to verify that each table responds in the way expected, they display next to each other on desktop, but stacked on top of each other on mobile and tablet.
        Confirm the page looks good at all device widths.

    Small print:
        Reduce and expand width of window to verify that the small print text behaves and centres the way expected, and that it looks good on all device widths.

    Call to action button:
        Repeat verification steps done for call to action button on Home page.

    Footer:
        Footer code is identical on all html pages. Testing already completed.

    Review all functionality and responsiveness on my mobile phone and tablet.

How to Order Page:

    Navigation bar:
        Navbar code is identical on all html pages. Testing already completed.

    Hero image:
        Repeat verification steps done for hero image on About page.

    Steps to Order Section:
        Reduce and expand width of window to verify that the steps containers, icons and text display the way expected,
        Confirm that the steps look good on all device widths.

    Completion times text:
        Repeat verification steps done for small print on pricing page.

    Call to action button:
        Repeat verification steps done for call to action button on Home page.

    Footer:
        Footer code is identical on all html pages. Testing already completed.

    Review all functionality and responsiveness on my mobile phone and tablet.

Contact Page:

    Navigation bar:
        Navbar code is identical on all html pages. Testing already completed.

    Hero image:
        Repeat verification steps done for hero image on About page.

    Contact form:
        Try to submit the empty form and verify that an error message about the required fields appears
        Try to submit the form with an invalid email address and verify that a relevant error message appears
        Try to submit the form with a file uploaded, verify that file selection process works.
        Try to submit the form with all inputs valid and verify that a success message appears.
        Reduce and expand width of window to verify that the form display behaves and centres the way expected, and that it looks good on all device widths.

    Footer:
        Footer code is identical on all html pages. Testing already completed.

    Review all functionality and responsiveness on my mobile phone and tablet.

Further testing:

    Asked fellow students, friends and family to look at the site on their devices and report any issues they find. margins were adjusted for navigation bar after feedback that "request quote" button was too close to nav menu on some devices
    I viewed my website on several devices at a local tech store, no further issues found.

A note to my fellow Code Institute students

I am happy that you have come to look at my testing.md file as an example of how to write a good one for your second Milestone project. You are welcome to learn how to structure and format your own testing.md from mine.

However, it is not ok to copy and paste large portions of it into your own project. Please remember to write your own, rather than copying mine or someone elses.

Many thanks! Anna