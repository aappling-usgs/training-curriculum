---
date: 2016-10-11
slug: introR-LMGWSCTN-Oct16
title: LMGWSC - Tennessee
menu: 
  main:
    parent: Course Specific Material
    weight: 1
---
October 11th - 13th in Nashville, TN

### Installation

See [Before the Workshop](/intro-curriculum/Before) for information on what software should be installed prior to the course.

### Tentative schedule

**Day 1**

-   08:00 am - 09:00 am -- Instructors available for questions
-   09:00 am - 10:30 am -- [Introduction](/intro-curriculum/Introduction)
-   10:30 am - 10:45 am -- *Break*
-   10:45 am - 12:00 pm -- [Get](/intro-curriculum/Get)
-   12:00 pm - 01:00 pm -- *Lunch*
-   01:15 pm - 03:15 pm -- [Clean](/intro-curriculum/Clean)
-   03:15 pm - 03:30 pm -- *Break*
-   03:30 pm - 04:30 pm -- [Clean](/intro-curriculum/Clean) continued
-   04:30 pm - 05:00 pm -- End of day wrap-up

**Day 2**

-   08:00 am - 08:30 am -- Instructors available for questions
-   08:30 am - 09:30 am -- [Explore](/intro-curriculum/Explore)
-   09:30 am - 10:30 am -- [Analyze: Base](/intro-curriculum/Analyze)
-   10:30 am - 10:45 am -- *Break*
-   10:45 am - 12:00 pm -- Analyze: [EGRET](https://cran.r-project.org/web/packages/EGRET/EGRET.pdf), [rloadest](https://github.com/USGS-R/rloadest), [dataRetrieval](https://cran.r-project.org/web/packages/dataRetrieval/dataRetrieval.pdf)
-   12:00 pm - 01:00 pm -- *Lunch*
-   01:00 pm - 02:30 pm -- Visualize: [ggplot2](/intro-curriculum/ggplot2/)
-   02:30 pm - 02:45 pm -- *Break*
-   02:45 pm - 04:00 pm -- Visualize: [ggplot2](/intro-curriculum/ggplot2/) continued
-   04:00 pm - 04:30 pm -- End of day wrap-up

**Day 3**

-   08:00 am - 08:30 am -- Instructors available for questions
-   08:30 am - 10:00 am -- [Repeat](/intro-curriculum/Reproduce/)
-   10:00 am - 10:15 am -- *Break*
-   10:15 am - 10:30 am -- [The importance of reproducibility](https://owi.usgs.gov/blog/reproducibility)
-   10:30 am - 10:45 am -- Automated reporting with R Markdown
-   10:45 am - 11:00 am -- What is Shiny?
-   11:00 am - 12:30 pm -- Practice: [USGS R packages](/intro-curriculum/USGS/), projects (group/individual), or [additional topics](/intro-curriculum/Additional/)

### Data files

Download data from the [Data page](/intro-curriculum/data/).

### Additional resources

-   [USGS-R blog](https://owi.usgs.gov/blog/tags/r)
-   [USGS-R twitter](https://twitter.com/USGS_R)
-   [USGS-R GitHub](https://github.com/USGS-R) (package source code + bug/feature reporting)
-   [RStudio cheatsheets](https://www.rstudio.com/resources/cheatsheets/) (data wrangling, visualization, shiny, markdown, RStudio, etc)

### Instructors

Lindsay Carr (<lcarr@usgs.gov>) -- *primary contact*

Jennifer Murphy (<jmurphy@usgs.gov>)

Scott Worland (<scworland@usgs.gov>)

### Lesson scripts

Instructors will be live coding during this course. Our code will be shared with you here at the end of each day.

### What is Shiny?

[Shiny]((http://shiny.rstudio.com/)) is a web application framework that allows you to present your data and results in an interactive web application. You can script the whole process in R and Shiny will convert that to an html document – no need to learn another computer language. There are lots of [example of shiny applications](www.rstudio.com/products/shiny/shiny-user-showcase/). These apps are useful for sharing results with others or exploring your data and results yourself.

All shiny apps open in a web browser. At the most basic level, R runs in the background on a personal computer and serves the application to a web browser. The user can make changes on the webpage and these changes will be processed in R and updated on the webpage. The interaction allows the user to easily explore their data and analyses based a varying a set of pre-specified inputs.

![](/course-specific-material/static/shiny1.png)

When the shiny app is hosted on your computer and a colleague asks to use your app, you will need to send them the R files which they would download and run on their computer. However, if the app is hosted on a web server then the shiny app can be served to the internet and anyone with a computer and internet access can use it.

![](/course-specific-material/static/shiny2.png)

Shiny apps are built using 3 basic components: a user interface (UI), server instructions, and a function that ties the UI and server instructions together. The UI is a web document written in HTML that describes how the webpage should look. With Shiny you don’t actually have to learn HTML to generate this document, instead Shiny converts the script you write in R to HTML. The server instructors tell the app what to show and how to respond to changes made on the webpage by the user. Finally, the UI and the server instructions are joined together using a shiny-specific function.

Spend some time exploring the different types of web applications:

-   <http://www.rstudio.com/products/shiny/shiny-user-showcase/>
-   <http://www.showmeshiny.com/>.

And when you’re ready to try it out yourself use [this tutorial](http://shiny.rstudio.com/tutorial/) or follow [this cheat sheet](http://shiny.rstudio.com/images/shiny-cheatsheet.pdf) to get the basic steps.

*Images from tutorial video at <http://shiny.rstudio.com/tutorial/>*

You can download the example shown in the course from [here](https://drive.google.com/drive/u/1/folders/0B54YFPSk4XN8NnFjUWE3MjVVRHc).