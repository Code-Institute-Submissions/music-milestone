# Ukulele Website
This is a website about the ukulele, a popular Hawaiian musical instrument. The website contains a brief history of the ukulele, an introduction to the sounds of the ukulele and a booking facility where users can book online ukulele classes. The site content helps beginners to learn more about the ukulele and allows site owners to showcase interesting information about the instrument and encourage users to take their online classes.
<br><br>

## UX <br><br>
### Who is this website for?
* Enthusiasts - People who want to learn about the ukulele and have very little knowledge of it 
* Students- People who wish to take ukulele classes online
* Teachers - Ukulele players who wish to give classes online and build their business<br><br>

### User Stories
1. As a ukulele enthusiast, I want to find information about the ukulele so that I can build my knowledge. 
- This user can find information in the 'About' and 'Play' sections of the website.

2. As a ukulele student, I want to hear some of the basic notes so that I can prepare for my first class. 
- This user can listen to the audio in the 'Play' section of the website.

3. As a ukulele student, I want to book my next online class so that I can attend it and improve my skills. 
- This user can book their next class in the 'Booking' section of the website.

4. As a ukulele teacher, I want to have a simple booking system available on my website so that I can display my class schedule easily and share it with my current students and prospective students who come across my website. 
- This user (as a site owner) can use the booking system in the 'Booking' section of the website.

5. As a ukulele teacher, I want to showcase my teaching skills by presenting interesting information on my website so that I can demonstrate my expertise and attract new students to my classes. 
- This user (as a site owner) can add their content and news to the 'Home', 'About' and 'Play' sections of the website.<br><br>

### Wireframes
The original wireframes for this project are located in the 'wireframe' folder:
* Desktop layout (wireframe/ukulele.pdf)
* Mobile layout (wireframe/mobile-wireframe.pdf)
<br><br>

## Features

### Existing Features
**Navbar** - There are two version of the navbar (one for desktop and one for mobile) that were created using Bootstrap. The consist navigation panel on each page allows users to navigate easily through the site. 

**CTA Links** - There are buttons at the end of the 'About', 'Home' and 'Play' pages that encourage users to quickly navigate to other pages on the site that they are likely to wish to visit once they've scrolled through the current page.

**Booking Form** - There is a booking form on the 'Booking' page that allows users to input their name and email address and to book a class - this is currently static. 

**Musical Ukulele** - The 'Play' page has a basic table with audio embedded that the user can click to hear individual notes.
<br><br>

## Features Left to Implement
**Booking Form** - I'd like to build on the booking form so that the user instantly receives confirmation of their booking on screen, as well as an automated email to say they've signed up. I'd also like to extend the calendar view so that users can page through it to the following weeks and book classes well in advance if they wish.

**Live Class Page**  - I'd like to add a page where the online classes are shown when the teacher goes live. Students could log in to this page and access their classes and schedule easily. The teacher could also opt to store class videos and tutorials here for revision.

**Interactive Musical Ukulele** - I'd like to add more features to the 'Play' page so that users could 'play' the ukulele more easily and have more choice of notes. This section could also display demos and have a searchable songbook.
<br><br>

## Technologies Used
The following languages and frameworks were used to build this project:

**HTML** -
This project uses HTML to structure the pages and website.

**CSS** -
This project uses CSS to style each of the website pages.

**Bootstrap** -
The project uses Bootstrap to improve navigation within the site. 
https://getbootstrap.com/

**Font Awesome** -
The project uses Font Awesome to present icons throughout the site.
https://fontawesome.com/    
<br>


## Testing

### Manual Testing
This project has been tested manually on desktop and mobile in Chrome and Firefox. 

### Automated Testing
All HTML pages have been tested using the HTML validator

The CSS file has been tested using https://validator.w3.org/ and the results file is in testing/W3C-results.htm

All images are under 5MB to ensure they load quickly. 

**User Stories**

1. *As a ukulele enthusiast, I want to find information about the ukulele so that I can build my knowledge.*<br><br> 
**Test and Result**
* Open the 'Home' page.
* Select 'About' in the navbar. 
* 'About' page displays. 
* Scroll to end of page. 
* Select 'Play the Ukulele'.
* 'Play' page displays. 
* Click/Tap different notes to check audio files are working.

- Elements in the 'About' section display vertically rather than horizontally in Firefox - this has not been addressed but can be fixed by updating CSS styles for those elements.

2. *As a ukulele student, I want to hear some of the basic notes so that I can prepare for my first class.* <br><br> 

**Test and Result**
* Open the 'Home' page.
* Select 'Play' in the menu. 
* 'Play' page displays. 
* Click/Tap different notes to check audio files are working.

- The audio buttons are much smaller on mobile but work well. Button borders are visible in Firefox but overall it displays the same. 

3. *As a ukulele student, I want to book my next online class so that I can attend it and improve my skills.*<br><br>  

**Test and Result**
* Open the 'Home' page.
* Select 'Booking' in the menu. 
* 'Booking' page displays. 
* Enter name.
* Enter email address.
* Select different class slots to ensure they are clickable. 

- Class slots are clickable but don't trigger a response - this is as designed. 


4. *As a ukulele teacher, I want to have a simple booking system available on my website so that I can display class schedule easily and share it with my current students and prospective students who come across my website.* <br><br> 

**Test and Result**
*Note:* This test is to ensure the schedule is viewable as it can't be edited by a site owner yet.
* Open the 'Home' page.
* Select 'Booking' in the menu. 
* 'Booking' page displays and weekly schedule is presented.

- Class slots are presented clearly for the week. Schedule displays horizontally on desktop and vertically for mobile.


5. *As a ukulele teacher, I want to showcase my teaching skills by presenting interesting information on my website so that I can demonstrate my expertise and attract new students to my classes.* <br><br> 

**Test and Result**<br><br> 
*Note:* This test is to ensure the content is viewable as it can't be edited by a site owner yet.
* Open the 'Home' page.
* Select 'About' in the menu. 
* 'About' page displays.
* Select 'Play' in the menu. 
* 'Play' page displays.

- Content is presented using different media formats and scales for mobile version. Content was overlapping on mobile but this has been fixed.<br><br> 


## Deployment
This project has been deployed to GitHub Pages.

Once the wireframes were finalised, the project was built and indiviual pages were tested at different stages throughout the project. The first deployment to GitHub Pages took place when the full website structure was in place and the GitHub Page link has been updated for testing when key additions were made.<br><br> 


## Credits

### Content
* About - The text for the 'About' page was copied from this Wikipedia article: https://en.wikipedia.org/wiki/Ukulele
* Home - The quote from Tracy Chapman was copied from brainyquote.com

### Media
* All of the photos used in this site were downloaded from unsplash.com from the following contributors:<br>
**about-bg.jpg** - Photo by Julian Myles on Unsplash<br>
**uke-about.jpg** - Photo by Johannes Weber on Unsplash<br>
**uke-bg.jpg** - Photo by Joints Creative on Unsplash<br>
**uke-home.jpg** - Photo by Minh Trần on Unsplash<br>

* The audio in this site was recorded specifically for this project.<br><br>

### Acknowledgements
I received inspiration for this project from ultimateguitar.com and the course material I've covered to date, and I used stackoverflow.com and w3schools.com for help with troubleshooting during the project. 