# Yogi Bear Yoga Studio

# 1. UX
## User Research
Identified key user personas, ie. people who are into wellness and also people who want to started with their yoga journey. The website should be inclusive for experienced practitioners and beginners, helping those looking for specific yoga styles or classes. Therefore, attracting new customers and return customers.

## Project goals

This website has the purpose of delivering information to the user.
It seeks to create a platform for the Yogi bear yoga studios existing clients, as well as attracting new clients.
The user research shall be taken into account. There is beginner-friendly information for those wishing to find a yoga community; explainations on yoga health benefits and defintion of the classes offered at the studio. There is content for the experienced yogi; classes offered, which to avoid as they are beginner classes - Yin Yoga. The content also includes expecting mothers as there are classes for them too. While all content remains relevent for user personas seeking a community of both physical and emotional wellness.

## User Goals

The user will have access to information that relates to Yogi bear yoga studios.
This is a static-frontend development project that aims to be simple and responsive, with easily acessable content.
It aims to create a positive user experience. There is an emphasis on responsive design to ensure that the website is accessible on various devices, including desktops, tablets, and mobile phones as well as implementing a mobile-first approach to ensure acessibility for as many screens as possible.

## User Stories
As a visiting user, I would like to learn about why yoga is a good choice of exercise.
As a visiting user, I would like to see who would teach the classes.
As a visiting user, I would like to view the class times.
As a visiting user, I would like to learn about the different types of yoga offered.
As a visiting user, I would like to see what the studio is like.
As a visiting user, I would like to contact the studio.

## Design choices

The design aims to be visually appealing, with an interface that is calm. The color scheme reflects the serenity associated with yoga. GoodUI was comsulted to help the project follow common and consistent UI/UX conventions
High-quality images of the studio space, instructors, and yoga poses to convey the atmosphere and experience were added.
All design choices are made to create an easy to use and easy to naviagte website, that is visually pleasing for the user. 
The webpage has a traditional 3 page layout with continuity in terms of navbar, footer and content layout. All of these elements remain in the same place on each page as does the logo "Yogi Bear". This makes the site easy to learn, use and navigation for the user.

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

### Content
Engaging and informative content, including instructor profiles, class descriptions, and yoga philosophy to educate and attract users.Encouraging an inclusive community.

## Wireframes
Designed in mockflow, there are 3 wireframes for each pages. Providing planned layout and views on large screens, medium screens and small screens.

### index.html
![wireframe big screens](https://github.com/RHuebsch13/YogiBear/blob/main/readme%20docs/homew.png?raw=true)
![wireframe medium screens](https://github.com/RHuebsch13/YogiBear/blob/main/readme%20docs/homet.png?raw=true)
![wireframe small screens](https://github.com/RHuebsch13/YogiBear/blob/main/readme%20docs/homep.png?raw=true)

### yoga.html
![wireframe big screens](https://github.com/RHuebsch13/YogiBear/blob/main/readme%20docs/yogaw.png?raw=true)
![wireframe medium screens](https://github.com/RHuebsch13/YogiBear/blob/main/readme%20docs/yogat.png?raw=true)
![wireframe small screens](https://github.com/RHuebsch13/YogiBear/blob/main/readme%20docs/yogap.png?raw=true)

### contact.html
![wireframe big screens](https://github.com/RHuebsch13/YogiBear/blob/main/readme%20docs/contactw.png?raw=true)
![wireframe medium screens](https://github.com/RHuebsch13/YogiBear/blob/main/readme%20docs/contactt.png?raw=true)
![wireframe small screens](https://github.com/RHuebsch13/YogiBear/blob/main/readme%20docs/contactp.png?raw=true)

# 2. Features

## Existing Features

* Navbar dropdown: this only becomes visible when the screen real-estate is less than 768px, making the navbar easily accessible even on a smaller screen. Showing the ability to prioritizing content and features for smaller screens while maintaining a seamless user experience. The purpose of this is to ensure that the website will work for as many people as possible across as many different devices as possible. 
* InStructor information, with images of instructors.
* Scrollable videos + pictures of th studio and classes
* Download link for the class timetable, which is the download icon.
* Social media icons that act as hyperlinks.
* Benefits of yoga as a practice.
* Types of yoga information, helping the user identify the type of workout they are looking for.

## Left to Implement
* Responsive calender that allows the user to book a spot in the upcoming classes
* Log in facility so the user can keep track of their booked/upcoming classes.

# 3. Technology Used

HTML, CSS and Bootstrap frameworks

CSS styling is applied as:

line 7 navbar

line 20 index.html

- line 54 why yoga
- line 184 instructors

line 219 yoga.html
- line 244 yoga types
- line 271 classes 

line 328 contact.html
- line 366 form

line 443 footer

# 4. Testing
## Results

* A visiting user can learn about why yoga is a good choice of exercise on the home page, with well laid out information in point form that are easy to read and visually pleasing.
* A visiting user can see who would teach the classes by reading about our instructors on the home page and they can see their picture so they can be easily recognised when the user decides to try a class.
* A visiting user can view the class times by viewing the class timetable on the yoga page or downloading the pdf file that provides the same information.
* A visiting user can learn about the different types of yoga offered by reading the information on the yoga page about the types of yoga offered at the studio.
* A visiting user can see what the studio is like by viewing the gallery images and videos.
* A visiting user can contact the studio by viewing the contact page and using the contact details provide or by filling in the query form.


## Bug Problems

### 1. Centering `<hr>` Element
- Issue: element not centered in equal dimensions under the welcome message.
- Original Code:

![hr element error](https://github.com/RHuebsch13/YogiBear/blob/main/readme%20docs/centering-I.png?raw=true)

- Corrected Code with Desired Effect:

![hr element correct](https://github.com/RHuebsch13/YogiBear/blob/main/readme%20docs/centering-c.png?raw=true)


### 2. Welcome Banner Not Loading
- Issue: Welcome banner image not loading.
- Original Code:

![background img error](https://github.com/RHuebsch13/YogiBear/blob/main/readme%20docs/incorrect%20file%20path.png?raw=true)

- Corrected Code with Desired Effect:

![background img correction](https://github.com/RHuebsch13/YogiBear/blob/main/readme%20docs/correct%20file%20path.png?raw=true)


### 3. Hover Feature Not Working
- Issue: Hover feature not working.
- Original Code:

![bugged hover code](https://github.com/RHuebsch13/YogiBear/blob/main/readme%20docs/incorrect%20nav%20item.png?raw=true)

- Corrected Code with Desired Effect:

![corrected hover code](https://github.com/RHuebsch13/YogiBear/blob/main/readme%20docs/correct%20nav%20item.png?raw=true)

### 4. Spacing Issue for Class Times on Small Screens
- Issue: Spacing issue bug for class times on small screens.
- Corrected Code with Desired Effect:

![added code](https://github.com/RHuebsch13/YogiBear/blob/main/readme%20docs/media%20query.png?raw=true)



## After Deployment

### 1. Gallery Not Loading
- Issue: Gallery should load when the page loads.
![gallery not loading](https://github.com/RHuebsch13/YogiBear/blob/main/readme%20docs/Screenshot%20(39).png?raw=true)
- Resolution: Assisted by Mentor Rohit Sharma, identified the file path was incorrect, and the image could not be located, which is why it wasn't loading.

## Validation Tests
- Code passed all validation tests on w3c validator and w3c CSS validator.
  - [CSS Validation](https://github.com/RHuebsch13/YogiBear/blob/main/readme%20docs/cssval.png?raw=true)
  - [Index.html](https://github.com/RHuebsch13/YogiBear/blob/main/readme%20docs/htmlindex.png?raw=true)
  - [Yoga.html](https://github.com/RHuebsch13/YogiBear/blob/main/readme%20docs/htmlyoga.png?raw=true)
  - [Contact.html](https://github.com/RHuebsch13/YogiBear/blob/main/readme%20docs/htmlcontact.png?raw=true)

## Lighthouse Testing
- Meta descriptions were added.
  - [Download PDF mobile home](https://github.com/RHuebsch13/YogiBear/blob/main/hmoe%20page%20mobile.pdf)
    
    Meta description added.
  - [Download PDF home page](https://github.com/RHuebsch13/YogiBear/blob/main/home%20page.pdf)
  - [Download PDF mobile gallery](https://github.com/RHuebsch13/YogiBear/blob/main/gallery%20mobile.pdf)
  - [Download PDF gallery page](https://github.com/RHuebsch13/YogiBear/blob/main/gallery%20page%20desk..pdf)
  - [Download PDF mobile contact](https://github.com/RHuebsch13/YogiBear/blob/main/contact%20mobile.pdf)
  - [Download PDF contact page](https://github.com/RHuebsch13/YogiBear/blob/main/contact%20desk..pdf)


No broken links found using [W3C Link Checker](https://validator.w3.org/checklink).

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

## How work on the project code within a local IDE; codeanywhere or VS code
To clone this project from Github:
1. Follow this link to the Project Github respository; [here](https://github.com/RHuebsch13/YogiBear)
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
### Background Image Sources:
* [Class time](https://pixabay.com/photos/lycaenidae-butterfly-banner-insects-3993275/)
* [Welcome](https://hotpodyoga.com/studios/newcastle/)
* [Types of yoga](https://www.mikkyrebelfit.com/workout/yoga-flow/)
* [Contact page](https://drchloetillman.com/home/yoga-banner-home/)

### Feature Image Sources:
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



