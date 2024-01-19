# Yogi Bear Yoga Studio

# 1. UX

## Project goals

This website has the purpose of delivering information to the user.
It seeks to create a platform for the Yogi bear yoga studios existing clients, as well as attracting new clients.

## User Goals

The user will have access to information that relates to Yogi bear yoga studios.
This is a static-frontend development project that aims to be simple and responsive, with easily acessable content.
It aims to create a positive user experience.

## User Stories


## Design choices

All design choices are made to create an easy to use and easy to naviagte website, that is visually pleasing for the user. 
The webpage has a traditional layout in terms of navbar, footer and content. All of these elements remain in the same place on each page as does the logo "Yogi Bear". This makes for easy site navigation.

### Fonts
Google font Roboto has been used as the primary font. The sans-serif fallback is included as a generic category in case 'Roboto' is not available on the user's device or browser. Both fonts were selected as the are easy to read and match the aesthetic of the page.

### Icons
Icons were used in the footer for the social media links as well as the download class timetable link. These icons were chosen because they are familiar and easily recognisable so the user can decipher the meaning and use of the icon. 

### Colours
The constant colours seen throughtout the pages are a dark grey and off-white, as well as a bright violet colour that is used for hover features.
The simple grey and white combination make the content easy to see and provides a simple but effective finish. The bright violet is drawn from the welcome banner picture and carried thorugh to bring a sense of continuity. The other background images choosen compliment these colours.

### Styling
headings are bigger in size so they are easily identified by the user. These heading are also relative to the content. All three page make use of divs and sections to provide cohensive layout. Bootstrap is on;y used in places and makes use of the concept on grid layout.
### Backgrounds
Several images have been used for backgrounds, the text has then been modified to stand out aganist the background, using colour and opacity. As well as images, solid colour background were used to break up the pages, this is done on the home and the contact page. 
## wireframes
Designed in mockflow, shows for views for big screens such as laptops and computers, smaller screens like tablets and the smallest screens being cellphones.
index.html
![wireframe big screens](https://github.com/RHuebsch13/YogiBear/blob/main/readme%20docs/homew.png?raw=true)
![wireframe medium screens](https://github.com/RHuebsch13/YogiBear/blob/main/readme%20docs/homet.png?raw=true)
![wireframe small screens](https://github.com/RHuebsch13/YogiBear/blob/main/readme%20docs/homep.png?raw=true)

yoga.html
![wireframe big screens](https://github.com/RHuebsch13/YogiBear/blob/main/readme%20docs/yogaw.png?raw=true)
![wireframe medium screens](https://github.com/RHuebsch13/YogiBear/blob/main/readme%20docs/yogat.png?raw=true)
![wireframe small screens](https://github.com/RHuebsch13/YogiBear/blob/main/readme%20docs/yogap.png?raw=true)

contact.html
![wireframe big screens](https://github.com/RHuebsch13/YogiBear/blob/main/readme%20docs/contactw.png?raw=true)
![wireframe medium screens](https://github.com/RHuebsch13/YogiBear/blob/main/readme%20docs/contactt.png?raw=true)
![wireframe small screens](https://github.com/RHuebsch13/YogiBear/blob/main/readme%20docs/contactp.png?raw=true)

# 2. Features

## Existing features

Navbar dropdown: this only becomes visual when the screen real estate is less than 768px, making the navbar easily accessible even on a smaller screen. The purpose of this is to ensure that the website will work for as many people as possible across as many different devices as possible. scrollable videos + pictures, not a real yoga studio, etc

Download link for the class timetable, which is the download icon.

Benefits of yoga as practice.

Types of yog ainformation, helping the user identify the type of workout they are looking for.

## left to implement
Responsive calender that allows the user to book a spot in the upcoming classes
log in facility so the user keep track of their booked/upcoming classes.

# 3. Technology Used

HTML, CSS and Bootstrap frameworks
CSS styling is applied as:
line 7 navbar

line 20 index.html
-line 54 why yoga 
-line 184 instructors

line 219 yoga.html
-line 244 yoga types
-line 271 classes 

line 328 contact.html
-line 366 form

line 443 footer

# 4. Testing
## Bug Problems
- Working with hr element, trying to center it in equal dimensions under the welcome message;

**orignal code:**

.container-fluid.welcome-container {

    display: flex;

    justify-content: center;

    align-items: center;
}


.block-divider {

    width: 70%;

    height: 2px;

    border: 0;

    padding: 0 5%;

    background-color: #fff;

}

**corrected code with desired effect:**

.container-fluid.welcome-container {

    display: flex;

    justify-content: center;

    align-items: center;
}


.block-divider {

    width: 70%;

    height: 2px;

    border: 0;

    margin: 5% auto;

    background-color: #fff;
}

- Welcome banner not loading

**orignal code:**

background: url('assets/images/middle.jpg') no-repeat center center;

**corrected code with desired effect:**

background: url('../images/home.jpg') no-repeat center center fixed;

- targetting the nav
**orignal code:**
.navbar-nav .nav-item a.nav-link:hover {
    color: #A020F0;
}
Code passed all validation tests on w3c validator and w3c css validator. Each html file was validated separately.
![css validation](https://github.com/RHuebsch13/YogiBear/blob/main/readme%20docs/cssval.png?raw=true)
![html validation contact.html](https://github.com/RHuebsch13/YogiBear/blob/main/readme%20docs/htmlcontact.png?raw=true)
![html validation index.html](https://github.com/RHuebsch13/YogiBear/blob/main/readme%20docs/htmlindex.png?raw=true)
![html validation yoga.html](https://github.com/RHuebsch13/YogiBear/blob/main/readme%20docs/htmlyoga.png?raw=true)
# 5. Deployment

# 6. Credits

gallery, form we3schools
Love Running, (structure of why yoga section, class times section) Code Institute
Whiskey Drop, (navbar dropdown menu option for smaller screeens, downloadble pdf, footer structure) Code Institute
why choose yoga (for info used on page) https://www.ekhartyoga.com/articles/practice/7-great-reasons-to-start-practicing-yoga
