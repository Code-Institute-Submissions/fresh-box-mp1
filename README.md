# Front End Project Module One

## FreshBox

A website providing a place for users to order fresh ingredients and recipe ideas on a subscription-based service.

FreshBox are environmentally conscious and only use distrubuters who use sustainable farming methods. Reduced use of carbon emissions
througout the process by using local farms and produce centers. Food is fresh when delivered and never frozen. Also work
with top end restaurants in the UK.

## UX

FreshBox is aimed at young business professionals who don't have the time to shop for every meal
due to work, gym and social life commitments. They want to increase their orders through simplistic and intuitive
design, making it easy for the user to order their first trial box without having to search for it and the
website.

#### User 1:

User has discovered this website through adveritising, and is looking to use a food delivery service. They are aware of other services, but has come across this site. They are a desktop user.

- This will be achieved by adding the box contents to the landing page. They are shown a bright, colourful display of healthy food, as well as the company name and slogan.

- They see the first paragraph and is drawn to the word FREE, as the design makes it appear bold to the user. This is also next to the word 'here' in a different colour, which leads them straight to the order page, encouraging orders.

![User 1 screenshot of index page](/screenshots/user-1-screenshot.png)

This is the first page the user sees. It shows the business goals, their environment concern and a brief description of the food boxes they provide. AS they are a desktop user, they are able to see brief details of the box, and if they click onto a box they will be taken to the boxes page. 

#### User 2:

- Mobile User. A returning user who hasn't already ordered and wants to explore the box contents from the landing page again before they make a decision on whether they want to order or not.

- The landing page shows a short description of the box contents via a more info button. The button only displays on the lower resolution screens. They can then be taken to the boxes page where more information on the box contents is given. They can then navigate to the order now page and easily fill out the form. On each page there is a link to get to the boxes page, or the order now page.

![User 2 screenshot of index page boxes](/screenshots/user-2-screenshot.png)

As the majority of users are using mobiles or tablets to view webpages, it is important to provide ways in which they can view the same content as desktop users. When a resolution size reaches a certain point. The More Info button will show them the box info. This can be deactivated to regain real estate. 

#### User 3:

- Has already ordered, but wishes to speak to customer service to discuss the contents of the box.

- The other box types can be found on the box’s webpage, as well as short description on the index page.

![User 2 screenshot of index page boxes](/screenshots/user-2-screenshot.png)

This is the footer at the bottom of each webpage. The email address located within the text is a link which will automatically open the users email app, with the company email already entered in the 'To:' field. Office hours are also provided so that the user is aware of when they might expect a reply, or when is best to email the customer service team.

### Wireframe designs

Wireframe designs have been added to show the initial ideas and designs on the FreshBox website.

It includes notes on each page to explain why design decisions where made and justifcation on layouts.

Some design choices were not kept or altered as in practice they did not encourage intuitive, user friendly experiences.

#### Design Change 1

##### Wireframe

![Wireframe of boxes webpage](/wireframes/wireframe-boxes-mobile1.png)

##### Live website

![Screenshot of boxes page](/screenshots/live-boxes-layout.png)

The design was changed due maintaining the layout throughout the website. This was to keep that 2 x 2 layout of the images shown on the index.html page, making it easier to recognise each box to the users.

#### Design Change 2

##### Wireframe

![Screenshot of index page](/wireframes/wireframe-index.png)

##### Live website

![Screenshot of index page](/screenshots/index-html.png)

The initial wireframe contained no hero image. In practice this didn't look appealing and made the initial landing page quite bland. I added different hero images to each of the pages to both make them more interesting, but to also to enable users to recognise what page they were on.

## Features

- Logo will feature throughout the website to encourage brand recognition, located at the top left of each page.

- Form to allow the user to order a sample box of their choice. Links to this form is located on each page to increase the likelyhood os users getting there.

- Choice will be of 4 different boxes. Images of fresh fruit and veg, nuts, healthy food etc, depending on the box choice.

- Each field in the order page will be mandatory to reduce the amount of incorrect data being gathered.

- Information will appear when a user hovers over the the box images to view more information.

- For mobile and tablet users a button will be visable to press and view the same information.

- Collapsing Navigation Bar, reacting to different screen resolutions.

- Links to social media accounts.

### Features Left to Implement

- Add new boxes when new boxes if and when new boxes are created.

- Log in / Sign up system to create.

- Modal to notify the customer that their order has been requested, along with a link within that modal to take the user back to the homepage.

## Technologies Used

- HTML5 - Used for the base coding of the website
- CSS3 - Used to style the webpages and their content
- GitHub - Used to save the word within a repository
- GitPod - Used to write and implement the coding
- Bootstrap - Grid layouts and form used. Also used to assist with the responsive design
- Balsamiq - Used to create wire frame designs in the planning stage.

## Testing

A number of tests were completed throughout the design and build process. Below are the details of the testing conducted and completed:

| Test                      | How                                                                                | Result                                                                                          | Fix                                                                                                  |
| ------------------------- | ---------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------- |
| index.html links          | Click each link displayed on page                                                  | Some links worked, those located in the content did not                                         | Located incorrect links and set correct href. Retested and worked                                    |
| boxes.html links          | Click each link displayed on page                                                  | All links worked and redirected correctly. However, links were missing from the boxes images    | Anchor tags were added to each box image to take the user to the boxes page                          |
| order-now.html links      | Click each link displayed on page                                                  | All links worked correctly                                                                      | N/A                                                                                                  |
| Responsive design         | Using the chrome developer tool to change resolution of the page                   | Content moved and responded as expected, no overlapping or loss of content                      | N/A                                                                                                  |
| More Info button          | Changing screen resolution size                                                    | Content was correctly hidden on resolution change, card was still visable on larger resolution  | Added .card rule to @media query to correctly hide content                                           |
| Hiding content            | Change resolution of the viewport                                                  | Hero text box was incorrectly staying the same size on smaller resolution                       | Checked the @media css style and saw that a '}' was missing. Added '}' to code, this fixed the issue |
| Form submission           | Enter details into order-now form and click 'Order Now' button                     | Data was not sent correctly and the webpage was only refreshed                                  | Added code into form tag to gather and display correct data                                          |
| Form submission 2         | Enter details into order-now form and click 'Order Now' button                     | Data was sent correctly, however not on a new webpage                                           | Added code to open new webpage when 'Order Now' button is clicked                                    |
| Alt Text on images        | Search each 'alt=' and ensure they correctly describe the image                    | Several alt text was incorrect                                                                  | Change the alt text to describe the image                                                            |
| Live Website              | Set up through GitHub Pages                                                        | Images were not displaying correctly                                                            | File location was set incorrectly. '/' was removed                                                   |
| Page loading time         | Clear cache and reload index.html                                                  | Page took a quite a long time to load the hero image                                            | Resize original hero image to reduce impact on load time                                             |
| Page loading time         | Clear cache and reload boxes.html                                                  | Page took a quite a long time to load the hero image                                            | Resize original hero image to reduce impact on load time                                             |
| Page loading time         | Clear cache and reload order-now.html                                              | Page loading time was low                                                                       | N/A                                                                                                  |
| HTML Validator            | Copy code into HTML editor provided by https://validator.w3.org/#validate_by_input | Error in index.html - <summary> not allowed inside <body>                                       | Removed <summary> tag                                                                                |
| HTML Validator            | Copy code into HTML editor provided by https://validator.w3.org/#validate_by_input | Error in index.html - The aria-controls attribute must point to an element in the same document | Incorrect code was added to the button. This was removed                                             |
| HTML Validator            | Copy code into HTML editor provided by https://validator.w3.org/#validate_by_input | No errors found in the boxes.html                                                               | N/A                                                                                                  |
| HTML Validator            | Copy code into HTML editor provided by https://validator.w3.org/#validate_by_input | No errors found in order-now.html                                                               | N/A                                                                                                  |
| Boxes image on index.html | Change screen resolution to view how images behave                                 | Images appeared as a row of 3 and 1                                                             | Changed @media in the CSS to compensate for resolution change                                        |
| README.md screenshots     | Save and upload changed to GitHub repository                                       | Screenshots were not appearing as expected                                                      | The images were not uploaded in the update. Updated the repository with the images                   |

## Deployment

Live website deployed through GitHub Pages. URL https://side-on.github.io/fresh-box-mp1/.

### Create clone of the repository

1. On GitHub, go to this depository. https://github.com/Side-On/fresh-box-mp1.

2. Above the list of files, click the download button on the green 'Code' button.

3. To clone with HTTPS, click the clipboard button next to the URL.

4. Open Git Bash.

5. Change the current working directory to the location where you want the cloned directory.

6. Type git clone, and then paste the URL you copied earlier.

7. Press Enter to create your local clone.

## Acknowledgements:

I researched a number of websites to create and add features into FreshBox. Below is a list with an example of why they were used.

- https://w3schools.com - For code reference.
- https://stackoverflow.com - code reference.
- https://dillinger.io/ - used to edit the README.md file.
- https://pexels.com - used for hero images and food images.
- https://flaticon.com - used for the icons found on index.html and boxes.html. Link also displayed on the footer a requested by the website.
- https://hellofresh.co.uk - inspiration for the FreshBox business idea.
- https://docs.github.com/en/free-pro-team@latest/github/creating-cloning-and-archiving-repositories/cloning-a-repository Info on cloning the repository
- https://getbootstrap.com/ - used for some layouts and code taken for form and navigation bar. CSS was changed from the original. 

### Code used:

- Bootstrap - https://getbootstrap.com/docs/4.5/components/navbar/ used when creating the Navigation Bar which appears throughout the website.
- Bootstrap - https://getbootstrap.com/docs/4.5/components/forms/ used when creating the order form located in the 'Order-Now' page.


All of the content, description was written by myself. Upon reasearching the name, after the website was complete, I realised there were a lot of live sites with very similar names, this was not known to me at the start of the project.

Within the layout of the code, after the <a> and <img>, the closing '>' appears independantly on the next line, this is due to the formatting created through beautifying the code. I tried to work around it by manually putting it in, however it still changed when beautifying the rest of the code.