## Welcome to my GitHub Pages hosted [#100DaysOfCode](http://www.100daysofcode.com/) Blog
[@gipsitana](https://twitter.com/gipsitana) on Twitter

### Day 4 March 11th 2018 - box-sizing

#### The CSS property with its own day.

On 1st February 2014 Chris Coyer of CSS Tricks declared  [**International box-sizing Awareness Day**.](https://css-tricks.com/international-box-sizing-awareness-day/) 

>In honor of, you guessed it, the most humble and undersung, yet awesome and useful CSS property: [box-sizing.](https://css-tricks.com/almanac/properties/b/box-sizing/) ~ Chris Coyer

The origin of the concept being a post by Paul Irish on 1st February 2012 
[* { Box-sizing: Border-box }FTW](https://www.paulirish.com/2012/box-sizing-border-box-ftw/)

There's a [fascinating history](https://css-tricks.com/box-sizing/) and it's interesting to discover how width has been interpreted differently between the W3C and Internet Explorer.

#### The Box Model

![BoxModel](299px-W3C_and_Internet_Explorer_box_models.jpg)

#### Introduction to Modern Web Technologies

[Lea Verou](http://lea.verou.me/2018/02/free-intro-to-web-development-slides-with-demos/) has shared the slides from her MIT labs introducing students to Web development technologies. A great set of slides plus  useful resource selection to go with them.  Lots more good stuff on her wonderfully absorbing Website too.

#### CSS Grid Dev-tools and Implicit vs Explicit Tracks

Two more of Wes Bos [CSS GRID](https://cssgrid.io/) videos.  I'm getting the hang of using npm through Powershell for ```browser-sync```.  Quite a bit of shuffling windows around the desktop and rearranging the dev tools panes, resizing things.

Outlining and changing the colour the lines around items in _web developer>inspector_.  Dotted lines surround implicit tracks, which are like the default ones and dashed lines border explicit tracks which are defined by you in the code.

### Day 3 March 10th 2018 -  Fun with CSS Grid Fundamentals

Second day of the [Wes Bos ](http://wesbos.com/) [CSS GRID](https://cssgrid.io/) course dives right into making and sizing grid items.

![GriddyUp](griddyup.jpg)


This piece of code demonstrates how ```display: grid;```  works on all the container items,  
```grid-template-columns: 200px 500px;``` and ```grid-template-rows: 200px 100px 400px;``` explicitly sizes the items and 
```grid-gap: 20px;``` sets the tracks, which are like margins between the items.
   

```
    .container {
      display: grid;
      grid-template-columns: 200px auto 500px 50px;
      grid-template-rows: 200px 100px 400px;
      grid-gap: 20px;
    }
``` 
  
The ```auto``` keyword made things fluid and the values are pixels or rems rather than percentages as the new ```fr``` value is going to be introduced instead later on.

### Not everything has to be square!

Sometimes it seems like everything on the Web is a box - it doesn't have to be.

>Use the Clip Path property to alter elements in your layouts to be polygons, circles, triangles, and more. ~ Jen Simmons

In this great video  [Jen Simmons](https://www.youtube.com/watch?v=3kncTIpc4Q4) explains.  There's a whole bunch more about layout on her YouTube Channel [Layout Land](https://www.youtube.com/channel/UC7TizprGknbDalbHplROtag) - just what I need right now.



### Day 2 March 9th 2018 - Griddy Up

After a quick review of last year's coding efforts I decided that I need to improve my CSS skills.  So today I started  
[CSS GRID](https://cssgrid.io/) the 25 video free course by [Wes Bos ](http://wesbos.com/).

>Wes, How is this Free!? What's the Catch?

>No catch! A huge thanks to Mozilla Firefox who has sponsored my time to create this course and offer it up for free. Firefox packs >some of the best dev tools and in particular their CSS Grid Dev tools make understanding, debugging and visualizing complex grid >layouts a snap.

### Starter Files and Tooling Setup

After the welcome video the first tutorial is only a little over 10 minutes, but there is a lot to do!
- Install Firefox Quantum: Developer Edition
- Download and install Node.js
- Download starter files from GitHub
- Download and install VS Code

I already have the Firefox Quantum Developer Browser but I did need to install Node.js.  I followed along with the video pausing it to get through each of the steps required to complete the setup.  I used Windows Powershell to check for the Node.js installation. Next was downloading the starter files from GitHub, I also forked the repo, noting that I should take care not to do a pull request. 

I got VS code up and running and read the opened JSON lock file.  Although this seemed a bit obscure to start with the reason is to have the```"browser-sync"``` tool update the results of coding in the browser without refreshing.

The next part was to look at the start file package in Powershell by copy pasting it into the root and then ```npm i``` which installed the dependency  ```"browser-sync"```.

```npm start``` then opened a page of the files to work with in the browser.

- A nice basic html skeleton file.
With a demonstration of how adjustments automatically refresh.
- An explanatory recommendation and demonstration of Emmet.
```container.item*10``` is a useful snippet. Hit tab = ten divs.
- A run through of the basic CSS stylesheet no CSS Grid here yet.
- ```var(--color)```from ```:root``` top of stylesheet
- Google ```"box-sizing: border-box;"``` 

Loads of tips and snippets in a short video so I'm happy.  Everything worked not exactly straight away but eventually so looking forward to tomorrow.




                                                                                                                  
### Day 1 March 8th 2018 - Mastering Markdown

Last year I coded every day, nearly four rounds of one hundred days of code. As well as tweeting my progress I followed tutorials, got stuck, found answers, read manuals, read code, read blogs, signed up for email newsletters, did MOOCs ... and made this 
website of my own [gipsi.itbit.me blog](http://gipsi.itbit.me).

Today I'm reviewing what I did, tinkering a bit, fixing broken links and setting up some new things for a another round of [#100DaysOfCode](http://www.100daysofcode.com/).

I'm participating in the CodeNewbie Challenge [**Start Coding** #CNC2018](http://2018.codenewbie.org/) which is encouraging me to think more clearly about and be more specific with my coding goals.

### Day 1 February 1st 2018 - delayed start

Partly due to working on:
- Learning about [Biodiversity and Global Change: Science & Action](https://www.class-central.com/course/coursera-biodiversity-and-global-change-science-action-7793) and creative writing [The Craft of Plot](https://www.class-central.com/course/coursera-creative-writing-the-craft-of-plot-5625).
- Setting up the tools for [Creative Programming for Digital Media & Mobile Apps](https://www.mooc-list.com/course/creative-programming-digital-media-mobile-apps-coursera).
- "Doing the Opposite" [#100DaysOfVolunteering](gipsi.github.io/snowtrees_20180227.jpg) as a thing after thinking about [#100DaysOfX](http://www.100daysofx.com/).
- A MOOC about mental health and wellbeing [Psychology and Mental Health: Beyond Nature and Nurture](https://www.futurelearn.com/courses/mental-health-and-well-being).

 _*I am developing this coding blog from a template and intend to keep the following section here for reference:_

## *Welcome to GitHub Pages
 
You can use the [editor on GitHub](https://github.com/gipsi/gipsi.github.io/edit/master/README.md) to maintain and preview the content for your website in Markdown files.

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.

### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/gipsi/gipsi.github.io/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://help.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.

