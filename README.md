<img src="https://codeinstitute.s3.amazonaws.com/fullstack/ci_logo_small.png" style="margin: 0;">

Welcome ksngo,

This is the Code Institute student template for Gitpod. We have preinstalled all of the tools you need to get started. You can safely delete this README.md file, or change it for your own project.

## Gitpod Reminders

To run a frontend (HTML, CSS, Javascript only) application in Gitpod, in the terminal, type:

`python3 -m http.server`

A blue button should appear to click: *Expose*,

Another blue button should appear to click: *Open Browser*.

To run a backend Python file, type `python3 app.py`, if your Python file is named `app.py` of course.

A blue button should appear to click: *Expose*,

Another blue button should appear to click: *Open Browser*.

In Gitpod you have superuser security privileges by default. Therefore you do not need to use the `sudo` (superuser do) command in the bash terminal in any of the backend lessons.

## Updates Since The Instructional Video

We continually tweak and adjust this template to help give you the best experience. Here are the updates since the original video was made:

**February 2020:** The initialisation files now _do not_ auto-delete. They will remain in your project. You can safely ignore them. They just make sure that your workspace is configured correctly each time you open it. It will also prevent the Gitpod configuration popup from appearing.

**December 2019:** Added Eventyret's Bootstrap 4 extension. Type `!bscdn` in a HTML file to add the Bootstrap boilerplate. Check out the <a href="https://github.com/Eventyret/vscode-bcdn" target="_blank">README.md file at the official repo</a> for more options.

--------

Happy coding!

1mar20:switched to visual studio code....


## Strategy

Reason for WebSite: To showcase my resume to hiring companies on a webpage. The webpage shall contain the relevant information (e.g. experience, contact info, skills, portfolios, interests) for hiring companies to know more about me.

## Scope

**Home Page**

1. Basic introduction of author
2. Contact information
3. Links to other two pages

**My Journey Page**
1. Line graph showing major milestones (e.g. education & employment status)
2. Employment history and elaborations
3. Links to other two pages

**More About Me**
1. Skills
2. Portfolios and any certificates
3. Interests and hobbies
4. Links to other two pages

## Structure

**Home Page**

1. Contains navigation bar to navigate between other pages
2. Contains Hero Image as background. Author basic info will display above this background image.
3. Contains text-box to display contact info and a form beside it for contact & remarks population.
4. Contains footer for social platform links.

**My Journey Page**
1. Contains navigation bar to navigate between other pages.
2. Contains background image and Line graphs are placed above.
3. Contains card components for Employment details.
4. Contains footer for social platform links.

**More About Me**
1. Contains navigation bar to navigate between other pages.
2. Contains secondary bar to navigate within this page.
3. Contains background image.
4. Contains section for skills information.
5. Contains section for portfolios information.
6. Contains section for interests and hobbies information.
7. Contains footer for social platform links.

## Skeleton

**Home Page**
1. Navigation bar is mobile friendly and will align vertically for screen width 500px and below. The links are manually tested to ensure the links bring user to correct page or location.
2. Basic Info is display by an animation keyframes with animation duration of 3sec. Basic Info will sit above the Hero Image.
3. Contact Information are displayed in flex and row direction. Contact entry by users are created as forms. Further backend work is required for the form to eventually pass the entries to the author. The contact information is mobile friendly and will align in columns for screen width 750px and below.
4. The footer bar's social platform links are currently broken till author's respective social platform links are ready. On hover over the icons, the font size will enlarge for additional interactivity.
**My Journey Page**
1. The navigation bar is mobile friendly and will collapse to hamburger for smaller screen. Author makes use of bootstrap NavBar components for this feature.
2. The background image is displayed under the entire HTML's body element.
3. The months shown along the line graph when hovered over will appear in a coloured bubble. Viewer can click on the months to popover further information on that month. Author makes use of bootstrap popover component for this feature.
4. At the bottom of the page,  author makes use of bootstrap collapse accordian component to display employment history. The user can click on respective employment period to expand out contents for that particular employment and click again to collapse the content. This will neatly hides the chunky content.
**More About Me**
1. The primary navigation bar is similar to the previous page.
2. The secondary navigation bar allows users to goes directly to the section in the page that they are interested in. Author makes use of bootstrap navs components for this feature.
3. The skills section has two layers displayed in the form of carousels which user can toggle by the directional button. The first layer makes use bootstrap card components and the second layer bootstrap progress components. The images transform by a scale of 1.1 when hovered upon for additional interactivity with user. The carousel effect makes use of bootsstrap carousel components.
4. The Portfolios section makes use of the bootstrap card columns. The images will also transform by scale 1.1 when hovered over. A 'placeholder statement' will display itself when user hover over the respective portfolio because they are placeholders till author can further upload personal projects in the future. The 'placeholder statement' hover over effect is controlled by its CSS opacity value. User is able to open up the website of respective portfolios when click on the shown page links.
5. The interests & hobbies section makes use of bootstrap button type & popover components. User can find out more content for respective button when click on.
6. An return to top icon is inserted at the bottom right so that user can return to top.

## Surface

**Home Page**
**My Journey Page**
**More About Me**
