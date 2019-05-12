# Exhibit Laois

Exhibit Laois is a website that aims to connect artists to their local communities. 
The website provides an online gallery for artists to display their work, it allows
local galleries to advertise their exhibitions and also acts an a news platform for
all things creative in the Laois community. Users of the site can see art, connect 
with artists to purchase artworks, get a listing of all gallereis and upcoming 
exhibitions, as well as stay up to date with the latest news. 

## UX

Exhbit Laois will be used by three designated users: artists, art galleries, and 
the general public in the Laois area. 

Artists: Galleries in Laois can be booked out for 2-3 years in advance for physical 
exhibitions, so an online space is needed to allow local artists to display their work
year round. On Exhibit Laois, each artist can host their own gallery without needing to
wait for physical space to do so. This can open up a more consistent revenue stream for 
these artists. 

User Story: "As an artist, I want to display and sell my work all year round. I need an online
platform to upload my work so that people can find and buy my work."

Galleries: Currently, most galleries have a webiste, but these are outdated, static and 
unresponsive. They are also infrequently updated due to a lack of technical expertise in 
these galleries. Exhibit Laois provides a central platform for local galleries to work together
by centralising their efforts to promote and support art locally. Galleries can advertise events, 
display their business and provide up to date news all in one place on Exhibit Laois. 

User Story: "As a Gallery, we need a reliable online space to promote our exhibitions and events, and 
to update art enthusiasts on local workshops. We need to be able to work together with oher galleries
and artists to develop art in the region". 

General Public: Currently, members of the Laois community who are interested in viewing and 
buying art have no platform where they can go to view artwork. The individual gallery sites 
do not act as online galleries, and while some individual artists do have their own studios or
social media pages, they are hard to find online. Exhibit Laois acts as a cenral hub through which
all artists can be easily found, their work viewed and the artist contact to buy work. Informaton
on exhibitions, art courses and upcoming events can all be easily located in one place.

User Story: "As an art enthusiast, I need somewhere I can go to see a wide variety of art for my own
entertainment and interest, but also to purchase for my home. I need to know about courses and workshops
for me and my kids, as well as stay informed about local exhibitions that I can support."

https://github.com/garylacumbre/exhibit-laois-website/tree/master/wireframes

## Features

Home Page - allows users to see a list of navigation options that meets their user requirements. It also
displays the latest news items most relevant to users. 

Artist Listings - By selection this option on the navigation menu, users can see a full list of all artists
on he site, including their name and kind of art they practice. Each artist is navigable to their own page 
from their photo on this page. 

Artist Gallery - This page allows user to view a bio of each artist, provides contact information and displays
an image gallery of the artists work along with the cost of each artwork.

Exhibitions - This page provides a list of all upcoming physical exhibitions, their locations and participating
artists

Gallery Listings - This page provides a list of physical galleries, their location and contact details

News Page - This page provides all latest news articles related to the site and its users.

Contact Page - this page allows users to submit feedback on the site.

### Features To Be Implemented 

1. The contact page needs to be connected to an email account and activated once JavaScript has been learned
2. The upcoming exhibitions table will be replaced with an interactive calendar using JavaScript
3. A subscription option will be added for future mailing list and newsletter, and a database of users will be maintained
4. using JS, Python & SQL
5. An e-commerce site will be developed where users can buy art directly through the site.

## Technologies

HTML - used to provide the basic structure and content of the website and to link pages within the site. 
Also used to import styles from external sites like Font Awesome, Google Fonts and Bootstrap
https://www.w3schools.com/html/

CSS - used to style all elements except the collapsible navbar
https://www.w3schools.com/Css/

Bootstrap - used only for the collapsible navbar in the mobile version of the site. 
https://getbootstrap.com

## Testing

#### General Public Users

User wants to see latest news - 
1. lands on Home page, scrolls down and sees latest news summary. Clicks on news item 
and it brought to the main news page. News page available form any page via nav bar
2. Lands on any page and uses News option on navbar to navigate to page

User wants to view upcoming exhibitions
1. From any page, including home user clicks on Exhibitions option in menu bar and navigates 
to the featured page

User wants to view list of artists
1. Artists listing page is available from any page via the nav menu. 

User wants to find a specific artist 
1. User can navigate to artists listings page from any page via the nav menu option 'Artists', scroll through
through artists and click on appropriate one
2. There is currently no direct link to any individual artist and users must navigate through the listsings page. 
Future iterations of the site can include a search bar to find individual artists if the site gets too big

User wants to find only one category of art
1. User can navigate to artists listings page from any page via the nav menu option 'Artists', scroll through
through artists and click on appropriate one
2. Future iterations of the site can include a category filter to find specific types of art if the site gets too big

User wants to give site feedback
1. From any page, the user clicks on the 'Contact' link in the nav menu and lands on the contact page. Cannot give
site feedback currently as the contact form is not connect to email. 

User wants to contact artist/ buy art 
1. User navigates to artsists listings, clicks on artist and then clicks on artists email to open email client.
2. User navigates to artist page and uses phone number listed there. 
3. Social media and other web links to artists own content can be added here when optained.

#### Artists

Artist wants to upload their work/ edit their page
1. Unable to upload directly via website at the moment. They will need to contact site admin to do this. 
2. Future iterations of the site will include an upload file button in the contacts form. 

#### Galleries

Gallery wants to include news items and event listing
1. Navigates to contact page via the nav menu on any page and input data into the contact form. 
2. This is not possible in the current iteration of the site pre-launch until the contact form is 
connect to an email account

#### Responsiveness

The site was built with a mobile-first approach. It uses block elements in the mobile version along with 
a collapsible navbar to save real estate. The nav bar is fixed and always scrolls with the page.

In the tablet version of the site, a two column layout is used instead of the block elements. Flexbox is used
to achieve this layout. The navbar remains fixed and available on scroll. Images resize as the page widens to
allow good visibility of images and a positive user experience. 

The laptop/ desktop version of the site uses a 3 column layout for images, with exception of the artists gallery 
which stays at two columns to allow the images to be studied more clearly. Future iterations of the site will laod
images in a pop-out gallery using JS. Font size of all text elements increases in the laptop/ desktop layouts and images 
are also resized using media queries. 

The widescreen version of the site is layed out the same as the desktop version but uses a narrower viewport width
for the main content of each page and uses larger font sizes and images to make use of the larger screen.

## Deployment

The site was deployed using GitHub Pages. The link to the site is:

https://garylacumbre.github.io/exhibit-laois/index.html

## Credits

#### Content

All text content on the site has been created by myself. No content was copied from other sources. 
Content is currently 'dummy content'. Real content will be added once the site gains some interactive features.

#### Images

All images on the News Page, Artists Listtings Page, Galleries Page, Artists Page and in the Latest News section on the Home page come from pexels and are
licensed for both commercial and non-commercial use. Images have been resized for the site using Adobe Photoshop. 
https://www.pexels.com/

The header image on the Home page comes from Adobe Stock. The artists profile operates under name: ledokol.ua and the image 
has been purchased under a commercial reuse licence. 
https://stock.adobe.com/ie/contributor/202074453/ledokol-ua?load_type=author&prev_url=detail

#### Acknowledgements

The idea for the site came from working in the Laois Library service where I was able to work with local artists
in setting up and running exhibitions in library art exhibition spaces. Once the site is deployed, these same artists 
will be able contribute their work. 



