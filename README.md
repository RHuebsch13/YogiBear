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
As a visiting user, I would like to learn about why yoga is a good choice of exercise.
As a visiting user, I would like to see who would teach the classes.
As a visiting user, I would like to view the class times.
As a visiting user, I would like to learn about the different types of yoga offered.
As a visiting user, I would like to see what the studio is like.
As a visiting user, I would like to contact the studio.

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
[background img error]()

**corrected code with desired effect:**
[background img correction]()


- bug: hover feature not working
**orignal code:**
[bugged hover code](https://github.com/RHuebsch13/YogiBear/blob/main/readme%20docs/incorrect%20nav%20item.png?raw=true)

**corrected code with desired effect:**
[corrected hover code](https://github.com/RHuebsch13/YogiBear/blob/main/readme%20docs/correct%20nav%20item.png?raw=true)


- bug:Spaceing issue for class times on small screens

**corrected code with desired effect:**
[added code](https://github.com/RHuebsch13/YogiBear/blob/main/readme%20docs/media%20query.png?raw=true)



## After deployment
- Gallery should load when page loads;
 [gallery not loading](https://github.com/RHuebsch13/YogiBear/blob/main/readme%20docs/Screenshot%20(39).png?raw=true)

 - Assisted by Mentor Rohit Sharma, identified the file path was incorrect and the imae could not be located and that is why is wasn't loading. 
 

Code passed all validation tests on w3c validator and w3c css validator. Each html file was validated separately.
* [CSS Validation](https://github.com/RHuebsch13/YogiBear/blob/main/readme%20docs/cssval.png?raw=true)
* [Index.html](https://github.com/RHuebsch13/YogiBear/blob/main/readme%20docs/htmlindex.png?raw=true)
* [Yoga.html](https://github.com/RHuebsch13/YogiBear/blob/main/readme%20docs/htmlyoga.png?raw=true)
* [Contact.html](https://github.com/RHuebsch13/YogiBear/blob/main/readme%20docs/htmlcontact.png?raw=true)

# 5. Deployment
This project was developed using codeanywhere and VS code IDE, commited to Git and pushed to GitHub.
To deploy this page to GitHub pages from its repository:
1. Log into Github.
2. Select repository RHuebsch13/YogiBear.
3. Select 'settings'from the menu near the top of the page.
4. Go to Github page section.
5. Under source, select deploy from a branch.
6. Select main /root under branch and click save. 
7. Refresh the page, the website is now deployed. 
8. Link can be retrived from Github pages.

## How work on the project code within a local IDE i.e:. codeanywhere or VS code
To clone this project from Github:
1. Follow this link to the Project Github respository; [Here](https://github.com/RHuebsch13/YogiBear)
2. Under respository name; select 'clone or download'
3. Copy the clone URL fro the repository.
4. In your IDE open the terminl.
5. Change the working directory to the location where you want the cloned directory to be made
6. Type git clone and your URL from step 3 

# 6. Credits
## Code
* Template code for horzontal scroll gallery from W3schools.
* Template code for Contact form from W3schools.
* Code for adding videos from Youtube W3schools.
* Code for making an input required in form.
* Template code for structure of why yoga section from Love Running mini project - Code Institute.
* Template code for structure of why yoga class times section layout using divs from Love Running mini project - Code Institute.
* Code for hr line under welcome statement from Love Running mini project - Code Institute.
* Template code for navbar dropdown menu option for smaller screens Whiskey Drop project - Code Institute.
* Code for instuctor section, blockquotes from Whiskey Drop project - Code Institute.
* Template code for footer, including how to add a pdf download link and social media links to icons, from  Whiskey Drop project - Code Institute
* Assitance with bug detection and elimataion, general layout and appearance from mentor; Rohit Sharma.

## Content
* Why yoga info based on info found [here](https://www.ekhartyoga.com/articles/practice/7-great-reasons-to-start-practicing-yoga)
* Type of yoga section info based on info found [here](https://www.mindbodygreen.com/articles/the-11-major-types-of-yoga-explained-simply) and [here](https://www.medicalnewstoday.com/articles/what-is-hot-yoga#definition)

## Media 
### Background image sources:
* [Class time](https://pixabay.com/photos/lycaenidae-butterfly-banner-insects-3993275/)
* [Welcome](https://hotpodyoga.com/studios/newcastle/)
* [Types of yoga](https://www.mikkyrebelfit.com/workout/yoga-flow/)
* [Contact page](https://drchloetillman.com/home/yoga-banner-home/)

### Feature image sources:
* [Circle image why yoga](https://medium.com/@maxd4rnall/how-dmt-saved-me-from-nihilism-a4b3d895a27f)
* [Instructor images](https://mandayoga.co.uk/) and [here](https://omstars.com/yoga-drills-secrets-of-flexibility)
* Gallery images 
- https://commons.wikimedia.org/wiki/File:Yoga_practice_by_Varahi_Mystic_Yoga.jpg 
- https://omstars.com/live-class/be0380cb-eb89-4f76-9df8-b7f74e828c6b
- https://www.mother.ly/birth/labor-delivery/yoga-poses-labor/
- https://blog.davidlloyd.co.uk/new-to-group-exercise-the-best-tips-for-beginners/
- https://omstars.com/yin-for-happy-hips
- https://www.goayogashala.com/yoga/is-adjustment-and-alignment-necessary-for-yoga-practice/
- https://yogawithmaria.co.uk/product/four-mixed-ability-yoga-classes-on-monday-evening/
- https://omstars.com/movement-foundations-practices-flows-and-foundations
* Gallery videos
- https://www.youtube.com/watch?v=osCsxeCy5Q4
- https://www.youtube.com/watch?v=uQszEXaiJ1Y&t=1s
- https://www.youtube.com/watch?v=uyIj0pS38S0&t=84s



