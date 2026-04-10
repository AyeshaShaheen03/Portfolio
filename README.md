# Personal Website 🚀🔥


For run project on local host:
gulp build, npm run build
gulp serve   (main command)
then it will run on (localhost:3000)
After changes:
Everytime you change something in any file, then add it to git
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
