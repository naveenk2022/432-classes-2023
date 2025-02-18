# 432 Class 14: 2023-03-02

[Main Website](https://thomaselove.github.io/432-2023/) | [Calendar](https://thomaselove.github.io/432-2023/calendar.html) | [Syllabus](https://thomaselove.github.io/432-syllabus-2023/) | [Notes](https://thomaselove.github.io/432-notes/) | [Contact Us](https://thomaselove.github.io/432-2023/contact.html) | [Canvas](https://canvas.case.edu) | [Data and Code](https://github.com/THOMASELOVE/432-data) | [Sources](https://github.com/THOMASELOVE/432-classes-2023/tree/main/sources)
:-----------: | :--------------: | :----------: | :---------: | :-------------: | :-----------: | :------------: |:------:
for everything | for deadlines | expectations | from Dr. Love | ways to get help | lab submission | for downloads | to read

## Today's Slides

Class | Date | PDF | Quarto .qmd | Recording
:---: | :--------: | :------: | :------: | :-------------:
14 | 2023-03-02 | **[Slides 14](https://github.com/THOMASELOVE/432-slides-2023/blob/main/slides14.pdf)** | **[Code 14](https://github.com/THOMASELOVE/432-slides-2023/blob/main/slides14.qmd)** | Visit [Canvas](https://canvas.case.edu/), select **Zoom** and **Cloud Recordings**

## More to come.

## Time to Event Data

Materials on time-to-event outcomes are found in Chapters 29-31 of our [Course Notes](https://thomaselove.github.io/432-notes/). This is a very brief introduction to the topic, and we will continue to discuss survival analysis and Cox regression in classes 21 and 22 of this course. My department also offers a full-semester course (PQHS 435) every spring in Survival Analysis, which goes into much more detail.

- In today's slides, I make reference to [this PDF guide by David Diez on Survival Analysis in R from OpenIntro](https://www.openintro.org/book/surv_in_r/), which I also recommend, and which provides the `OISurv` package.
- I strongly recommend you look at the (7-minute) video "[Survival Curves: Showing More by Showing Less](https://www.youtube.com/watch?v=EoIB_Obddrk)" on YouTube posted by Frank Harrell, which explains the logic behind several tools in the `rms` package which let you interact with a graph and a non-parametric survival function which saves a little more information than the usual Kaplan-Meier plot.
- The **survminer** package is where you can find the **ggsurvplot** approach we'll take today. 
- For more customization of plots like the Kaplan-Meier curves we'll build today, visit https://rpkgs.datanovia.com/survminer/ or https://github.com/kassambara/survminer/. 
    - For instance, they provide a [PDF cheat sheet](https://rpkgs.datanovia.com/survminer/survminer_cheatsheet.pdf) which was pretty helpful to me.
- You may also be interested in learning more about concordance in survival analysis (and in general) [from this vignette](https://cran.r-project.org/web/packages/survival/vignettes/concordance.pdf) (pdf).
