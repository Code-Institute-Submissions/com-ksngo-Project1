## Welcome to my project One,

I have created 'My Resume' webpages.

My resume home page is <a href="https://ksngo.github.io/Project1/" target="_blank"> `https://ksngo.github.io/Project1/`</a> . 

In my report, my webpages will be discuss with the five elements of UX. In addition, I have used google chrome as primary browser to inspect my webpages.

Thank you.

---------

**Contents**

1. Strategy

    a.  ssss
    b. sssss
    c. sssss
    
    `Home page`
    
    `My Journey Page`
    
    `More About Me`
2. Scope

    `Home page`
    
    `My Journey Page`
    
    `More About Me`
3. Structure

     `Home page`
    
    `My Journey Page`
    
    `More About Me`
4. Skeleton

    `Home page`
    
    `My Journey Page`
    
    `More About Me`
5. Surface

    `Home page`
    
    `My Journey Page`
    
    `More About Me`

--------

## 1. Strategy

Reason for WebSite: To showcase my resume to hiring companies on a webpage. The webpage shall contain the relevant information (e.g. experience, contact info, skills, portfolios, interests) for hiring companies to know more about me.

## 2. Scope

**Home Page**

1. Basic introduction of author
2. Contact information
3. Links to other two pages

**My Journey Page**
1. Line graph showing major milestones (e.g. education & employment status)
2. Employment history and details
3. Links to other two pages

**More About Me**
1. Skills
2. Portfolios and any certificates
3. Interests and hobbies
4. Links to other two pages

## 3. Structure

**Home Page**

1. Contains navigation bar to navigate to other pages
2. Contains Hero Image as background. Author basic info will display above this background image.
3. Contains text-box to display contact info and a form beside it for any interests or remarks to be logged.
4. Contains footer for social platform links.

**My Journey Page**
1. Contains navigation bar to navigate to other pages.
2. Contains background image and Line graphs are placed over it.
3. Contains card containers/boxes for Employment details.
4. Contains footer for social platform links.

**More About Me**
1. Contains navigation bar to navigate to other pages.
2. Contains secondary bar to navigate to other sections in this page.
3. Contains background image.
4. Contains section for skills information.
5. Contains section for portfolios information.
6. Contains section for interests and hobbies information.
7. Contains footer for social platform links.

## 4. Skeleton

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

## 5. Surface

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

1. The theme color use in this page are using bootstrap primary colour, white and bootstrap dark colour. The background colour is papayawhip skin color. The general color theme of the three webpages though are not completely similar but should not be also awkwardly different. The intention is to minimise user's confusion and maximise user's acceptance and likings to the choice of colour.
2. The secondary navigation bar has a opposite colour to primary navigation bar for contrast for their different purposes. On hover over, the background will become grey and texts will turn to black color. Hence, they can build closeness and identity with  the subsequent header (black background) which they are linked to.
3. The secondary navigation bar links to the three respective section headers. The section headers have a black background. The black colour is to clearly display the section headers while each section holds its content which are pretty rich in color. Hence, the black color will enhance the demarcation of the the content spaces. The margin and padding of the section's columns are set to enlarge the spaces between the sections and contents so that it will not be too claustrophbic. The spaces are also not too excessive to prevent redundancies. 
4. The row bar chart colors in the skills section will complement the respective skills image color. For example, css image is blue in color and the row bar color for it is also in blue color.
5. For the portfolio & interests/hobbies sections, the cards/buttons are also spaced apart to have more backdrop warm skin colour revealing.


Reported by : Ngo Kee Siang
Date: 22 March 2020

------------------------- End of Report. ------------------------


