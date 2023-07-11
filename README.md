![BB Gym](/documentation/bb_gym.jpeg)

# Beefs & Babe Gym


 ## About BB Gym

Beefs & Babe Gym (BB Gym) website is for users to locate and get a 'feel' for the gym. 
New and frequent visiotrs can find information and contact / location details of the gym with ease.
The site will show the space, some equipment and give a friendly atmosphere with emphasis on 'serious training'.

The website can be accessed via this [link](https://hewers89.github.io/BB_Gym/)

## User Stories /  Goals

### First Time Visitor Goals:
* As a first time visitor I would want to see with ease what the websites purpose is. In this instance, showing a gym with title and highlighting it is a gym.

* Additionally, I need to easily navigate my way around the website to access the details i need. Access to social media and contact details.

* Furthermore, I would want the site to show the organisation is trustworthly and worth visiting for a membership.


### Returning Visitor Goals

* As a returning visitor i would want to have access to the gym contact details.

* I may want to see if i have been showcased in the show room photography.

* Also have access to additional information about the organisation through their socials.


### Company Goals.

* For new visitors to contact the organisation and sign up for a membership.

* For new/current members to access and sign up to classes.

* For new/current members to access and sign up to PT sessions. 



## Features

Navigation
The NavBar is situated at the top of the screen.
The BB is the link to the home page. 
Showroom links to pictures of the gm enviroment 
Contact links to Address in text form and google maps. Also a contact us form. 

It has a simple design and is easy to use, the links have hover effect and change color. 

The Navbar is responsive and adjusts to fit the screen.


## Footer

The footer contains all social media links for the gym which open in a new tab.

## Home Page
The home page has a simpke design with a main hero image. 
It is clean and enhances that this is a gym webpage.

## Show Room
The show room has pictures showing equipment and the public exercising, with and without PT. 
Its highlights the friendly enviroment and welcomes potential members to visit.

## Contact

The contact page has simple layout easy to use for contact in person by visiting or via a contact form complete with submit button.

## Classes

This page shows the current gym schedule in an easy to read layout.

## Design

### Colour scheme

![Color pallet](documentation/rgb_146_140_140.jpeg)

![Color Pallet](documentation/rgb_173_53_10.jpeg)

![Color Pallet](documentation/rgb_251_250_250.jpeg)

* Black was used with the opacity of 0.8 in footers and nav bar.
* Orange/red was used throughout due to being gender neutral and clean against the background. It is also used on the BB 'logo' to help it stand out.
* Off white was used for links. 
* Grey is a neutral balance between the red black and off white. 


## Wireframes

[Homepage Laptop](documentation/wireframes/homescreen_laptop.png)

[Homepage ipad | phone](documentation/wireframes/homescreen.png)

[Showroom Laptop](documentation/wireframes/showroom_laptop.png)

[Showroom ipad | phone](documentation/wireframes/showroom.png)

[Contact Laptop](documentation/wireframes/contact_laptop.png)

[Contact ipad | phone](documentation/wireframes/contact.png)


## Deployment

The site was deployed to GitHub.

Follow the steps to deploy:

* In the Github repository, open the settings tab
* From the drop-dowm menu, selct **Main** branch and then **Save**

## Local Deployment
To make a local copy of this project, you can clone it. In your IDE, type the following command:
git clone https://github.com/HEWERS89/BB_Gym.git



## Testing

### Light House

* Home [Desktop](documentation/frontpage_laptop.pdf) |
[Mobile](documentation/frontpage_mobile.pdf) 

* Showroom [Desktop](documentation/showroom_laptop.pdf)|
[Mobile](documentation/showroom_mobile.pdf)

* Contact [Desktop](documentation/contact_laptop.pdf) | 
[Mobile](documentation/contact_mobile.pdf)

* Classes [Desktop](documentation/classes_laptop.pdf)|
[Mobile](documentation/classes_laptop.pdf)



### Chrome Responsive Viewer

* [Home page](documentation/responsive_frontpage.png)
* [Showroom](documentation/responsive_showroom.png)
* [Contact page](documentation/responsive_contactpage.png)
* [Classes](documentation/responsive_classespage.png)

### Manual Testing


| Feature | Action | Expected result | Tested | Passed | Comments |
| --- | --- | --- | --- | --- | --- |
| Navbar | | | | | |
| BB | Click on the "Home" link | The user is redirected to the main page | Yes | Yes | - |
| Home | Click on the "Home" link | The user is redirected to the main page | Yes | Yes | - |
| Showroom | Click on the "Showroom" link | The user is redirected to the gallery page | Yes | Yes | - |
| Classes | Click on the "Classes" link | The user is redirected to the main classes page | Yes | Yes | - |
| Contact | Click on the "Contact" link | The user is redirected to the contact page | Yes | Yes | - |
| Footer | | | | | |
| Instagram icon in the footer | Click on the Instagram icon | The user is redirected to the Instagram page | Yes | Yes | - |
| Facebook icon in the footer | Click on the Facebook icon | The user is redirected to the Facebook page | Yes | Yes | - |
| Location icon | Click on the Location icon | The user is redirected to the Contact us page | Yes | Yes | - |
| Home page | | | | | |
| "Contact Us" button in banner on each page | Click on the "Contact Us" button | The user is redirected to the contact page | Yes | Yes | - |
| Contact page | | | | | |
| Name input | Enter Name | Name is entered| Yes | Yes | If user doesn't enter name, the error message appears |
| Email input | Enter the email | The email is entered | Yes | Yes | If user doesn't enter the email, the error message appears. If user enters not valid email, the error message appears |
| Message input | Enter message | Message is entered | Yes | Yes | If user doesn't enter message, the error message appears.
| "Submit" button | Click on the "Submit" button | The user is redirected to the response page | Yes | Yes | - |
| Response page | | | | | |
| Response message | The user will be automatically redirected to the home page after 10 seconds | The user is redirected to the home page | Yes | Yes | - |

### Compatability

[Google Chrome](https;//google.co.uk)  Manually tested on google chrome for functionality , apperance and responsivness. All features passed.

[Internet Explorer](https://www.microsoft.com/en-gb/download/internet-explorer.aspx) Manually tested on google chrome for functionality , apperance and responsivness. All features passed.

## Bugs

* There was an empty line above the footer due to bootstrap. I used devtools to access and target ul aplied no margin via !important.

* The footer was not sticking to the bottom of the page with less content, I added a body and main rule to ensure the footer stick to the bottom of the page.

* The form would not center so i added a class name and targeted this with flexbox and justified content. 

* GoogleMaps and the Address when at 900px would not seperate, therefore I targeted it with media query. 


## Languages
 [HTML](https://www.w3schools.com/html/) for the foundation of the site.

 [CSS](https://developer.mozilla.org/en-US/docs/Web/CSS) used to add style and layout.

 [Flexbox](https://developer.mozilla.org/en-US/docs/Learn/CSS/CSS_layout/Flexbox) to arrange items and make them responsive.

 [Balsamiq](https://balsamiq.com/) used to make wireframes.

 [VScode](https://code.visualstudio.com/) used as my tool for writing and editing code.

 [Github](https://github.com/) used to host the code of the website.

 [Gitpod](https://www.gitpod.io/) an open source CDE

## Media

 #### Gym Images
 
 [Hero](https://jonathanholmes.co.uk/6-of-the-best-gyms-in-london/) Hand holding barbell 

 [Gym Equipment](https://www.cgtrader.com/) Treadmills and spin bikes in gym with orange and black theme

 [Gym Theory](https://pinnaclecontracting.com/)

 [Gym Racked](https://ny.racked.com/) Group of women during an exercise class

 [Weights](https://fitness-superstore.co.uk/weights) Barbells on stand within an orange gym

 [Orange Gym](https://orangegym.at) Man on treadmill in gym with orange and black gym

 [Exercise](https://\Fitness-superstore.co.uk) Man exercising using gym equipment 

 [Trainer](https://growthopsdigital.com.au) Woman exercising with a personal trainer

 [Pt 1](https://mygym.co.uk) Personal trainer smilling with people exercising in background

 [Pt](https://nacams.org) Woman deadlifting with personal trainer

 ## Credits

 [Code](https://www.w3schools.com) Used to understand flexbox and box models

 [Flex box Kevin powell](https://www.youtube.com/watch?v=vQAvjof1oe4) Videos on flexbox

 [Bootstrap](https://getbootstrap.com/) 

 [Fontawesome](https://fontawesome.com/)

 [Map](https://www.google.com/maps) 

 [Color Palette generator](https://convertingcolors.com/)

 [Chrome Responsive Viewer](https://chrome.google.com/webstore/detail/responsive-viewer/inmopeiepgfljkpkidclfgbgbmfcennb)

 [Light House](https://developer.chrome.com/docs/lighthouse/overview/)




 ## Acknowledgments 

[Code institute](https://learn.codeinstitute.net/) Mentor Juliia Konovalova 