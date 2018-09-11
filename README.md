---
output:
  html_document: default
  pdf_document: default
---

Modern Data Structures
======================

QMSS G5072 - Columbia University
--------------------------------

**Fall 2018**  
**Lecture: Mondays 6.10 - 8pm (but see weekly schedule)**  
**Location: 825 Seeley W. Mudd Building**

Instructor: Thomas Brambor  
[thomas.brambor.com](http://thomas.brambor.com/)  
[tb2729@columbia.edu](tb2729@columbia.edu)  
IAB 509E Mon 4.50 - 5.50pm  

TA1: Xinyu Ni  
[xn2115@tc.columbia.edu](xn2115@tc.columbia.edu)  
IAB 270J Time Thur 10am - 12pm

TA2: Mikaela Zhang  
[xz2782@columbia.edu](xz2782@columbia.edu)  
IAB 270J Time Tue 10am - 12pm

------------------------------------------------------------------------

Quick Links
-----------

-   [Course Description](#course-description)
-   [References and Resources](#references-and-resources)
-   [Requirements and Assessments](#requirements-and-assessments)
-   [Policies](#policies)
-   [Lecture Topics](#lecture-topics)
    -   [Part 1 - Data Manipulation](#part-1---data-manipulation)
    -   [Part 2 - Getting Data in](#part-2---getting-data-in)
    -   [Part 3 - Other “Big Data” Considerations](#part-3---other-big-data-considerations)

### Course Description

This course is intended to provide a detailed tour on how to access, clean, “munge” and organize data, both big and small. (It should also give students a flavor of what would be expected of them in a typical data science interview.) Each week will have simple, moderate and complex examples in class, with code to follow. Students will then practice additional exercises at home. The end point of each project would be to get the data organized and cleaned enough so that it is in a data-frame, ready for subsequent analysis and graphing. Therefore, no analysis or visualization (beyond just basic tables and plots to make sure everything was correctly organized) will be taught; and this will free up substantial time for the “nitty-gritty” of all of this data wrangling.

### Course Website

All lecture materials, exercises, and (links to) readings will be made available in the GitHub course repository.

This is a fairly new course. The materials and topics indicated below are a provisional roadmap that will be adjusted to the needs of the students. I will let you know well ahead of time of any changes.

### Communications

For all questions to the members of the teaching team, we will be using a discussion forum on Piazza. Please [sign up here.](https://piazza.com/columbia/fall2018/qmssgr50722018moderndatastructures). The forum will be used to exchange questions about lectures, assignments, software etc. Students are encouraged to help each other!

Students are asked to customize their Piazza notification preferences to receive immediate (ASAP) notifications of messages and announcements through the third-party provider of choice (e.g. email, SMS/text). Students are also asked to log into the course regularly (more than twice a week) and check announcements and the Piazza inbox immediately upon logging in to stay on top of developments in the course as they occur.

Please send all emails and messages to the instructor and teaching assistants through Piazza. Messages sent through the Piazza Inbox (Send a Message) feature will be answered within 24 hours during the week and within 48 hours on weekends. Please consider these response times when asking about assignments etc.

------------------------------------------------------------------------

### References and Resources

#### Books

There are no required books for the course. All required readings will be provided as PDFs or links. However, here are some books that you may find useful in addition to the lectures and course readings.

-   Wickham, H., & Grolemund, G. (2017). R for Data Science: Import, Tidy, Transform, Visualize, and Model Data (1 edition). O’Reilly Media. -- Great as introduction on how to use R. From the creator of many R packages that we use in the course, this will help with the usual tasks of data import and management, modeling, and some visualization. [Book is available for free online](http://r4ds.had.co.nz/).

-   Wickham, H. (2014). Advanced R (1 edition). Boca Raton, FL: Chapman and Hall/CRC. [Book is available for free online](http://adv-r.had.co.nz/)

-   Boehmke, B. C. (2016). Data Wrangling with R (1st ed.). New York, NY: Springer. [Book is available as an electronic resource in the library](http://www.columbia.edu/cgi-bin/cul/resolve?clio12431857)

#### Free Online Resources

##### Datacamp

I have obtained a license from [Datacamp](https://www.datacamp.com/enterprise/modern-data-structures-qmss-g5072), a provider of online education. All students will be enrolled within the first week of the course. The syllabus indicates **suggested Datacamp modules** to complement the lecture material and graded assignments. Of course, feel free to try out other offerings you are interested in from Datacamp's high quality content.

##### R, RStudio, and R Markdown

-   [IDRE at UCLA](http://www.ats.ucla.edu/stat/r/) has lots of tutorials, code examples, for R and other statistical packages.
-   [Try R](http://tryr.codeschool.com). In-browser, interactive online tutorial. Particularly useful if you have not used R (much) before.
-   [Cheat sheets](https://www.rstudio.com/resources/cheatsheets/) for data wrangling, data visualization, general use of R, R Studio, R Markdown etc.
-   [R Studio resources for R Markdown](http://rmarkdown.rstudio.com/). Get started here with markdown.
-   [Awsome-R](https://awesome-r.com) A curated list of great R packages and tools.

##### Git and GitHub

-   Git
    -   [Official git command line and GUI clients, official documentation](https://git-scm.com/)
-   Clients
    -   [Desktop Client for Mac and Windows](https://desktop.github.com/)
    -   [Sourcetree - another free visual Git](https://www.sourcetreeapp.com/)
-   Tutorials
    -   [Setting up git](https://help.github.com/articles/set-up-git/)
    -   [Try.github](https://try.github.io)
    -   [Hello World - GitHub for the non-programming beginner.](https://guides.github.com/activities/hello-world/)
    -   [Guides at GitHub](https://guides.github.com/)
    -   [Git and Github guide from plot.ly](https://plot.ly/r/github-getting-started-for-data-scientists/) Extensive screen-shot guided intro to Git, Github, Git in RStudio and GitHub pages.
    -   [Pro Git - a full book with lots of details](https://git-scm.com/book/en/v2)
    -   [Datacamp - Introduction to Git for Data Science](https://www.datacamp.com/courses/introduction-to-git-for-data-science)

##### Coding Help Sites

-   <http://stackoverflow.com/> Programming Q&A site. Excellent first stop if you have questions on coding. Searching for keywords, and restrict your queries by adding tags about the coding language or package in square brackets, e.g. `[R]`,`[ggplot]`, or `[shiny]`.

-   <http://stats.stackexchange.com/> A stackoverflow off-shoot with a bit more focus on conceptual questions in statistics.

-   <http://rseek.org/> Search engine for R-related stuff, including tutorials and code.

### Requirements and Assessments

#### Requirements

This course will guide you through the data wrangling process using the software package `R` for most exercises. The program `R` itself can be downloaded for free at <http://cran.r-project.org/>.

Some familiarity with the software, in particular with regards to the base functions in R is assumed. Knowledge of specific packages and other software tools will be built throughout the course. If you have extensive experience with other similar programming tools, say Python or Matlab, you will be fine. However, if you are completely new to `R` and do not have compensatory experience in other coding languages, please consider  the QMSS course "Data Mining" instead.

You will need to have access to your own computer to install software and packages, do your assignments etc. I highly recommend bringing your laptop to class to follow along the coding tutorials and examples.

#### Assessments

**Homework**

Homework problems will be assigned on a weekly basis, and students are expected to work on them alone.

**Exams**

There is no in-class final exam. Instead, the focus will be on developing a final project in the form of an R package. 

**Grade Distribution**

The distribution of the parts for your grade is as follows:

-   Final Project = 30%
-   Homework Assignments = 60%
-   Attendance and Participation = 10%

### Policies

**Attendance and Class Participation**

Your attendance and participation are necessary at every meeting. This class will work best when students ask a lot of questions.

**Academic Integrity**

This course is based on the principles of academic integrity established by Columbia University and agreed to by each student. The same rules hold in this course. Academic dishonesty will not be tolerated. All submitted work must be your own work and properly cited.

The full guidelines on academic integrity as well as a review of how or what to cite, can be found here: <http://gsas.columbia.edu/academic-integrity>

Students found guilty of plagiarism or academic dishonesty will be subject to appropriate disciplinary action, which may include reduction of grade, a failure in the course, suspension or expulsion. This includes lab reports – if they are copied from another student, severe penalties may be applied. \*\* Note that plagarism is also possible when writing code, so be careful to write your own code.

**Late Assignment Policy**

Students will lose points for handing in late assignments, at the discretion of the instructor and teaching assistant.

**Other**

Turn off or silence your cell phones prior to the beginning of class. I reserve the right to answer all calls (your's, not mine) received during class time and let your friends know what you are learning that day.

Feel free to use laptops in class - in fact, I encourage it. Respecting your classmates and myself, please refrain from using Facebook, shopping sites or other random distractions during class.

**Changes**

There may be adjustments of readings, assignments, exams, and classrooms. Changes will be posted on Piazza/Github along with announcements.

**Slides**

Lecture slides will be made available on the course website. However, I believe that learning and understanding is better served when you need to aggregate and structure your notes yourself, so I suggest you do so as well.

------------------------------------------------------------------------

Lecture Topics
--------------

#### [Week 1: (Sep 10) Introduction](Lectures/Week01/week01_lecture.md)

-   **On your own:** Install R and R Studio on your own computer. Try out R Markdown (use the [tutorial](http://rmarkdown.rstudio.com/) to get familiar).
-   **Datacamp**: To review base R complete the course [_Introduction to R_](https://www.datacamp.com/courses/free-introduction-to-r).

### Part 1 - Data Manipulation

#### [Week 2: (Sep 17) Github](Lectures/Week02/week02_lecture.md)

-   **On your own:**
    - Sign up for a GitHub account.
    - Install GitHub Desktop (if you are confident in using command-line Git or have a different software preference, feel free to skip this step.)
    - Claim your private repository connected with this class.
-   **Reading**:
    -   [Hello World - GitHub for the non-programming beginner.](https://guides.github.com/activities/hello-world/)
    -   [An Intro to Git and GitHub for Beginners (Tutorial)](http://product.hubspot.com/blog/git-and-github-tutorial-for-beginners), by Meghan Nelson.
-   **Datacamp**: 
      - **Git**: Feel free to check out this fairly comprehensive [introduction to Git](https://www.datacamp.com/courses/introduction-to-git-for-data-science). Several things are beyond what is required in the course (undo, branches, collaboration). 
      - **R Markdown**: For a more comprehensive introduction to R Markdown the course [Reporting with R Markdown](https://www.datacamp.com/courses/reporting-with-r-markdown) is worth a look.

- **Advanced Topics (optional, on your own only)**:
    - _Combining Shiny & RMarkdown_ ([Overview here](https://beta.rstudioconnect.com/content/2671/Combining-Shiny-R-Markdown.html)):
        - RMarkdown also allows interactive applications with Shiny. Follow the [introduction on the RStudio website](http://rmarkdown.rstudio.com/authoring_shiny.html) to create an interactive document. Shiny apps can be [embedded in a document](http://rmarkdown.rstudio.com/authoring_embedded_shiny.html) or called from an externally saved shiny application. 
        - In Shiny applications themselves, you can [allow users to generate a report](https://shiny.rstudio.com/articles/generating-reports.html) (based on markdown). 
    - RMarkdown can be used directly from the command line or from within R. You can [render `.R` scripts into reports](http://rmarkdown.rstudio.com/articles_report_from_r_script.html).
    - _Report Automation_: The creation of report (as well as uploading/emailing) can be [automated completely](http://www.analyticsforfun.com/2016/01/scheduling-r-markdown-reports-via-email.html).
    - _Git_: 
        - The in-class introduction to Git was centered around GitHub. To learn a bit more, get comfortable with [command line git](http://rogerdudler.github.io/git-guide/) usage. 
        - Also, make sure you understand how branches work and how to work with a group of people.
        - Submit something to a public repository on Github using a pull request.

> **Homework 1**: [Using RMarkdown and Github](Exercises/hw01/hw01.md). Also see the [homework submission instructions](Exercises/homework_submission_instructions.md).

#### [Week 3: (Sep 24) Basics of the tidyverse](Lectures/Week03/week03_lecture.md)

-   **On your own:** Install `tidyverse` package.
-   **Reading**:
    -   [Why R is Hard to Learn](http://r4stats.com/articles/why-r-is-hard-to-learn/), by Robert A. Muenchen
    - Wickham, H., & Grolemund, G. (2017). [R for Data Science](http://r4ds.had.co.nz/). Chapters 9-12
-   **Datacamp**: There are several offerings related to data manipulation with tidyverse packages. I recommend chapters 1 and 3 of [_Introduction to the Tidyverse_](https://www.datacamp.com/courses/introduction-to-the-tidyverse). For more advanced usage, also consider [_Working with data in the tidyverse_](https://www.datacamp.com/courses/working-with-data-in-the-tidyverse) and [_Data manipulation in R with dplyr_](https://www.datacamp.com/courses/dplyr-data-manipulation-r-tutorial). 
    
> **Homework 2**: [Data Wrangling with the Tidyverse](Exercises/hw02/hw02.md). Also see the [homework submission instructions](Exercises/homework_submission_instructions.md).

#### [Week 4: (Oct 1) Functions I: the basic logic and simple steps](Lectures/Week04/week04_lecture.md)

-   **Reading**:
    -   [Functions in *Advanced R*](http://adv-r.had.co.nz/Functions.html) by Hadley Wickham
    - Some basics of code styling. [Style Guide in _R packages_](http://r-pkgs.had.co.nz/style.html), by Hadley Wickham 

-   **Datacamp**:
    - Chapters 1 and 2 of [_Writing Functions in R_](https://www.datacamp.com/courses/writing-functions-in-r).
    
- **Advanced Topics (optional, on your own only)**:
    - We discussed how scoping depended on R environments. Learn more about how these enviroments are called, how to create new environments, how you can look up their content, and how to define the search path of a scoping operation. See Wickham, _Advanced R_, chapter on ["Environments"](http://adv-r.had.co.nz/Environments.html)
    - We only discussed `for` loops in lecture. Check out two other types of loops - `while` and `repeat` loops - and how they can be useful for programming. Datacamp has a tutorial on ["A Tutorial on Loops in R - Usage and Alternatives"](https://www.datacamp.com/community/tutorials/tutorial-on-loops-in-r).
    - A great way to hide additional arguments for advanced users of a function is the [`...` (read dot-dot-dot)](https://github.com/lcolladotor/dots) argument. Try to get familiar with it and hide some options of a function you created.

> **Homework 3**: [`for` loops and functions](Exercises/hw03/hw03.md). Also see the [homework submission instructions](Exercises/homework_submission_instructions.md).

#### [Week 5: (Oct 8) Functions II: nested operations and complex sets of commands. The `purrr` package](Lectures/Week05/week05_lecture.md)

-   **On your own:** Install `purrr` package.
-   **Reading**:
    - Wickham, H., & Grolemund, G. (2017). _R for Data Science_. [Chapter 21 on "Iteration"](http://r4ds.had.co.nz/iteration.html) - For the introduction of the `purrr()` package, I follow this material quite closely.
    -   *Optional:* For a more interactive approach try [Swirl – R Programming – Lesson 9 – Functions](https://github.com/swirldev/The_R_Programming_Environment), by Johnny Chan. 
    
- **Datacamp**:
    - Chapters 3 and 4 of [_Writing Functions in R_](https://www.datacamp.com/courses/writing-functions-in-r).
        
- **Advanced Topics (optional, on your own only)**:
    -   [Section on _Functional Programming_ in *Advanced R*](http://adv-r.had.co.nz/Functional-programming.html) by Hadley Wickham. Note, that the `purrr` package did not exist yet when the book was written, so it is not discussed.
  
> **Homework 4**: [Functions II](Exercises/hw04/hw04.md). Also see the [homework submission instructions](Exercises/homework_submission_instructions.md).

#### [Week 6: (Oct 15) Functions III: Writing your own R Package](Lectures/Week06/week06_lecture.md)

-   **On your own:** Please follow the instructions in the [_Intro_](http://r-pkgs.had.co.nz/intro.html) of Hadley Wickham's book on _R Packages_ to make sure you have the required software installed.  
-   **Reading**:
    -   [Writing An R Package From Scratch](https://hilaryparker.com/2014/04/29/writing-an-r-package-from-scratch/), by Hilary Parker
    -   [Instructions for Creating Your Own R Package](http://web.mit.edu/insong/www/pdf/rpackage_instructions.pdf), by Song Kim, Phil Martin and Nina McMurry
    -   *Further reading, not required!:* Wickham, H. (2015). R Packages: Organize, Test, Document, and Share Your Code (1st edition). Sebastopol, CA: O’Reilly Media. [Available online for free](http://r-pkgs.had.co.nz/).  
- **Advanced Topics (optional, on your own only)**:
    - [*Advanced R*](http://adv-r.had.co.nz) by Hadley Wickham:  There are several issues for which we have very little time in lecture. These include [performance](http://adv-r.had.co.nz/Performance.html) of R code and how to [optimize](http://adv-r.had.co.nz/Profiling.html) it. Similarly, we spend no time on [C++ programming](http://adv-r.had.co.nz/C-interface.html), but R has some well-developed packages to create [high-performance functions in Rcpp](http://adv-r.had.co.nz/Rcpp.html).
    
> **Homework 5**: [Writing an R Package](Exercises/hw05/hw05.md). Also see the [homework submission instructions](Exercises/homework_submission_instructions.md).

#### [Week 7: (Oct 22) Functions IV: Working with strings](Lectures/Week07/week07_lecture.md)

-   **On your own:** Install `stringr` and `rebus` packages.
-   **Reading**:
    -   [Handling and Processing Strings in R](http://gastonsanchez.com/Handling_and_Processing_Strings_in_R.pdf), by Gaston Sanchez
    -   [Strings in *R for Data Science*](http://r4ds.had.co.nz/strings.html), by Hadley Wickham and Garrett Grolemund

- **Datacamp**:
    - A great course on getting started with strings is [_String Manipulation in R with stringr_](https://www.datacamp.com/courses/string-manipulation-in-r-with-stringr).
    
- **Advanced Topics (optional, on your own only)**:
    - There are a lot of tools to work with text as data. To get started with text mining and visualization, I recommend the following readings:
        * Silge, J., & Robinson, D. (2017). [Text Mining with R: A Tidy Approach.](http://tidytextmining.com/) O’Reilly Media.
        * Grimmer, J., & Stewart, B. M. (2013). Text as Data: The Promise and Pitfalls of Automatic Content Analysis Methods for Political Texts. Political Analysis, 21(3), 267-297. https://doi.org/10.1093/pan/mps028
    - For packages to work with text, I recommend the following:
        * [Quanteda package vignette](https://cran.r-project.org/web/packages/quanteda/vignettes/quickstart.html) on text analysis
        * [tm package vignette](https://cran.r-project.org/web/packages/tm/vignettes/tm.pdf)

> **Homework 6**: [Working with Strings](Exercises/hw06/hw06.md). Also see the [homework submission instructions](Exercises/homework_submission_instructions.md).

### Part 2 - Getting Data In

#### [Week 8: (Oct 29) APIs](Lectures/Week08/week08_lecture.md)

- **On your own:** Install the `httr` package.  
-   **Reading**:
    -   [Using Data.gov APIs in R](http://data.library.virginia.edu/using-data-gov-apis-in-r/), University of Virginia Library
    -   [Scraping via APIs](http://bradleyboehmke.github.io/2016/01/scraping-via-apis.html), by Bradley Boehmke

- **Datacamp**:
    - Chapters 1 and 2 of [_Working with Web Data in R_](https://www.datacamp.com/courses/working-with-web-data-in-r).
    
- **Advanced Topics (optional, on your own only)**:
    - _Writing a R API client_: We have learned how to write an R package before. So how about writing an R API package if none is available yet. CRAN provides some [Best practices for API packages](https://cran.r-project.org/web/packages/httr/vignettes/api-packages.html) by Hadley Wickham.
    - _Creating an API_: We can go even further. The [`plumber`](https://www.rplumber.io/) package allows you to turn your existing R code into a web API.

> **Homework 7**: [Calling an API using `httr`](Exercises/hw07/hw07.md). Also see the [homework submission instructions](Exercises/homework_submission_instructions.md).

#### [(Nov 5) University holiday. NO CLASS is held.

Try to catch up with any material. Ask questions on Piazza to clarify any issues. 

#### [Week 9: (Nov 12) Handling JSON and XML](Lectures/Week09/week09_lecture.md)

-   **Reading**:
    -   [Using R to download and parse JSON: an example using data from an open data portal](http://zevross.com/blog/2015/02/12/using-r-to-download-and-parse-json-an-example-using-data-from-an-open-data-portal/), by Zev Ross
    -   [Better handling of JSON data in R?](https://www.r-bloggers.com/better-handling-of-json-data-in-r/), by Rolf Fredheim
    -   [Introduction to `tidyjson`](https://github.com/jeremystan/tidyjson/blob/master/vignettes/introduction-to-tidyjson.Rmd), by Jeremy Stanley

-   **Datacamp**:
    - Chapter 3 of [_Working with Web Data in R_](https://www.datacamp.com/courses/working-with-web-data-in-r).
    
> **Homework 8**: [Writing a simple API client](Exercises/hw08/hw08.md). Also see the [homework submission instructions](Exercises/homework_submission_instructions.md).

#### [Week 10: (Nov 19) Web Scraping from HTML](Lectures/Week10/week10_lecture.md)

- **On your own:** Install the `rvest` package.  
-   **Reading**:
    -   [Using rvest to Scrape an HTML Table](https://www.r-bloggers.com/using-rvest-to-scrape-an-html-table/), by Cory Nissen
    -   [How To Screen-scrape](http://rpubs.com/chrisbail/screen_scraping_and_apis), by Chris Bail

-   **Datacamp**:
    - Chapters 4 and 5 of [_Working with Web Data in R_](https://www.datacamp.com/courses/working-with-web-data-in-r).
    
> **Homework 9**: [Web Scraping from Wikipedia](Exercises/hw09/hw09.md). Also see the [homework submission instructions](Exercises/homework_submission_instructions.md).

#### [Week 11: (Nov 26) SQL](Lectures/Week11/week11_lecture.md)

- **Reading**:
    - There are lots of great SQL Tutorials to go further. Here are a few pointers:
        - [Codeacademy's SQL Tutorial](https://www.codecademy.com/learn/learn-sql)
        - [SQLzoo's SQL Tutorial](https://sqlzoo.net/)
        - [W3School.com SQL reference](https://www.w3schools.com/sql) (also interactive)
    - Practice using [SQLZOO](http://sqlzoo.net/)
    
-   **Datacamp**:
    - If possible, complete [_Intro to SQL for Data Science_](https://www.datacamp.com/courses/intro-to-sql-for-data-science) before lecture. The course covers the set of commands for single table operations.
    - Joins in SQL are essential, especially given the usually _relational_ nature of the data. Cover joins and relational set theory in [_Joining Data in PostgreSQL_](https://www.datacamp.com/courses/joining-data-in-postgresql).
    
- **Advanced Topics (optional, on your own only)**:  
      - Try your hand on connecting to a remote SQL database of your choice.  
      
> **Homework 10**: [Practicing SQL Queries](Exercises/hw10/hw10.md). Also see the [homework submission instructions](Exercises/homework_submission_instructions.md).


### Part 3 - Other “Big Data” Considerations

#### [Week 12: (Dec 3) Amazon Web Services and Parallelization](Lectures/Week12/week12_lecture.md)

-   **Reading**:
    -   [A comprehensive beginner’s guide to start ML with Amazon Web Services (AWS)](https://www.analyticsvidhya.com/blog/2016/05/comprehensive-guide-ml-amazon-web-services-aws/) by Aarshay Jain
    -   [Analyzing Your Data on the AWS Cloud (with R)](https://www.r-statistics.com/2013/07/analyzing-your-data-on-the-aws-cloud-with-r/), by Tal Galili
    -   [Five ways to handle Big Data in R](https://www.r-bloggers.com/five-ways-to-handle-big-data-in-r/), by Oliver Bracht
    
-   **Online Tutorials (only recommended)**:  
    - [Launch a Linux Virtual Machine with Amazon EC2](https://aws.amazon.com/getting-started/tutorials/launch-a-virtual-machine/)
    - [Store and Retrieve a File with Amazon S3](https://aws.amazon.com/getting-started/tutorials/backup-files-to-amazon-s3)
    - [Create and Connect to a MySQL Database with Amazon RDS](https://aws.amazon.com/getting-started/tutorials/create-mysql-db)

-   **Datacamp**:
    - There is no AWS tutorial on Datacamp, but the course [_Scalable Data Processing in R_](https://www.datacamp.com/courses/scalable-data-processing-in-r) provides a good introduction on dealing with large-sized data.

- **Advanced Topics (optional, on your own only)**:  
    - Learn more about efficient coding in R. I recommend the chapters on "Efficient Coding" and "Efficient Optimization" from Gillespie, C., & Lovelace, R. (2017). Efficient R Programming: A Practical Guide to Smarter Programming (1 edition). Sebastopol, CA: O’Reilly Media. [Free online](https://csgillespie.github.io/efficientR/)
    - Additional coverage of Parallelization in R: McCallum, Q. E., & Weston, S. (2011). Parallel R: Data Analysis in the Distributed World (1 edition). Beijing: O’Reilly Media. [PDF free here](http://detritus.fundacioace.com/pub/books/Oreilly.Parallel.R.Oct.2011.pdf)
    - An extensive and well-written tutorial on parallelization: [Going beyond single-core R](https://ljdursi.github.io/beyond-single-core-R/#/) by Jonathan Dursi.

> **Final Project Proposal**: [Final Project Proposal due on Dec 1](Exercises/final_project/final_project.md).

#### [Week 13: (Dec 10) Big data access and computation](Lectures/Week13/week13_lecture.md)

-   **Readings on Algorithms**:
    -   [Basic Introduction into Algorithms and Data Structures](https://www.uni-oldenburg.de/fileadmin/user_upload/physik/ag/compphys/download/Alexander/dpg_school/LN_liers.pdf), by Frauke Liers
    - _Introduction to Pseudocode_ by Carnegie Mellon’s Robotics Academy

-   **Datacamp**:
    - The course [_Introduction to Spark in R_](https://campus.datacamp.com/courses/introduction-to-spark-in-r-using-sparklyr) is beyond what we can cover but provides a good start on Spark using R.
    
-   **Online Tutorials (only recommended)**:  
    - For Spark:
        - [RStudio Website with resources for Spark integration](https://spark.rstudio.com/)
        - [Apache Spark for R](http://spark.apache.org/docs/latest/sparkr.html)
        - RStudio Webinar [Using Spark with Shiny and R Markdown](https://www.rstudio.com/resources/webinars/using-spark-with-shiny-and-r-markdown/)
    - For BigRQuery: [Using R with Google BigQuery](https://cloud.google.com/blog/products/gcp/google-cloud-platform-for-data-scientists-using-r-with-google-bigquery)  
    - For GDELT:
        - [Brendan Knapp's brief analysis of the Syria conflict using GDELT here](https://rpubs.com/BrendanKnapp/GDELT_Syrian_Conflict)
        - RStudio Webinar [Working with Big Data in R](https://www.rstudio.com/resources/webinars/working-with-big-data-in-r/)
- **Advanced Topics (optional, on your own only)**:
    - [Running a cluster on AWS using Spark](https://spark.rstudio.com/examples/stand-alone-aws/)

> **Final Project due on Dec 17**: [Final Project Description](Exercises/final_project/final_project.md).

