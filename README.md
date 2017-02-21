#Udacity Front-end Development Portfolio Project

###Sean Krinik, Submission.

Thank you for checking out my portfolio. A few quick notes on my project:

* I used Bootstrap 3 framework for grid system and other styling components.
* I have two stylesheets, each dependent on a media query in the head. One style sheet loads styling for screens of size *<768px* and another for screens *>767px*. I chose the breakpoint based off of content, and the *768px* mark is a common tablet size.
* I validated my CSS & HTML on w3validate - all green. 
* I checked the devtools network load process. There is one small issue that I encountered and posted in the forums. Some of the source images for the large screen HTML block under a media query get loaded (even though `display: none;` on that block), but not displayed once the stylesheet hits. For right now, there is no way around it. I didn't want to implement javascript since I'm not that advanced yet. 

Beyond that, I created a simple front page with my logo, links to my actual website, social media outlets and some of my photos. I plan on fully building my own photography portfolio once I finish the full FEND course and can add my own JS. 

Side note, grunt is pretty sweet. Thank you for inclduing grunt in the responsive images section. I used the `imagemagick` and a css minifier to create responsive sizes of all my images, and minified stylesheets. Super cool. Look forward to using grunt in the future. 
