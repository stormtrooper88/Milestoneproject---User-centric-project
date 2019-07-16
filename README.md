User-Centric Frontend Development project - Code Institute – By Thomas Christian Butcher

The overview of the project "Full Stack Web Developer" is to create a website focused on demonstrating my skills as a Full Stack Web Developer. It aims to show to prospective employers the courses I am undertaking, those I have completed, some information about myself and finally a contact form if you wish to contact me. 


UX

Use this section to provide insight into your UX process, focusing on who this website is for, what it is that they want to achieve and how your project is the best way to help them achieve these things.

In particular, as part of this section we recommend that you provide a list of User Stories, with the following general structure:

As a user type, I want to perform an action, so that I can achieve a goal.
This section is also where you would share links to any wireframes, mockups, diagrams etc. that you created as part of the design process. These files should themselves either be included in the project itself (in an separate directory), or just hosted elsewhere online and can be in any format that is viewable inside the browser.

My goal in the design of this site was to make it user-friendly to future employers whilst informing them about myself and what I have accomplished so far. The idea is to give the reader an outlook on who I am and what I have accomplished. The welcome caption with a contact me link allows the user to go directly to the contact form. The navbar allows the user to go through the site and return to parts they may not have seen. The next section is about me with a video containing someone typing to the right / left of the text about myself. The next section demonstrates what I have done so far regarding coding. Below this you will find a contact me form where you can complete it and I will receive the message. At the footer I have a link to my LinkedIn account. The greyscale colour scheme was chosen as it went well with my picture and created a silk look to the work. 

You can find my wireframes in my GitHub repository as I changed them throughout the project. 

Technologies
1.	HTML
2.	CSS
3.	Bootstrap Version 4.3.1
4.	https://www.youtube.com/watch?v=05ZHUuQVvJM

Features
This site uses the sticky navbar feature from bootstrap which does two things: firstly the nav-bar will follow the user down the page and secondly if you click on a certain section then you will directed to it immediately. 

Features Left to Implement

I would like to have different languages in the menu bar as I speak French and Danish. 

Technologies Used

In this section, you should mention all of the languages, frameworks, libraries, and any other tools that you have used to construct this project. For each, provide its name, a link to its official site and a short sentence of why it was used.
1.	Bootstrap Version 4.3.1 https://getbootstrap.com/
2.	How To Add a Video Background with HTML & CSS https://www.youtube.com/watch?v=05ZHUuQVvJM
3.	HTML5 and CSS3 beginner tutorial 18 – background images{Part 2} https://www.youtube.com/watch?v=xNg2rh_h5v8
4.	How to add text over image - HTML and CSS https://www.youtube.com/watch?v=edCuCED3Zmo

Testing

In this section, you need to convince the assessor that you have conducted enough testing to legitimately believe that the site works well. Essentially, in this part you will want to go over all of your user stories from the UX section and ensure that they all work as intended, with the project providing an easy and straightforward way for the users to achieve their goals.

Whenever it is feasible, prefer to automate your tests, and if you've done so, provide a brief explanation of your approach, link to the test file(s) and explain how to run them.

For any scenarios that have not been automated, test the user stories manually and provide as much detail as is relevant. A particularly useful form for describing your testing process is via scenarios, such as:

Contact form:
Go to the "Contact Us" page
Try to submit the empty form and verify that an error message about the required fields appears
Try to submit the form with an invalid email address and verify that a relevant error message appears
Try to submit the form with all inputs valid and verify that a success message appears.
In addition, you should mention in this section how your project looks and works on different browsers and screen sizes.

I have tested the links at the top of the page to ensure that they direct the user to that specific section of the site. 

I have tested the "contact me" button link to ensure that it takes the user to the contact form at the bottom of the page. 

I have gone to the "contact me" page and tried to submit without completing the name section. Upon clicking the send message button, a yellow mark pops up and states that the user must fill out the name section before being able to send the message. 
I have then filled in the name and left out the email. Upon clicking the send message button, a yellow mark pops up and states that the user must fill out the name section before being able to send the message. I have also tested inputting a random set of letters into the email section and then receive a notice stating that the @ is missing from the email section. I have tried simply entering the @ however I am told I must enter a part after the @. 
Once I have filled in both the name and email section of the form, I am told that my message won't send until a message has been written. 
With all the information filled in, the page reloads and the contact me form is blank again. 

You should also mention in this section any interesting bugs or problems you discovered during your testing, even if you haven't addressed them yet.

I am currently having trouble with my video being loaded onto the page. This is video is a welcome message and so should be seen regularly. – This has since been resolved but now the video isn’t playing. I have spoken to my mentor and though we tried to fix the issue with embedding the link in google documents it was not fixed and so I have decided to create a carousel with a fade. This however is not showing up on the site right now. 

I have had problems moving my nav bar to the middle which through watching videos on how to edit this I was able to change it. (insert link)
I cannot seem to place my footer at the bottom and middle of the page. 

The links I have in my footer are not linking with their respective sites. This was fixed after noticing that my links did not have https in them. 

If this section grows too long, you may want to split it off into a separate file and link to it from here.

Deployment

This section should describe the process you went through to deploy the project to a hosting platform (e.g. GitHub Pages or Heroku).

In particular, you should provide all details of the differences between the deployed version and the development version, if any, including:

Different values for environment variables (Heroku Config Vars)?
Different configuration files?
Separate git branch?
In addition, if it is not obvious, you should also describe how to run your code locally.

Credits

Content

All content is written by and the picture was taken by me. 

Media

The photo used in this website is from my own pictures. The video was found on the following site: https://www.videvo.net/video/typing-in-the-dark-03/4478/ - This has since been removed.
The pictures used in the carousel are from the following links: https://archsmarter.com/wp-content/uploads/2014/03/Learn-to-code1.jpg / https://i2.wp.com/s3-eu-west-1.amazonaws.com/sup46/wp-content/uploads/2019/02/01124431/code-institute-header-2-e1549023510442.png

Acknowledgements

I would like to acknowledge the code institute mini-project and 
hschafer2017 (https://github.com/Code-Institute-Solutions/StudentExampleProjectGradeFive)

I would also like to acknowledge https://www.videvo.net/video/typing-in-the-dark-03/4478/ for providing the free video footage of someone typing. 
