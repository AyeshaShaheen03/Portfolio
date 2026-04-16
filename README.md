# Personal Website 🚀🔥


For run project on local host:
gulp build, npm run build
gulp serve   (main command)
then it will run on (localhost:3000)
After changes:
If you change anything in any file, then push files from git bash, vercel will not update the changes, because i am using _site folder for vercel, vercel is just reading the -site folder, index.html file where all files data is saved, so after changes in any file, go to vs code termonal run command: 
jekyll build
this command will rebuild the _site folder, then run command:
gulp serve
this will run project on localhost, chec if it ispdated version or not.
Then commit and push files on git hub, then vercel will update after read the data of _site folder.
Everytime you change something in any file, after updating _site folder, then add it to git using folder git bash:
go to project in PC, open git bash, give command:
git init  (only first time when you push project on githb repo)
git add .
git commit -m "any comment here"
git push   (push should be in Main branch)
from these three command, changes will update in github repo, and vercel will autonaticaaly update and redeploy the website with new changes
When you update any img, or change just img extension, not in coding file, but in img folder (e.g. computech.JPG to computech.jpg), then git commit will not work
give these command:
git mv img/portfolio/computech/computech.JPG temp.jpg  (give comp path/ tell git to rename a file)
git commit -m "temp rename"
then, 
git mv temp.jpg img/portfolio/computech/computech.jpg  (change name of img/ give updated img name with full path)
git commit -m "fix lowercase"
git push
All done!!!





Hello! Thanks for checking out the repo for my latest portfolio website. This website isn't just my new portfolio, but also a personal project in and of itself. I think I've grown quite a bit as a developer & designer in the past year, so I wanted to create something to showcase some of what I've learned and done.

## Getting started
- `npm install gulp-cli -g`
- `npm install`
- `gem install jekyll sass bundler jekyll-minifier jekyll-sitemap`
- `gulp serve` to start a dev server
- `gulp build` for prod

## What I used
- [Sublime Text 3](https://www.sublimetext.com/3) my ride-or-die
- [Github Pages](https://pages.github.com/) for easy push-to-deploy hosting
- [Jekyll](https://jekyllrb.com/) for a static site generator
- [Sass](http://sass-lang.com/) for less time-consuming and more modular CSS
- [Bourbon](http://bourbon.io/) for sass mixins
- [Gulp](http://gulpjs.com/) for an automated and enhanced workflow
- [Flaticon](http://www.flaticon.com/) for images
- [Unsplash](https://unsplash.com/) for stock photos
- [Skrollr.js](https://github.com/Prinzhorn/skrollr) for parallax effects
- [Formspree](https://formspree.io/) for a simple, sans-PHP contact form

Let me know what you think!





from here portfolio

- title: Screentime 2.0
  demo: https://play.google.com/store/apps/details?id=com.starry.management
  description: ScreenTime 2.0 was one of <a href="https://starry.com/" target="_blank">Starry</a>'s most important consumer-facing software updates on <a href="https://starry.com/station" target="_blank">Starry Station</a>, providing new functionality for users to easily filter content, pause the internet, and even create custom rules for blocking apps like Facebook and Twitter right from their mobile phones. As a co-op, I played a large role in the implementation of this feature on Starry's cordova android app, and was responsible for building out front-end designs, linking up back-end data, as well as communicating with designers and other engineers throughout the process. <br><br> Check out the Starry App on <a href="https://play.google.com/store/apps/details?id=com.starry.management" target="_blank">Google Play</a>, and learn more about ScreenTime 2.0 on <a href="https://www.producthunt.com/tech/screentime-for-starry-station" target="_blank">Product Hunt</a> and the <a href="https://blog.starry.com/whats-new-screentime-just-got-better-for-parents/" target="_blank">Starry Blog</a>.
  img: screentime
  used:
  - thing: JavaScript
  - thing: CSS
  - thing: Handlebars.js
  - thing: Backbone.js
  - thing: Marionette.js
  - thing: Cordova

- title: Online Resume
  demo: http://brittanychiang.com/react-profile/
  code: https://github.com/bchiang7/react-profile/
  description: This is just an online version of my resume I made for fun. I was interested in learning React.js, so I found this <a href="https://medium.com/learning-new-stuff/building-your-first-react-js-app-d53b0c98dc#.1439cdewq">simple tutorial</a> and it kind of spun into this weekend project. I probably didn't need to use React at all, but hey, at least I learned a few things!
  img: resume
  used:
  - thing: JavaScript
  - thing: React.js
  - thing: CSS

- title: Old Personal Website
  demo: http://brittanychiang.com/v1
  code: https://github.com/bchiang7/website_2015/
  description: This was my first portfolio website I built in 2014. It's a simple one-pager like this one, but relied heavily on Bootstrap. Since then, I think my web development and design skills have expanded immensely.
  img: websitev1
  used:
  - thing: HTML
  - thing: CSS
  - thing: Bootstrap
  - thing: JavaScript
  - thing: jQuery

- title: CourseSource
  demo: http://webdevspring2016-chiangbrittany.rhcloud.com/project/client/#/login
  code: https://github.com/bchiang7/WebDevSpring2016/tree/master/public/project
  description: CourseSource is a web application built on the MEAN (MongoDB, Express, Angular, Node) stack for my web development class in 2015. I created this web app with the intention of providing Northeastern Students a better experience browsing the courses offered at Northeastern (which is currently a painstakingly tedious task on our current student portal).
  img: coursesource
  used:
    - thing: HTML
    - thing: CSS
    - thing: Bootstrap
    - thing: JavaScript
    - thing: jQuery
    - thing: NodeJS
    - thing: AngularJS
    - thing: Express
    - thing: MongoDB

- title: NU Women in Tech
  demo: http://nuwit.ccs.neu.edu/
  code: https://github.com/nuwit/website
  description: While serving as web chair for Northeastern University Women in Technology, I did a complete overhaul of the club website. I designed and developed the current website using Jekyll as a static site generator, and was responsible for the upkeeping and maintainence of the site.
  img: nuwit
  used:
    - thing: Jekyll
    - thing: Liquid
    - thing: Yaml
    - thing: HTML
    - thing: CSS
    - thing: Bootstrap
    - thing: jQuery

- title: Fontipsums
  demo: http://brittanychiang.com/fontipsums
  code: https://github.com/bchiang7/fontipsums
  description: As a typography nerd, I wanted a way to visually see different font combinations together. I whipped up this simple website to display some of my favorite pairings combined with some fun lorem ipsum variations I found on the web. Over the course of creating this site, I learned a lot about web fonts and best practices.
  img: fontipsums
  used:
    - thing: HTML
    - thing: SCSS

- title: One Card For All
  demo: http://onecardforall.org
  description: At MullenLowe, I helped build this 2015 holiday site around an algorithm that generated a holiday greeting to each and every person on the planet. We also accounted for newcomers being added at an amazing rate. Overall, the website is a tranquil, animated experience. As new names appear, visitors can watch them fall, like snowflakes, onto a stylized world map. Users can also find their own name and see it as part of the world collective. Check out this short <a href="http://us.mullenlowe.com/work/one-card-for-all/" target="_blank">video</a> describing the project!
  img: onecard
  used:
    - thing: HTML
    - thing: SCSS
    - thing: JavaScript
    - thing: jQuery

- title: JetBlue HumanKinda
  demo: https://us.mullenlowe.com/work/humankinda/
  description: During my first co-op as a creative technologist at Mullen Lowe, I played a major role in the development of this Tumblr site to complement JetBlue's HumanKinda campaign and documentary. The site houses the video documentary at the top, the many graphics created by Mullen for the campaign, and an interactive quiz to determine how "HumanKinda" you are. Learn more about this project <a href="http://us.mullenlowe.com/work/humankinda/" target="_blank">here</a>!
  img: humankinda
  used:
    - thing: HTML
    - thing: CSS
    - thing: JavaScript
    - thing: jQuery





<!-- from here experiences  -->
- position: HCI Research Assistant
#   company: NU College of Computer &amp; Information Science
#   url: http://www.ccis.northeastern.edu/
#   description: Assisted a computer science PhD student in the development of a software prototype built with HTML, CSS, JavaScript, and jQuery to facilitate better understanding of parent-child communication preferences in low-SES (Socio-Economic Status) families. Developed remotely to meet weekly deadlines and project checkpoints.
#   sprite: research
#   date: Mar - May 2015

# - position: Creative Technologist Co-op
#   company: MullenLowe U.S.
#   url: http://us.mullenlowe.com/
#   description: Developed and maintained code for in-house and client websites. Tested front-end code in various browsers and mobile devices to ensure cross-browser compatibility and responsiveness. Collaborated closely with other developers and digital producers to meet deadlines for clients including Lovesac, U.S. Cellular, JetBlue, and more.
#   sprite: industry
#   date: July - Dec 2015

# - position: HCI Teaching Assistant
#   company: NU College of Computer &amp; Information Science
#   url: http://www.ccis.northeastern.edu/
#   description: Assisted professor with grading homework and project assignments. Held office hours to aid students in their understanding of core HCI concepts and reported to the professor the extent of their understanding.
#   sprite: academic
#   date: Jan - May 2016

# - position: President
#   company: NU Women in Tech
#   url: http://nuwit.ccs.neu.edu
#   description: Lead weekly club meetings to foster a community of diverse women in CS. Manage a variety of academic and social activities throughout the semester, including tech talks, student panels, and workshops. Communicate regularly with e-board and administrative organizations.
#   sprite: university
#   date: May 2016 - Present

# - position: Software Engineer Co-op
#   company: Starry
#   url: https://starry.com/
#   description: Engineered and maintained major features of Starry's customer-facing web app using ES6, Handlebars, Backbone, Marionette, and CSS. Proposed and implemented scalable solutions to issues identified with cloud services and applications responsible for communicating with Starry Station. Worked closely with designers and other developers to ensure thoughtful and coherent user experiences across Starry’s mobile apps.
#   sprite: industry
#   date: July - Dec 2016

# - position: Developer
#   company: Scout Studio
#   url: http://www.northeastern.edu/scout/
#   description: Collaborated with a small team of student designers to spearhead a new design system for Scout’s first annual student-led design conference at Northeastern. Worked closely with designers and management team to develop, document, and manage the conference’s marketing website using Jekyll, Sass, and JavaScript.
#   sprite: university
#   date: Jan 2017 - Present

# # - position: UI Engineer Co-op
# #   company: Apple
# #   url: http://www.apple.com/
# #   description: Worked on iTunes using Ember.js
# #   sprite: industry
# #   date: July - Dec 2017
