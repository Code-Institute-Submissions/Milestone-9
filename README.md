# Damien Dempsey

### Code Institute / User-Centric Frontend Development Milestone Project

Tasked to create a static website combining knowledge from the first three modules in the Full Stack Web Development course with the Code Institute.

I am a huge fan of Damien Dempsey and I wanted to base my project on him. After using Damiens own official website https://damiendempsey.com i found it did not have enough information about him or his music. He wouldn't be a well known artist and so i felt his website should have more of this information, so I seen this as an oppurtunity to build a website to give people that knowledge of the great singer/songwriter that he is.
 
## UX

The goal of this website is to:

* Provide people with more of an understanding and information about the type of the artist Damien is.
* Create more traffic to this site but also through his social media platforms which can be found on every page.
* Build his brand awareness here in Ireland but also abroad.

#### User Stories

1. As a fan or potential fan/user, I want to check where Damiens next tour or gigs will be held.
2. As a fan or potential fan/user I want to see if Damien has social a media presence so I can follow him across social media platforms.
3. As a fan or potential fan/user I want to be able to check Damiens website on my mobile device as I do not own a laptop or desktop.
4. As a fan or potential fan/user i want to be able to listen to his music or watch videos on the site.
5. As a fan or potential fan/user I want to see a contact form so I can contact the artist or his to team to answer any questions that I cannot find the answer too on the website.

#### Design & Color Scheme

In the design of this website i used [Bootstrap 4](https://getbootstrap.com/) for my gallery layout & album cards. I then used some of my own custom HTML & CSS for the rest of the site.

The typography ('Roboto', sans-serif;) i chose is from [Google Fonts]{https://fonts.google.com/}.

In the Navbar i used the DAMIEN DEMPSEY logo which forms the basis as the back to "HOME" page which is commonly found amongst industry standards.

I used the shamrock emoji ☘️ on the [Homepage](https://jmurray1989.github.io/Milestone-1/index.html) to help emphasize that Damien is an Irish Singer | Songwriter.
 
After trying out a few different color schemes I decided on roughly the same color scheme from Damiens own official website. I feel it really makes the website pop when you have a dark background with different color overlays compared to the standard white background.

I used the standard grey setting within css for my buttons, album cards, header spaces & footer. I then used the color of #fafafa Color Hex Gray98 for the font to really make it stand out from the dark background. For my main images on each section of the website i decided to use black & white images to keep within the same color scheme as the overall project.

To help me choose my colour scheme is used [Adobe Color Wheel] {https://color.adobe.com/create}.

#### Wireframes

To build my wireframes i used [Balsamiq](https://balsamiq.com/) which is the software that the course briefly touches on. I found it quite easy to navigate and use so i did not look into other softwares.

All wireframes created for this project can be found [Here](https://github.com/Jmurray1989/Milestone-1/tree/master/wireframes)

Example below:-

![Desktop-Home](https://github.com/Jmurray1989/Milestone-1/blob/master/wireframes/desktop/Home.png?raw=true)

## Features

This is a summary of the features i have put in place but also the features i will add in the future.

###Navbar

All pages on the website follow the same principle with a fixed navbar, main image, a <h2>header and a footer with links to all of Damiens social media platforms.

Intuitive navigation fixed to the top of the the page that resizes for mobile devices with the hamburger icon. When pressed it expands to show the other navigable pages. On desktop i have used a hover function that will show the user which navpage they are highlighting and a class of active that will indentify to the user the current page they are on.

###Buttons

I have buttons on the homepage that will navigate you to other pages within in the website. I also have a button on the Tour page which will navigate you to Damiens own official tour link where you can purchase tickets for his upcoming gigs. [See Here]{https://damo.tourlink.to/shows}

###Cards

In the Music section of the website I have album cards which feature images of Damiens albums and a short write up about each. I also added buttons to this section which allow you to play each album through Spotify. See example [Here]{https://jmurray1989.github.io/Milestone-1/music.html}

###Video

The Video section of the website has many videos of Damien performing well known songs live and also includes some interviews.

###Gallery

The Gallery section has a range of images of Damien from live performances to appearing on television with special guests.

###Contact Us Form

The contact page features a form so visitors can contact Damiens management looking for more information that may not be available to them on the site.

###Footer

The footer is featured on all pages and contains clickable icons that will take you to each of Damiens social media platforms.

1. [Facebook]{https://www.facebook.com/damiendempseyofficial/}
2. [Twitter]{https://twitter.com/damodempsey}
3. [Instagram]{https://www.instagram.com/damiendempseymusic/}
4. [Youtube]{https://www.youtube.com/channel/UCa055fVTZiTHEI0tOZWfetg}
5. [Spotify]{https://open.spotify.com/artist/0bmF1w9eyJrY4CHyjpTQOW}
6. [Itunes]{https://music.apple.com/us/artist/damien-dempsey/67966386}


### Future Plans

Further development of this website will include a merchandise store for all of Damiens merchandise and a fan forum that fans of Damien can interact with each other and share stories about the singer/songwriter.

I also want to set-up the submit section on the form so that it will be fully operational to use.

Build a customer pre-loader, as videos and photos sometimes load slowly depending on network speeds.

I would also like to include a Blog that Damien himself could write to his fans informing them of whats going on in his world. Something which he is fond of doing on other social media platforms such as Facebook.


## Technologies Used

The Technologies I used to build this project are as follows,


- [JQuery](https://jquery.com)
    - The project uses **JQuery** to simplify DOM manipulation.


## Testing

In this section, you need to convince the assessor that you have conducted enough testing to legitimately believe that the site works well. Essentially, in this part you will want to go over all of your user stories from the UX section and ensure that they all work as intended, with the project providing an easy and straightforward way for the users to achieve their goals.

Whenever it is feasible, prefer to automate your tests, and if you've done so, provide a brief explanation of your approach, link to the test file(s) and explain how to run them.

For any scenarios that have not been automated, test the user stories manually and provide as much detail as is relevant. A particularly useful form for describing your testing process is via scenarios, such as:

1. Contact form:
    1. Go to the "Contact Us" page
    2. Try to submit the empty form and verify that an error message about the required fields appears
    3. Try to submit the form with an invalid email address and verify that a relevant error message appears
    4. Try to submit the form with all inputs valid and verify that a success message appears.

In addition, you should mention in this section how your project looks and works on different browsers and screen sizes.

You should also mention in this section any interesting bugs or problems you discovered during your testing, even if you haven't addressed them yet.

If this section grows too long, you may want to split it off into a separate file and link to it from here.

## Deployment

This section should describe the process you went through to deploy the project to a hosting platform (e.g. GitHub Pages or Heroku).

In particular, you should provide all details of the differences between the deployed version and the development version, if any, including:
- Different values for environment variables (Heroku Config Vars)?
- Different configuration files?
- Separate git branch?

In addition, if it is not obvious, you should also describe how to run your code locally.


## Credits

### Content
- The text for section Y was copied from the [Wikipedia article Z](https://en.wikipedia.org/wiki/Z)

### Media
- The photos used in this site were obtained from ...

### Acknowledgements

- I received inspiration for this project from X
