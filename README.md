This is a read.me file for my UVM CML Web Page Project

Project Description: This project attempted to redesign my current website which is a WordPress website and is located at http://www.createmakelearn.org.  I used the concepts learned in this class to  code individual webpages that would allow me to migrate from Wordpress to HTML files that I maintain.   

I used the knowledge and skills I gained from the 12 modules of EDCI 5003 including HTML, CSS, Javascript.  

I used two different AI tools to reinforce the skills I needed to achieve this project.  I used Claude AI to get some ideas for new design elements and I used Git-hub co Pilot to fill gaps in  the skills I needed to implement and understand the various elements needed.  I also enjoyed experimenting with different design ideas.   Because I was experimenting with new design ideas and new knowledge, the coding is not always consistent across the pages.  As I progress through coding each page, I often came up with new approaches, and did not go back to the previous pages to change the code to make them all the same.  It's sort of like building a house room by room and as you learn new skills, the later rooms have more features and the craftsmanship improves.  In the case of coding, you can go back and change the earlier pages, and if I decide to migrate my website, I will definitely step back and implement more consistent approaches throughout.  

Here are how I demonstrated each criteria:

HTML Structure & Semantics:  I created 5 pages using the correct HTML structure and semantic HTML documents.  I think that my code could have been cleaner, but one of the reason it was not as tidy as it could be was that I over-documented in some places.  You will see extra documentation when a feature was new to me and I wanted to remember how it worked or at least document my understanding of some of the features that AI helped me learn.  But as I got more confident in the DOM structure and use of classes, I stopped documenting what mimght be obvious to more seasoned observors. 


CSS Styling & Layout:  I was proud that I was able to use a style sheet most of the time.  
I was especially proud that I learned to make grids with flexbox and other display classes.  I noticed that there were times the last item in a list of 'cards'  spanned the whole page as I resized the browser and was able to fix that on the TEAM page, but it is still happening on some pages as I resize the browser.  I need to do some more troubleshooting on those pages. 

One thing I would do if I had the time was to clean up the style sheet and look for redundant and conflicting style class.  This happened because I tried different layouts on different pages to learn new skills.  As I got to the end of the project I became more confident with the styles and had ideas of how I could try a new feature one one page and apply it to a page I had worked on previously.  This caused some redundancies that I started to remove (i.e. hero class) but didn't get a chance to go through the whole site and tighten up my use of classes (especially reoccuring card classes).  


JavaScript Functionality.  I used Javascript functionality in a few different areas, and added some listeners. I especially used it to navigate between different segments and pages.  I also had fun learning to use it in new wagys on the Connect page where I learned how tomake some of the code for the form hidden and then appear when you click on Send me a Message.  I also used some Javascript in the NavBar. I became more confident in the use of variables. At one point I learned there were benefits to storing my brand colors in variables, and wished I had done this in earlier pages.  I look forward to stepping back and taking some of the concepts I learned in the latter part of this project and going back and applying them to the pages I did in the earlier part of the project. 
I was very proud of the solution I implemented to make it so the navbar updates only needed to happen in one place and I would 'fetch' the navbar html page each time the page loaded. 


Form & Validation	The Connect page offers 4 different ways to connect with me and included a few different forms.  I coded the Form to send a message  directly from the Connect page. That form includes a Prevent and  an Alert since it does not really work and is for demo purposes only.  There are  also two embedded forms (one from Follow It subscription service) that I was able to bring into its own HTML page. That required more than cut and paste the embed code. I had to make modifications to the form that demonstrated understanding of how forms, classes, and javacript worked.  I tried to make it work like the Send Message form and have it appear in the same page (hidden until I clicked on it). However it didn't quite look right so  I reverted to putting the  code for it on its own site.   I also embedded the Google Form I currently use for my mailing list on a page. 


Data Handling (JSON /)  
I was successful in using the Fetch command to get the info from the Navbar all in one page so I didn't have to make changes on each page one at a time. I thought this was cool and liked the way it functioned.   
I tried to go one step further and use Json and that did not work well.  I  only  tried Json on one page.   You can seem my Json attempt on the page cml_pd.html, but I do not think it is working therefore I did not change the other pages to  use the navbar.jason method. 

I tried very hard to  implement the Json version of the navbar and although I did not write the functions myself, I worked through the functions and how they worked together and was able to document each line to show that I understood it.  
 I did include a backup method where I fetch the navbar from a file called navbar.html if the script throws an error. I believe that the cml_pd.html Json implementation is catching the error and reverting back to my original method of fetching the navbar code from its own HTML page and rebuilding the navbar upon loading the page. 
  To test this theory, I made a slight changes in the navbar.jason file to see if the navbar reflected that change and since that change is  not appearing on the cml_PD.html navbar, I'm guessing it is throwing an error and is reverting back to the old method in the Catch function. 
  Therefore,I  kept this original navbar method on all the other pages because I know that is working and does use the FETCH command to build the navbar from the navbar.html file instead of the navbar.jason file. 


Project Completeness.  I did a deep dive into this project. The more I did the more I wanted to do and I might have bitten off more than I had time for but I am  excited to continue working on it  and possibly migrating my WordPress Website to a CPanel hosting situation.  The project might have felt more complete if I had not had mission creep as I became more confident. 

Code Quality & Comments - I learned so much doing this project and tried to comment new learning. But the more confidence I gained the less I commented functionality that were becoming familiar to me.  However I still think I overcommented for the purpose of showing that I understood the code segments that AI helped me implement.   I do need to clean up the code more, but when I used some of the 'clean code' features, it made some of my comments disappear. 


Creativity & Originality  I really liked some of the ideas of using svg code instead of images and creating effects with SVG class.  That was one of my favorite creative features of this page (i.e. border radius for the pictures of the Team Page that made the square photos into circles and the svg design for the icons for the Connect page  and the colors of the segments or cards changing using the child elements).  I used AI to get ideas and show me how to implement features I liked.  

User Experience (UX)	I tink the user experience works because of the branding color and also because of the consistent navbar.   One thing  I don't like is  that the BlOG link goes to an external site (Blogger), so I will need to tweak the blog with some new navigational elements so it integrates better.   

Presentation & Deployment	Here is the link to the project on GitHub 
https://github.com/ldelabru/cml_web

and the link to the publshed project 

Your site is live at https://ldelabru.github.io/cml_web/









