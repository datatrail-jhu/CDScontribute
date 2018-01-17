# How to Contribute to the Chromebook Data Science project

## Content Development
### Where to find the content?
The most important way to contribute to the project at this point is content development. You can contribute by developing course lessons by choosing a lesson from the courses listed below and pushing your `.md` file to the corresponding course repository. Since others have already started contributing to course development, make sure no other person has already developed the course lesson by checking the course repository. Course repos are hosted here:

1. [Course I: Introduction and Setup]()
2. [Course II: Google and the Cloud](https://github.com/jhudsl/cds_googlecloud)
3. [Course III: Data]()
4. [Course IV: R]()
5. [Course V: MarkDown Basics](https://github.com/jhudsl/cds_markdownbasics)
6. [Course VI: Github Basics](https://github.com/jhudsl/cds_githubbasics)
7. [Course VII: Key Packages]()
8. [Course VIII: Getting Gelp](https://github.com/jhudsl/cds_gettinghelp)
9. [Course IX: Data Cleaning and Visualization & Case Studies]()

### Authorship Right
While you will be acknowledged in the course content, by contributing to this project you agree to transfer the ownership of the content to develop to Chromebook Data Science Project and Jeffrey T. Leek. Please make sure you read, fill out, and submit the form [here](https://goo.gl/forms/treKbfnliXDCqWhl2) before you start contributing to the project. Althogh our intent is to redirect revenues back to the project, there is some revenue generated from the project (mainly thought Leanpub). The transfer of authorship rights is to avoid the complexitiy that arises with the revenue generate from the project.

Please make sure to add your name at the end of the course lesson (item) that you develop. This is to help us better communicate with content creators for future references and to be able to acknowledge your work.

### Style
It is important that you avoid complicated language and write an easy-to-read lesson. The intent of this program is to educate individuals with little to no knowledge of computers and data science. The content is written in Markup languge called Markua. For a guide on how to write your lesson in Markua, check this [link](https://leanpub.com/markua/read#leanpub-auto-what-is-markua).

Keep the following items in mind for an easy-to-read lesson.
1. Avoid technical language!
2. Explain new concepts! If you refer to a technical term (e.g. `dplyr`, `baseR`, or `Data Viz`) be sure that those terms are clearly defined in previous courses or course items.
3. Do not introduce concepts, tools, or packages outside of the curriculum! A list of suggested courses and lessons are provided at the end of this document. If you have a suggesition for a course item, add and push it to this document for our consideration.
4. Use explanatory charts and graphs! And avoid using irrelevant graphics.
5. Make sure to add a quiz or assignment at the end of each lesson! Unless it is difficult to create a quiz on the content your wrote. Quizzes have two main purposes. a) to test learner's knowledge b) prevent learners from completing a course lesson without reading and understanding the content.
6. Use examples! Examples are a great way to learn.
7. Be aware of plagiarism and copyrighted content! Do not use any copyrighted third-party content and any content under Creative Content has to be commercial purposes as well. 
8. Cite! You are responsible to cite the sources that you use in your content. If it is an image, provide the link where you downloaded the image at the bottom. If you cite a blog post, journal article, video, or any other document, provide the link and the date you accessed the content.
9. Feel free to read the already existing contet on the Github repos above to have a sense of appropriate style.

### Formatting
Lessons should be written in Markdown and pushed to the `manuscript` folder in the related course repository. Please make sure to name the document starting with the lesson number (starting from 00) followed by "lesssonname". For instance, the lesson on Version Control in the Github Basics course is saved as `01_versioncontrol.md`.

Any image used in the course should be placed in the `img` folder of each course repository even if it is taken from online resources. Avoid importing images directly from urls since links may not be permanent. For naming, use a similar protocol. For instance, an image used in the Version Control lesson can be called `06_imagename.png` and should be placed in a subfolder called `01_versioncontrol` in the `img` folder. Make sure to link images in a relative format within your document.

### Third-party content copyright
As mentioned above, you can use content from outside sources ONLY if they are under CC BY Attribution license. The use of copyrighted material and content under CC BY NC is prohibited. 

## Chromebook Data Science Curriculum: Courses
### Course I: Introduction and Setup
- [ ] What to expect from the program?
- [ ] What is expected from you?
- [ ] What is data science?
- [ ] What is a chromebook?
- [ ] Getting logged on w/ account & w/o account
- [ ] How to setup wifi
- [ ] Tour of menus
- [ ] Personalization
- [ ] Where are the files stored? Google drive & local drive
- [ ] Apps (Circle menu)
- [ ] Common errors
- [ ] Updating your Chromebook
- [ ] What is a Chrome app
- [ ] Pixlr
- [ ] Suggested apps
- [ ] Working offline
- [ ] Your Coursera and DataCamp accounts
- [ ] Internet safety
- [ ] Ethics for data science
- [ ] Data privacy

### Course II: Google and the Cloud
- [x] What is the cloud?
- [x] Google Chrome
- [ ] Gmail/Inbox
- [x] Google Drive
- [x] Google Sheets
- [ ] Google Slides
- [x] Google Docs
- [x] Google Calendar
- [ ] Google Hangouts
- [ ] Google Maps
- [ ] Youtube
- [ ] Dropbox
- [ ] Internet friendly document formats
- [ ] Slack

### Course III: Data
- [ ] What is data? Part 1 (Types of data)
- [ ] What is data? Part 2 (Using data)
- [ ] What is data? Part 3 (Exploratory data analysis)
- [ ] Crazy internet files
- [ ] Incaps
- [ ] CSVs
- [ ] Excel files
- [ ] Where will files be online (database online, web pages, files)

### Course IV: R
- [ ] What is R?
- [ ] What is R used for?
- [ ] R versus other statistical software
- [ ] How to run R on chromebook
- [ ] Digital Ocean
- [ ] Tour of R Studio
- [ ] Getting data in
- [ ] Add on packages
- [ ] R Markdown
- [ ] R Reports
- [ ] Creating pdfs with R
- [ ] How to connect to Github
- [ ] Exporting R data to Google Sheets

### Course V: MarkDown Basics
- [ ] Introduction to MarkDown (Leah)
- [ ] Creating/Previewing a MarkDown file in RStudio (Leslie)
- [ ] Sharing a MarkDown document with others (Leslie)
- [ ] Inserting links/images
- [ ] Using MarkDown for reports
- [ ] Creating a website using MarkDown


### Course VI: Github Basics
- [ ] How to create an account
- [ ] Version control
- [ ] How to work with website
- [ ] What is a repository
- [ ] Create repository
- [ ] Edit repository
- [ ] Make an issue
- [ ] How to search for code
- [ ] Public vs private repos
- [ ] MarkDown (moved to module 5)
- [ ] Markdown editing (moved to module 5)

### Course VII: Key Packages
- [ ] dplyr
- [ ] tidyr
- [ ] ggplot
- [ ] readr
- [ ] stringr
- [ ] rvest
- [ ] rdrop2
- [ ] googlesheets
- [ ] xm12
- [ ] http
- [ ] lubridate
- [ ] viz
- [ ] plotly
- [ ] gganimate

### Course VIII: Getting Help
- [ ]

### Course IX: Data Cleaning and Visualization & Case Studies
- [ ] Data cleaning process (Messy vs Tidy)
- [ ] How to find R packages for different data types
- [ ] Rstats.cetfile
- [ ] How to make beautiful plots
- [ ] Pushing/Pulling on Github (Own repo and others)
- [ ] Common errors and conflicts

