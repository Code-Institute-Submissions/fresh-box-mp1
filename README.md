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

### Wireframe design

Designs have been added to show the initial ideas and designs on the FreshBox website. It includes notes on each page to explain why design decisions where made. Some design choices were not kept or altered as they were not best practice when considering user eperience.

#### User 1:

> Discovered this website using a search engine, has heard of similar companies providing a similar service.
> I want to see what types of boxes are on offer and I want to learn about the business.

> This will be achieved by adding the box contents to the landing page. It will show the boxes on offer and that the
> first box is free.

#### User 2:

> Returning user who hasn't already ordered. I want to order my first box.

> This can be done through the landing page as well.

#### User 3:

> Has already ordered, but wishes to explore what other types of boxes are available to order.

> The other box types can be found on the box’s webpage, as well as sort description on the index page.

### Features

- Logo will feature throughout the website to encourage brand recognition, located at the top left of each page.

- Form to allow the user to order a sample box of their choice. Links to this form is located on each page to increase the likelyhood os users getting there.

- Choice will be of 4 different boxes. Images of fresh fruit and veg, nuts, healthy food etc, depending on the box choice.

- Each field in the order page will be mandatory to reduce the amount of incorrect data being gathered.

- Information will appear when a user hovers over the the boxes images to view more information.

- For mobile and tablet users a button will be visable to press and view the same information.

- Collapsing Navigation Bar, reacting to different screen resolutions.

- Links to social media accounts.

### Features Left to Implement

- Create basket and ordering system allowing the user to chose how many boxes they want to receive each week.

- Add new boxes when new boxes if and when new boxes are created.

- Log in / Sign up system to create.

- Modal to notify the customer that their order has been requested.

### Technologies Used

- HTML5 - Used for the base coding of the website
- CSS3 - Used to style the webpages and their content
- GitHub - Used to save the word within a repository
- GitPod - Used to write and implement the coding
- Bootstrap - Grid layouts and form used. Also used to assist with the responsive design
- Balsamiq - Used to create wire frame designs in the planning stage.

## Testing

A number of tests were completed throughout the design and build process. Below are the details of the testing conducted and completed:

| Test                 | How                                                              | Result                                                                                         | Fix                                                                                                  |
| -------------------- | ---------------------------------------------------------------- | ---------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------- |
| index.html links     | Click each link displayed on page                                | Some links worked, those located in the content did not                                        | Located incorrect links and set correct href. Retested and worked                                    |
| boxes.html links     | Click each link displayed on page                                | All links worked and redirected correctly. However, links were missing from the boxes images   | Anchor tags were added to each box image to take the user to the boxes page                          |
| order-now.html links | Click each link displayed on page                                | All links worked correctly                                                                     | N/A                                                                                                  |
| Responsive design    | Using the chrome developer tool to change resolution of the page | Content moved and responded as expected, no overlapping or loss of content                     | N/A                                                                                                  |
| More Info button     | Changing screen resolution size                                  | Content was correctly hidden on resolution change, card was still visable on larger resolution | Added .card rule to @media query to correctly hide content                                           |
| Hiding content       | Change resolution of the viewport                                | Hero text box was incorrectly staying the same size on smaller resolution                      | Checked the @media css style and saw that a '}' was missing. Added '}' to code, this fixed the issue |
| Form submission      | Enter details into order-now form and click 'Order Now' button   | Data was not sent correctly and the webpage was only refreshed                                 | Added code into form tag to gather and display correct data                                          |

## Deployment

## Acknowledgements:

I researched a number of websites to create and add features into FreshBox. Below is a list with an example of why they were used.

- https://w3schools.com - For code reference.
- https://stackoverflow.com - code reference.
- https://dillinger.io/ - used to edit the README.md file.
- https://pexels.com - used for hero images and food images.
- https://flaticon.com - used for the icons found on index.html and boxes.html. Link also displayed on the footer a requested by the website.
- https://hellofresh.co.uk - inspiration for the FreshBox business idea.

All of the content was written by myself.
