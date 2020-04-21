# My Resume

This is my resume.

 
## UX
 
This website is for potential companies when I need to submit my resume to them. Resume on webpage as replacement to conventional Resume in Microsoft Words will provide a more advanced method of showcasing myself to companies. 

As a potential employer, I want to understand my applicant's background and strengths so that I can consider whether to invite him/her for interview.

As a jobseeker, I want to show employers my information(e.g. experience, contact info, skills, portfolios, interests) so that hiring companies can consider me.

## Features

### Existing Features

#### Scope
**Home Page**

Navigation Bar
    - Home 
        - allows user to know that this is the homepage. It also allows to be clicked to refresh the home page.

    - My journey
        - allows user to another webpage by clicking on it.
    
    - More about me
        - allows user to go to another webpage by clicking on it

Hero Image
    - allows user to understand the basic information about me. 

Contact
    - allows user to see my contact information.
    - allows user to contact me by clicking on submit button after having written into the form.

Footer
    - allows user to go to my linkedin or facebook pages by clicking on them.
    - allows user to see when this webpage is last updated.

**My Journey Page**

Navigation Bar
    -My Journey
        -allows user to know that this is the 'my journey' page.
    -Back to home
        -allows user to return to home page by clicking on it.
    -More about me
        -allows user to go another webpage by clicking on it.
    -Contact
        -allows user to go to my contact information page in home page by clicking on it.

Hero Image
    -Hero Image
        -allows user to see my milestones in year to year basis by clicking on the months.
    
Previous Employers
    -allows user to check on my previous employment record by clicking on respective companies name. 

Footer
    - allows user to go to my linkedin or facebook pages by clicking on them.
    - allows user to see when this webpage is last updated.


**More About Me**

Navigation
    -More about me
        - allows user to know that this is 'More About Me' page.
    -Back to home
        - allows user to return to home page by clicking on it.
    - My journey
        - allows user to go back to my journey page by clicking on it.
    - Contact
        -allows user to go to my contact information page in home page by clicking on it.

Secondary Navigation
    -Skills
        -allows user to go to 'Skills' section in the same page by clicking on it.
    -Portfolios & certificates
        -allows user to go to 'Portfolios and certificates' section in the same page by clicking on it.
    - Interests & hobbies
        allows user to go to 'Interests & hobbies' section in the same page by clicking on it.

Skills Section
    - allows user to see the skills in cards format or line chart format by clicking on the left or right chevron buttons.


Portforlios and certificates section
    - allows user to goes to my other portfolios by clicking on them.
    - allows user to understand each portfolios by reading the brief write-ups presented in each card.
    -allow user to see any certificates uploaded by my by clicking on them.

Interests & Hobbies
    -allows user to understand my interests and hobbies by hovering over each button.

Return to top
    -allows user to return to top by clicking on the upward pointing chevron button.

Footer
    - allows user to go to my linkedin or facebook pages by clicking on them.
    - allows user to see when this webpage is last updated.

#### Skeleton

**Home Page**
1. Navigation bar is mobile friendly and will align vertically for screen width 500px and below. The links are manually tested to ensure the links bring user to correct page or location.
2. Basic Info is display by an animation keyframes with animation duration of 3sec. Basic Info will display over the Hero Image.
3. The hero image also have animation keyframes of transform by scale 1.1 with animation duration of 5sec.
4. For photo, without hover, the effect is produced by using animation sliding. To make it blend in with the blue background, a layer is added above the elements of the photo and background color of blue and a degree of opacity. Finally, filter high contrast is used to accentuate the lighter and darker colour of the photo. For mobile friendliness of max width 850px, the photo will appear below the blue surface background.
5. Contact Information are displayed in flex and row direction. Contact entry by users are created as forms. Further backend work is required for the form to eventually pass the entries to the author. The contact information is mobile friendly and will align in columns for screen width 850px and below.
6. The footer bar's social platform icons on hover over, the font size will enlarge for additional interactivity. They are linked to respective social platforms. Kindly note author's place them as placeholders for time-being. 

**My Journey Page**
1. The navigation bar is mobile friendly and will collapse to hamburger for smaller screen. Author makes use of bootstrap NavBar components for this feature.
2. The background image is displayed in the HTML's body element.
3. The months shown along the line graph when hovered over will have a larger font-size in a white circle. Viewer can click on the months to popover further information on that month and can close them by clicking anywhere else on the page. Author makes use of bootstrap popover component with data-toggle of 'focus' instead of default 'manual-click' for this feature. User is guided to click on the first month by animated arrows. This feature's css/html codes are credited to @Raymond Bessemer at codepen.io.
4. At the bottom of the page,  author makes use of bootstrap collapse accordian component to display employment history. The user can click on respective employment period to expand out contents for that particular employment and click again to collapse the content. This will neatly hides the chunky content.

**More About Me**
1. The primary navigation bar is similar to the previous page.
2. The secondary navigation bar allows users to goes directly to the section in the page that they are interested in. Author makes use of bootstrap navs components for this feature.
3. The skills section has two layers displayed in the form of carousels which user can toggle by the directional button. The first layer makes use bootstrap card components and the second layer bootstrap progress components. The images transform by a scale of 1.1 when hovered upon for additional interactivity with user. The carousel effect makes use of bootsstrap carousel components.
4. The Portfolios section makes use of the bootstrap card columns. The images will also transform by scale 1.1 when hovered over for better user interactivity experience. A 'placeholder statement' will reveal itself clearly in blue when user hover over the respective portfolio because they are placeholders till author are to upload personal projects. The 'placeholder statement' hover over effect is made via css opacity value. User can open the portfolios' websites by clicking on the respective website names as they appear with black underline when hover over.
5. The interests & hobbies section makes use of bootstrap button type & popover components. User can quickly breeze through their content by just hovering over them.
6. A return to top icon is available at the bottom right so that user can return to top.

#### Surface

**Home Page** 

1. The color theme is in shades of blue and white. The contrast is clear and simple to the user eyes. 
2. The content on this page is minimal and aims for a simple introduction with relevant information.
3. The navigation bar links have hover-over effect by transform translate down so that users can visually notice when their mouse hover over the links. The text family for navigation bar is Oswald.
4. On starting the page, the words animation will begin to match the mood of the introduction. The words animation are using linear animation by different relative positions at different keyframes to produce the overall effect. The text family here is Roboto. At the background, the hero-image's animation is by transform scale of 1.1. The overall objectives is to produce an inviting and approachable introduction.
5. The sliding photo on hover over will change to original photo color with shadow effect as if the photos are above on a table. If user decided to view at the photos, when mouse out, the photo will blend in back to be congrous with the blue background so as to be less distracting to use with its original colour.
5. The contact form allows user to insert their information if they choose to. The text family here is Opensans.
6. The three text familes will be reused for the next two pages, with navigation & footer using Oswald, Body and sections using either Roboto or Opensans.

**My Journey Page**

1. The color theme of the page are chosen with bootstrap primary colour and white colour and green as the background. 
2. The background image has been chosen with an overhead view of forest with a horizontal road. The green forest are easy for user's eye and create acceptable contrast with the line graph. The road is meant for vehicles making journey and thus matching the identity of my content about my journey.
3. The simple line graph plots the years equivalently apart and months logically placed. User can be drawn attention to the first month to click on the month via the animation effects of arrows and 'Start'. User are then encouraged to click on respectives months to view more content that will stay open till user chose to click away. On hover over the months texts, they will be more conspicous with larger font and white circle background. Author hopes that this allow intuivity for users to begin clicking the month of July and start moving along the line graphs to click the available months for more content reading.
4. For the bottom table, upon page being loaded, the first column content will always be uncollapsed so that user is aware there are more content for each column headers. Each respective headers' link will also appear with underline when hover over.

**More About Me**

1. The theme color use in this page are using bootstrap primary colour, white and bootstrap dark colour. It shares the same background colour with the home page.
2. The secondary navigation bar has a opposite colour to primary navigation bar for contrast for their different purposes. On hover over, the background will become grey and texts will turn to black color. Hence, they can build closeness and identity with  the subsequent header (black background) which they are linked to.
3. The secondary navigation bar links to the three respective section headers. The section headers have a black background. The black colour is to clearly display the section headers while each section holds its content which are pretty rich in color. Hence, the black color will enhance the demarcation of the the content spaces. The margin and padding of the section's columns are set to enlarge the spaces between the sections and contents so that it will not be too claustrophbic. The spaces are also not too excessive to prevent redundancies. 
4. The row bar chart colors in the skills section will complement the respective skills image color. For example, css image is blue in color and the row bar color for it is also in blue color.


#### Features Left to Implement
- The portfolios section in 'More about me' page are currently only stand-in and are not my portfolios. They will be updated.
- The Skills section in 'More About me' page can be updated with more skills in the future.
- The line graph at the 'My journey' page can be updated to any future milestones.
- The contact form at the 'home' page can be touched on to connect to backend.
- The footer's linkedIn and Facebook icons can be linked to ready social platforms in the future.

## Technologies Used

- [BootStrap](https://getbootstrap.com/docs/4.4/getting-started/introduction/)
    - The project uses **BootStrap** for styling CSS for 'My Journey' and 'More About Me' webpages.
- [Fontawesome 4.7](https://fontawesome.com/v4.7.0/get-started/)
    - The project uses **FontAwesome** for the social platforms fonts and chevron fonts.
- [Google Fonts](https://fonts.google.com/)
    - The project uses **Google Fonts** for font family.
- [JQuery](https://jquery.com)
    - The project uses **JQuery** which are used because bootstrap requires them.
- [Arrow animation](https://codepen.io/rbessemer/pen/kxmFD?__cf_chl_jschl_tk__=292975ab154eaca5ab3b8a304c6948a20ec06141-1584604089-0-ARp8mLUtgfnRiEmGJXJekyn1esXX51v_X6Cos2aDNcLC5pl75KSFPzXUm2xFj5D6lxBR1pOouqKDal_oApslnlNsgRFUzGWVPwMxY9nDtvBg1tikP-NHXqM-j3tOmicb122NNUBrmJ7c7QpxaNJ3ogbUYY9UowWlT2nQ7iDVmtUKLSOHgALzie6PhJJTbGTXzWpozxqG_LXIigtE_Z-e36SGEx39larAOvN1briU2CkYAorCQufSJ2Moi_ur79-kuWI3vgpcFgth3DUIbACYzt-xDEZ1oD0FbsDyE7u-We4Bu5FwBIEHgKyZ6XX60r6eY-eVjevNoTBv8h57onGNqvFMp9UIQf7On6OIMS7vsqe9 )
    - The project uses **Raymond Bessemer** work as guide for creating arrow animations in the 'My Journey' webpage in the line graph.
    

## Testing

In this section, you need to convince the assessor that you have conducted enough testing to legitimately believe that the site works well. Essentially, in this part you will want to go over all of your user stories from the UX section and ensure that they all work as intended, with the project providing an easy and straightforward way for the users to achieve their goals.

1. Contact form:
    1. Go to the "Contact Us" page
    2. Try to submit the empty form and verify that an error message about the required fields appears
    3. Try to submit the form with an invalid email address and verify that a relevant error message appears
    4. Try to submit the form with all inputs valid and verify that a success message appears.


1. Home:
    1. 
In addition, you should mention in this section how your project looks and works on different browsers and screen sizes.

You should also mention in this section any interesting bugs or problems you discovered during your testing, even if you haven't addressed them yet.

If this section grows too long, you may want to split it off into a separate file and link to it from here.

## Deployment

This section should describe the process you went through to deploy the project to a hosting platform (e.g. GitHub Pages or Heroku).

In particular, you should provide all details of the differences between the deployed version and the development version, if any, including:
- Different values for environment variables (Heroku Config Vars)?
- Different configuration files?
- Separate git branch?

In addition, if it is not obvious, you should also describe how to run your code locally.

My resume home page is <a href="https://ksngo.github.io/Project1/" target="_blank"> `https://ksngo.github.io/Project1/`</a> . 

## Credits

### Content
- The text for section Y was copied from the [Wikipedia article Z](https://en.wikipedia.org/wiki/Z)

### Media
- The photos used in this site were obtained from ...

### Acknowledgements

- I received inspiration for this project from X