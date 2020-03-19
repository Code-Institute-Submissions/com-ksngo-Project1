<img src="https://codeinstitute.s3.amazonaws.com/fullstack/ci_logo_small.png" style="margin: 0;">

Welcome,
 
Please find my resume page at <a href="https://ksngo.github.io/Project1/" target="_blank"> `https://ksngo.github.io/Project1/`</a> .

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
4. Contact Information are displayed in flex and row direction. Contact entry by users are created as forms. Further backend work is required for the form to eventually pass the entries to the author. The contact information is mobile friendly and will align in columns for screen width 750px and below.
5. The footer bar's social platform links are placeholders till author's respective social platform links are ready. On hover over the icons, the font size will enlarge for additional interactivity.

**My Journey Page**
1. The navigation bar is mobile friendly and will collapse to hamburger for smaller screen. Author makes use of bootstrap NavBar components for this feature.
2. The background image is displayed in the HTML's body element.
3. The months shown along the line graph when hovered over will have a larger font-size in a white circle. Viewer can click on the months to popover further information on that month and can close them by clicking anywhere else on the page. Author makes use of bootstrap popover component with data-toggle of 'focus' instead of default 'manual-click' for this feature. User is guided to click on the first month by animated arrows. This feature's css/html codes are credited to @Raymond Bessemer at codepen.io.
4. At the bottom of the page,  author makes use of bootstrap collapse accordian component to display employment history. The user can click on respective employment period to expand out contents for that particular employment and click again to collapse the content. This will neatly hides the chunky content.

**More About Me**
1. The primary navigation bar is similar to the previous page.
2. The secondary navigation bar allows users to goes directly to the section in the page that they are interested in. Author makes use of bootstrap navs components for this feature.
3. The skills section has two layers displayed in the form of carousels which user can toggle by the directional button. The first layer makes use bootstrap card components and the second layer bootstrap progress components. The images transform by a scale of 1.1 when hovered upon for additional interactivity with user. The carousel effect makes use of bootsstrap carousel components.
4. The Portfolios section makes use of the bootstrap card columns. The images will also transform by scale 1.1 when hovered over. A 'placeholder statement' will display itself when user hover over the respective portfolio because they are placeholders till author can further upload personal projects in the future. The 'placeholder statement' hover over effect is controlled by its CSS opacity value. User is able to open up the website of respective portfolios when click on the page links.
5. The interests & hobbies section makes use of bootstrap button type & popover components. User can find out more content for respective button when hover on.
6. A return to top icon is inserted at the bottom right so that user can return to top.

## 5. Surface

It’s the sum total of all the work and decisions we have made. It determines how does the product will look like, and choosing the right layout, typography, colors, …etc.
In Surface, we are dealing with _Visual Design(Sensory Design), It’s concerned about the visual appearance of content, controls, which gives a clue of what user can do, and how to interact with them. It should make things easier to understand, increase cognitive ability to absorb what users see on the screen.


**Home Page** 

**My Journey Page**

**More About Me**
