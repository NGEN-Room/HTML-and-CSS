# HTML & CSS

## Overview
Last session we created our blogs using github pages > we then created a basic HTML file > staged, commited and pushed that to Github. This lesson we are looking to build your blog using HTML and CSS while also getting used to Github, command line and VScode. You will be learning HTML through online resources and applying that to your blog.

When creating your blog remember that even though your blog will serve a purpose, experiment with it, see what works and what doesnt. You can get lost for hours of just coding so be digilint with your timing. If you spend an hour on one things versus multiple then you may want to re-evalutate your plan of action. I want you guys to create as much horrible, messy pieces of code as it teaches you what works and what doesnt.

Also remember you are more than welcome to copy and paste but if you want to actually learn what you are doing then doing it from scratch or breaking down what you copy and pasted so you know what does what

# Options of learning
## HTML + Css Basics: Udacity ( Watching and action )
I will be using other free resources such as freecodecamp and udacity to help teach you a little bit more about html and what it is. Udacity learning style is to show a video and then do some sort of action after. If this sounds like you then i recommend the below

 - if you head to this link: [Intro-to-html-and-css](https://www.udacity.com/course/intro-to-html-and-css--ud001)
 - sign up and follow the guide for Intro to HTML and CSS
 - If you can put the speed up to 1.25 or 1.5 as it will quicken the video
    - Now the study will be up to you! you are more than welcome to do only the first one and move on thats fine. I recommend finishing up to the thrid lesson as it covers both html and css.
 - we will be runnng this lesson over the next two days so there is no need to rush. 

## HTML + Css Basics: FreeCodeCamp ( Coding and reading )
However if you want to use more coding and reading then FreeCodeCamp is the one for you. As a reminder i did both. you are more than welcome to do both they cover the same things just in a different way

1. Sign up to freeCodeCamp using your GitHub login. 
2. for an Introduction into [Basic HTML and HTML5](https://learn.freecodecamp.org/responsive-web-design/basic-html-and-html5)  
3. [Introduction to Basic CSS](https://learn.freecodecamp.org/responsive-web-design/basic-css)  
5. [Introduction to Responsive Web Design Challenges](https://learn.freecodecamp.org/responsive-web-design/responsive-web-design-principles/)

## Useful Resources 

Learn Code academy's video [tutorial for beginners](https://www.youtube.com/watch?v=3JluqTojuME&list=PLoYCgNOIyGAB_8_iq1cL8MVeun7cB6eNc&index=1) 

[Udacity HTML, CSS, and Boxes](https://classroom.udacity.com/courses/ud304) 




## Tech Blog + pull new changes 
Alright your ready to fill out your tech blog and learn how to update any new changes that have arrived.

1. to pull the new changes from github we will need our command line. in your cmd line, head on over to your Student-Journal repo
2. make sure you are on the correct branch. (`should state what branch you are in at the end of the directory route in the cmd line`)
3. once you are confident that you are on your branch, we will begin the "PULL" process
```
During the development of an app or website or code there will be alot of chagnes that are made to a main branch. If we are working on a piece of this app one of the easiest ways for us to make sure that we are working on an up to date version of the repo is to pull those changes from the master to your current working branch. In our case i will be making changes to the student-journal as we go through the program for you guys to fill out. SO this pulling process will help you alot.
```
4. Once we are ready to pull in our command line we will write 
"git pull origin master"
- "git pull" is the command to fetch the code from your current branch. Becasue we want to pull the changes from master we need to give GIT PULL some more information
- "origin" We are telling the command that it will need to pull from a remote source.
- "master" This part of the command is telling the command which branch to pull from, so becasue the changes we need are in master thats the changes we are going to pull to your current branch.
5. HOPEFULLY there are no merge conflicts ( which if you do reach out to me )
6. Awesome now our branch should have your thrid technical blog.
7. Open your branch so we can start to make some changes. Hint: code

Once you have finished stage, commit, and push to github.

## For those that have these problems:
- Dont have the student-journal on my local machine
    - Hint: Clone
- Have the repo on my local machine but not on my branch 
    - Hint: Checkout
- When i cloned down the Student-Journal and tried to checkout my branch it wasnt there.
    - either you need to pull the master repo down to your local machine. This is because you probably have an older version and just need to update the repo with the new changes and new branches that you hopefully created and pushed
    - or, you didnt push up your branch from the last local machine that you had so you dont have any online version to switch to. if this is the case then go to where you last were on and push it up.


# Blog Challenges
- Set up a basic HTML page with the appropriate tags (html, head, title, etc.)  
- Add paragraphs, headings, links, images, lists, and/or tables  
- Divide content on a page using divs and spans  
- Link an external stylesheet to an html document  
- Position elements using CSS  
- Modify element style (size, color, etc) using CSS  
- Compare and use classes and ids to manipulate elements  
- On your main index.html ( your landign page) put some information on it such as your pepeha and what the reason of your blog will used for.
- connect up your other pages to you main page

## Set up part one - Add Another HTML Page
1. Head over to where you saved or cloned your blog code using cmd line
2. Once there in your command line make a new folder called blog (Hint: mkdir)
2. CD into this folder and create a file caled `tech-blog-1.html`(hint: touch)
3. Open `tech-blog-1.html` in your code editor (hint: code)
4. create a HTML basic setup (html, head, title, etc.) which you can easily do using this shortcut ` ! + enter key`
5. in the body section create an H1 tag and copy your contents from your Techanical Blog week one into.  You can come back to change this later
6. This will be used for you to copy your tech blogs and show off your understanding of coding. By the end of tomorrow we should see tech-blog-1.html, tech-blog-2.html, tech-blog-3.html. Simply by copying and pasting your tech blogs into those areas.
7. do the same for your Reflection blogs. Create new file > Name it reflection-blog-one.html > create basic html > copy your contents from reflection blog week one into this file > Stage commit push

To view this file online go to `your-username.github.io/blog/tech-blog-1.html`

this will show you your blog post online


## Set up part one - Link CSS stylesheet
1. currently you have a line of code in your index.html ( on the main directoy root of your repo ) which is bugged. 
2. To sort this bug out you are wanting to connect it to the correct css stylesheet name
``` 
Current code line 7:   <link rel="stylesheet" href="styles.css">
current style sheet name: index.css

AS you can see the link in index.html ( href="styles.css" ) is not correctly linked to the index.css 

index.css ---> href="styles.css" 
vs 
index.css ---> href="index.css"
```
3. what you need to do is change the link in index.html from href="styles.css" to href="index.css"
4. once you have changed this you should be able to see the css changes on your live server ( for your landing page )
5. Now what we want to do is connect a CSS page to all the other blogs. NOTE: usually you would have one CSS stylesheet which you can link to so everything is cohesive. 
6. just like on the index.html page. create a link into one of the blog htmls.
7. NOW if you copy and paste the css link into the head this will not work. Reason being is that in the link you are pointing to a style sheet in that directoy ( or blog folder ).
8. what you want to do is link that style sheet ( in the blog htmls ) back to the index.css a layer above. (remember how you would go up a level or directory in your command line )
9. once you have linked all the files to the css file you are ready to start experimenting, changing and creating your blog using HTML and CSS
10. why are you still here do you blog



