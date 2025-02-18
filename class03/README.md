# 432 Class 03: 2023-01-24

[Main Website](https://thomaselove.github.io/432-2023/) | [Calendar](https://thomaselove.github.io/432-2023/calendar.html) | [Syllabus](https://thomaselove.github.io/432-syllabus-2023/) | [Notes](https://thomaselove.github.io/432-notes/) | [Contact Us](https://thomaselove.github.io/432-2023/contact.html) | [Canvas](https://canvas.case.edu) | [Data and Code](https://github.com/THOMASELOVE/432-data) | [Sources](https://github.com/THOMASELOVE/432-classes-2023/tree/main/sources)
:-----------: | :--------------: | :----------: | :---------: | :-------------: | :-----------: | :------------: |:------:
for everything | for deadlines | expectations | from Dr. Love | ways to get help | lab submission | for downloads | to read

## Today's Slides

Class | Date | PDF | Quarto .qmd | Recording
:---: | :--------: | :------: | :------: | :-------------:
03 | 2023-01-24 | **[Slides 03](https://github.com/THOMASELOVE/432-slides-2023/blob/main/slides03.pdf)** | **[Code 03](https://github.com/THOMASELOVE/432-slides-2023/blob/main/slides03.qmd)** | Visit [Canvas](https://canvas.case.edu/), select **Zoom** and **Cloud Recordings**

- The PDF link provides the version of the slides that I suggest you focus on during class.
- The Quarto file link provides the code I used (in [Quarto](https://quarto.org/)) to build the slides.
- See [the resources page](https://github.com/THOMASELOVE/432-classes-2023/tree/main/sources#learning-about-quarto-and-making-the-switch-from-r-markdown) for more advice on using Quarto and transitioning to Quarto from R Markdown. 

# Announcements

1. Our **Answer Sketch for Lab 1** (including both .qmd and .pdf) is now available on our Shared Drive.
    - A few people had trouble knitting their files into an HTML that could be viewed successfully on Canvas. Take a look at what you're submitting and make sure it looks like what you're planning for, and also, be sure to include all of the YAML pieces included in the template, not just some of them. Thanks!
2. The [Minute Paper after Class 03](https://bit.ly/432-2023-minute-03) is now available, and is due Wednesday 2023-01-25 at Noon.
3. I edited Chapter 3 (so it really produces 90% confidence intervals for the t tests), and rearranged the current Chapters 11-13 in the [Course Notes](https://thomaselove.github.io/432-notes/), renamed the files (in a way that shouldn't affect you, but we'll see), and added Chapter 14 on fitting linear models with `ols` since our last class. 
4. The material on survey weights that we'll discuss today isn't really part of the Course Notes, so the slides and references below will be your main sources.

## On Asking Questions

1. Using the tools we've set up for feedback, in particular Campuswire and TA office hours, is definitely the best approach to getting an answer in a timely fashion. Emailing Dr. Love in the evening (particularly this week and the following three weekends) is a way for your question to be answered too late to do you any good.
2. When asking a question of us or anyone else about coding, it's always better for you to err on the side of sending along your entire Quarto file, so that we can attempt to replicate the problem you are observing, rather than just sending us a piece of your code, which may or may not be where the trouble lies. Thanks!

## On Categorizing Quantitative Data

Categorizing quantitative information before graphing it is generally something to avoid. Show as much of the data as possible, would be my first suggestion. But if it cannot be helped, then I am aware of two particularly appropriate tools for categorizing quantitative data:

- the `cut_interval` function from the **ggplot2** package (part of the tidyverse) - details at <https://ggplot2.tidyverse.org/reference/cut_interval.html>
- the `cut2` function from the **Hmisc** package, which is the one I usually use, for example, there is a demonstration in Section 4.3.1 of the 432 Course Notes at <https://thomaselove.github.io/432-notes/431review2.html#creating-a-low-and-high-group-on-sedate>

## References related to Today's Slides

Three primary sources:

- Ramzi W. Nahhas, [Introduction to Regression Methods for Public Health Using R](https://bookdown.org/rwnahhas/RMPH/), in particular the Chapter on [Analyzing Complex Survey Data](https://bookdown.org/rwnahhas/RMPH/survey.html).
- [Example R code to replicate NCHS Data Brief No. 303, Figure 1](https://wwwn.cdc.gov/nchs/data/tutorials/DB303_Fig1_R.R)
- The `survey` package home page: http://r-survey.r-forge.r-project.org/survey/index.html

### Tutorials...

- https://www.r-bloggers.com/2015/09/linear-models-with-weighted-observations/
- https://stackoverflow.com/questions/10268689/weighted-regression-in-r
- https://online.stat.psu.edu/stat501/lesson/r-help-13-weighted-least-squares

### On NHANES specifically...

- https://wwwn.cdc.gov/nchs/nhanes/analyticguidelines.aspx
- https://wwwn.cdc.gov/nchs/nhanes/tutorials/Module3.aspx
- https://stylizeddata.com/how-to-use-survey-weights-in-r/
- https://stats.idre.ucla.edu/r/faq/how-can-i-do-regression-estimation-with-survey-data/
- http://asdfree.com/national-health-and-nutrition-examination-survey-nhanes.html

## What Should I Be Working On?

1. Please complete the [Minute Paper after Class 03](https://bit.ly/432-2023-minute-03) by noon tomorrow (Wednesday 2023-01-25)
2. Continue reading [How To Be A Modern Scientist](https://leanpub.com/modernscientist) (so you're done by the end of January)
3. Get started on [Lab 2](https://thomaselove.github.io/432-2023/lab2.html) due next Monday 2023-01-30 at 9 PM.

## One Last Thing (one more time)

![](snowtilesTwitter.png)

[Origin and development of a Snowflake Map](https://waterdata.usgs.gov/blog/snow-tiles-demo/) by Althea Archer (posted 2023-01-11) provides reproducible R code demonstrating the evolution of a recent data visualization of snow cover in the continental United States. This work is a product of the USGS (United States Geological Survey) - the nation's largest water, earth and biological science and civilian mapping agency.

I learned about this work from [this post at FlowingData](https://flowingdata.com/2023/01/17/snow-cover-mapped-using-snowflakes/).

## Shameless Promotion: The Play That Goes Wrong 

- The Play That Goes Wrong runs from January 27 - February 18, 2023 on Friday and Saturday nights at 8 PM at [Aurora Community Theatre](https://www.auroracommunitytheatre.com/).
- Details at https://github.com/THOMASELOVE/theater and https://www.auroracommunitytheatre.com/
- Tickets are going quite quickly. It is plausible that some or even many performances will sell out in advance, so if you want to go, please buy tickets soon.
- Thank you.
