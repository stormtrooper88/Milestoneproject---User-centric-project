User-Centric Frontend Development project - The Code Institute – By Thomas Christian Butcher

The overview of the project "Full Stack Web Developer" is to create a website focused on demonstrating my skills as a Full Stack Web Developer. It aims to show to prospective employers the modules that I have undertaken and those that I am yet to complete. It shows my skills as a developer which include a carousel, NavBar and some information about myself with finally a Contact Me form if you wish to contact me. 

This is the link for the site: https://stormtrooper88.github.io/Milestoneproject---User-centric-project/

UX


(Link to my balsamiq mock up)[https://ibb.co/Q9V4rFG]


My goal in the design of this site was to make it user-friendly to future employers whilst informing them about myself, what I have accomplished so far and show-casing some of the skills I have learnt to date. 

 The welcome caption includes a short paragraph about myself with a "Contact Me" link that allows the user to go directly to the contact form should they wish to contact me. 
 
 The navbar at the top of the site allows the user to go straight to a certain part of the site rather than scrolling down.The UX for this is that the user may want to nagivate to a specific section. 
 
 Scrolling down the user will encounter an "about me" section which gives more details about my working life before coding and gestures to the user to keep scrolling down to find out what skills I have completed.
 
 Before viewing the skills section I wanted to show the user at least one of my skills. I had tried to set up a video but after trying to get it to work with the help of Code Institute and my mentor, I decided to include a carousel instead. This demonstrates a skill I learnt on my own with some help from Code Institute and my mentor. 
 
 After this the user will reach the "my skills" section where I have created a list of subjects I am undertaking at the Code Institute, under each subject is a line which aims to show the user how far along I am with that particular subject.
 
Below this the user will find a Contact Me form where they can contact me with their name, email and message. 

At the footer I have a link to my LinkedIn and GitHub accounts so that they can see my working experiences and my work so far since starting the course.

The greyscale colour scheme was chosen as it went well with my picture and created a easy transition, the red Code Institute picture stands out as it is red in background. 


Technologies
1.	HTML
2.	CSS
3.	Bootstrap Version 4.3.1
4.	How To Add a Video Background with HTML & CSS - https://www.youtube.com/watch?v=05ZHUuQVvJM
5.	Jquery

Features
This site uses the sticky navbar feature from bootstrap which does two things: firstly the nav-bar will follow the user down the page and secondly if you click on a certain section in the menu bar then you will directly be sent to the section you have clicked.

I found this tool from the git repository in hschafer2017 (https://github.com/Code-Institute-Solutions/StudentExampleProjectGradeFive) 

Features Left to Implement

I would like to have different languages in the menu bar as I speak French and Danish. 

I would like to fix the white space found between the intro message and the about me section. 

Technologies Used


1.	Bootstrap Version 4.3.1 https://getbootstrap.com/
2.	Jquery This was needed to make the carousel work
3.	HTML5 and CSS3 beginner tutorial 18 – background images{Part 2} https://www.youtube.com/watch?v=xNg2rh_h5v8
4.	How to add text over image - HTML and CSS https://www.youtube.com/watch?v=edCuCED3Zmo
5.	The pictures used in the carousel are from the following links: https://archsmarter.com/wp-content/uploads/2014/03/Learn-to-code1.jpg / https://i2.wp.com/s3-eu-west-1.amazonaws.com/sup46/wp-content/uploads/2019/02/01124431/code-institute-header-2-e1549023510442.png

Testing


I have tested the links at the top of the page to ensure that they direct the user to that specific location of the site that they wish to visit. 

I have tested the "contact me" button link to ensure that it takes the user to the contact form at the bottom of the page. 

I have gone to the carousel to test whether each picture is visible. I encountered a problem here as the pictures were all different sizes. This was fixed by creating a class and modifying it in CSS so the height matched each picture. 

I have gone to the "contact me" page and tried to submit without completing the name section. Upon clicking the send message button, a yellow mark pops up and states that the user must fill out the name section before being able to send the message. 
I have then filled in the name and left out the email. Upon clicking the send message button, a yellow mark pops up and states that the user must fill out the name section before being able to send the message. I have also tested inputting a random set of letters into the email section and then receive a notice stating that the @ is missing from the email section. I have tried simply entering the @ however I am told I must enter a part after the @. 
Once I have filled in both the name and email section of the form, I am told that my message won't send until a message has been written. 
With all the information filled in, the page reloads and the contact me form is blank again. 

I tried to follow the "Always Design for Mobile First" from : https://www.w3schools.com/css/css_rwd_mediaqueries.asp

I am currently having trouble with my video being loaded onto the page. This was meant as a video to welcome the user message and so should be seen regularly. – This has since been resolved but now the video isn’t playing. I have spoken to my mentor and though we tried to fix the issue with embedding the link in google documents it was not fixed and so I have decided to create a carousel with a fade. This however is not showing up on the site right now which was fixed by adding images to the carousel.  

I have had problems moving my nav bar to the middle which through watching videos on how to edit this I was able to change it. 

I cannot seem to place my links at the bottom and middle of the page. - I was able not able to fix this as of yet. 

The links I have in my footer are not linking with their respective sites. This was fixed after my mentor noticed that my links did not have https in them at the start of the link. 

I have had issues with the "about me" section and positioning it correctly. I have since placed it just above the carousel so that it can be clearly read and seen by the user. 

Deployment

This is the link for the site: https://stormtrooper88.github.io/Milestoneproject---User-centric-project/

I created the GitHub Pages site following the instructions laid out on the GitHub site. All the new commits are sent to the master branch and then edited into the live version of the site. 

I did this by entering my GitHub repository and entering the settings section. From here I went down to GitHub Pages section and choose the theme "minimal". From here I was then directed to the settings page of my repository and in the Github Pages section I found the link provided at the start of this README.nd


If you wish to run the code locally then you can clone my git repository and run it an editor such as Visual Studio Code. Simply past git clone https://github.com/stormtrooper88/Milestoneproject---User-centric-project into your terminal. Once you have done this you will want to stop the connection with the GitHub repository. You do this by typing into your termal git remote rm origin.


Credits

Content

All content is written by me and the background picture was taken by me. The other pictures are from the following links:  https://archsmarter.com/wp-content/uploads/2014/03/Learn-to-code1.jpg / https://i2.wp.com/s3-eu-west-1.amazonaws.com/sup46/wp-content/uploads/2019/02/01124431/code-institute-header-2-e1549023510442.png

Media

The photo used in this website is from my own pictures. The video was found on the following site: https://www.videvo.net/video/typing-in-the-dark-03/4478/ - This has since been removed.
The pictures used in the carousel are from the following links: https://archsmarter.com/wp-content/uploads/2014/03/Learn-to-code1.jpg / https://i2.wp.com/s3-eu-west-1.amazonaws.com/sup46/wp-content/uploads/2019/02/01124431/code-institute-header-2-e1549023510442.png

Acknowledgements

I would like to acknowledge the code institute, my mentor Dick and 
hschafer2017 (https://github.com/Code-Institute-Solutions/StudentExampleProjectGradeFive). They have all helped, guided and finally inspired me to create this website. 


