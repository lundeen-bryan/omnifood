# Jonas-Schmedtmann-HTML-CSS

### Link To Tutorial

See the [Build Responsive Real World Websites with HTML5 and CSS3]( https://www.udemy.com/course/design-and-develop-a-killer-website-with-html5-and-css3/) on Udemy.

---

### Table of Contents

Brief table of stuff.
- [Description](#description)
- [Timetable](#timetable)
- [Tutorial Comments](#video-notes-and-comments)
- [References](#references)
- [Project Status](#project-status)
- [Tutorial Author Info](#author-info)

---

## Description

This is going to be my full notes and commentary on the course by Jonas. Essentially this is one big course on HTML and CSS, Jonas teaches slower than most instructors which makes it easy to keep up but maybe take a little longer than others to finish this one project. The course is only about 12 hours long compared to others like Brad Traversy which is 21-hours long. 

#### Technologies

- HTML5
- CSS3
- some JS

[Back To The Top](#jonas-schmedtmann-html-css)

---

## Timetable

Time | Comments
-----|---------
11.30 | Initial commit
11.52 | Created git init and added several files. I found that he has a pretty interesting 
11.58 | One of the interesting things he created was pointing to a responsive web tool here [Responsive Grid System](http://www.responsivegridsystem.com/)
12.12 | started with centering the text
12.34 | Moved the omnifoods folder to downloads and moving items via Gyula
12.41 | Set a bg image and centered it and opaque
12.44 | I changed the html font size to em value instead of pixes since it's setting percentages of font sizes throughout the project. 
12.49 | Turned off my Intellisense by default it was causing errors
13.10 | I have no buttons the way Jonas shows, and there are 542 questions in this lecture so I probably won't find the answer as to why I don't have a button the way he does.
13.47 | Added buttons and transition effects then 
13.48 | Commit and take a lunch break
16.53 | Back from chores and adding images to site img folder
18.20 | Finished header section i.e. the landing page
18.22 | Commit 22 changes
18.29 | Using after pseudo-class, fluid grid, use new icons in columns
19.15 | Had a problem matching the format and prettier was giving errors, removed xtra div fixed it
12/06 | Sunday
08.48 | Converting entire project to BEM
10.34 | adding up styles for BEM(B) and non-BEM(NB) NB=1+10+1+10+10+10+10+11+24+24+1+20+20+20+20+20+20=232, B=1+1+10+10+10+10+20+20+10+10+20+20+20+20+20+20=222. So I saved about 1 class worth of specificity values. 
11.09 | re-write features section in BEM style. 
12.28 | Decided it was too labor-intensive to convert this whole project to BEM. Reverted to previous commit.
18.19 | On vid 43 he uses h2:after but that should have double colons as stated in the documentation here: [after](https://developer.mozilla.org/en-US/docs/Web/CSS/::after).
18.47 | The icons can't be sized like a font so I have to read the documentation on how to resize them in [github](https://github.com/ionic-team/ionicons). 
18.59 | Commit and push
17.40 | Plan to add images and zoom-in transition using CSS per lesson 43
18.13 | Sebastian answered my criticism on Vid 41 extremely well and gave good suggestions.
19.08 | When adding the photos you need to start with the right class
19.24 | I really had to change the vw for the navbar and the meal photos section 
20.09 | Changed width of a few elements in long-copy so that it was in viewport width
20.11 | Commit: Added images and zoom transition for meal section
12/08 | Tuesday


## Video Notes and Comments

### On Video # 41

The following was my actual feedback to the course mods and teaching assistants. 

> I wasted a lot of time on the section that jonas talks about using the ion icons set. His instructions are out dated. The first clue is when I notice there is no download button for the icon set. 

> The real solution is to go to the github page (find the link in the upper right corner of the ionicons homepage) and look under the heading "Installation" where it says to insert the reference to the js file at the bottom of your page right above the closing html tag. Then when you're on the main page and you find an icon you want then copy the css code and insert it into the spot you want to see the icon. 

> I think it's fair that if Jonas sold almost 50,000 students on this course then he should be able to make reasonable efforts to update it or make notes for students. When you have over 500 comments, it's hard to find the comment that speaks about ion icons. Udemy is a huge platform and it doesn't seem to have an easy way to categorize comments other than per video. As a top seller, you should recommend that Udemy categorize comments as well, or allow tags so that if I tagged something as "ionicon" then people with that problem could find it. Also the assistant who answers questions for Jonas doesn't fully answer questions in a way that allows future students to find the answer. He'll often say, "check your other msg" or "upload your code to codepen" then that's it.... the conversation dies at that point. You are making more work for yourself because you have to answer the same question multiple times. 

> Anyway, I hope Jonas gets this feedback. I'm serious and I'm going to remember this thread when it is time to post my review of the course. 

> Thanks.

Sebastian answered this question with a lot of empathy and a very thorough technical explanation. I sincerely believe he wanted me to feel I was getting the best answer and I felt it was a good answer that was well thought out. 

### On Video #43 ion-icons is a class so don't use "icon-big" class 

Jonas says to use the ".icon-big" class but it doesn't work with the new ion-icon set. If you read the instructions on GitHub for ion-icons you will see that it is already an attribute if you install it per the instructions so then you have to change it's properties as if it's was an element called ion-icon. 



[Back To The Top](#jonas-schmedtmann-html-css)

---

## References

[click and type] 

[Back To The Top](#jonas-schmedtmann-html-css)

---

## Project Status

The current status of this project is in development. 

[Back To The Top](#jonas-schmedtmann-html-css)

---

## Author Info

- YouTube - [Jonas Schmedtmann](https://www.youtube.com/channel/UCNsU-y15AwmU2Q8QTQJG1jw)

[Back To The Top](#jonas-schmedtmann-html-css)

