# Module 1 Final Project

## Introduction

Want to understand better understand which movies you may want to invest in? This repo contains just that information.

## Contents

- student.ipynb
This is a jupyter notebook that contains all of the code involved in performing the data analysis

- what kind of movie should you invest in.ppt
A powerpoint presentation


## Summary

Movie genre
Gross profit margin indicates that these top 5 genres are the movies wth the highest profit margin.

![alt text]https://github.com/jefferyrosario/dsc-mod-1-project-v2-1-onl01-dtsc-pt-012120/blob/master/genre_gross_profit.png


https://github.com/learn-co-curriculum/dsc-mod-1-project-v2-1/blob/master/module1_project_rubric.pdf

## The Project

Microsoft sees all the big companies creating original video content, and they want to get in on the fun. They have decided to create a new movie studio, but the problem is they don’t know anything about creating movies. They have hired you to help them better understand the movie industry.
Your team is charged with doing data analysis and creating a presentation that explores what type of films are currently doing the best at the box office. You must then translate those findings into actionable insights that the CEO can use when deciding what type of films they should be creating.

# The Dataset

You may scrape or make API calls to get additional data, but included in the repository (in the folder `zippedData`) is some movie-related data from:
* Box Office Mojo
* IMDB
* Rotten Tomatoes
* TheMovieDB.org

# The Deliverables

For online students, there will be five deliverables for this project (Note: On-campus students may have different requirements, please speak with your instructor):

1. A well documented **Jupyter Notebook** containing any code you've written for this project and comments explaining it. This work will need to be pushed to your GitHub repository in order to submit your project.  
2. An organized **README.md** file in the GitHub repository that describes the contents of the repository. This file should be the source of information for navigating through the repository.
3. A short **Keynote/PowerPoint/Google Slides presentation** (delivered as a PDF export) giving a high-level overview of your methodology and recommendations for non-technical stakeholders. Make sure to also add and commit this pdf of your non-technical presentation to your repository with a file name of presentation.pdf.
4. **[A Blog Post](https://github.com/learn-co-curriculum/dsc-welcome-blogging-v2-1)**
5. A **Video Walkthrough** of your non-technical presentation. Some common video recording tools used are Zoom, Quicktime, and Nimbus. After you record your presentation, publish it on a service like YouTube or Google Drive, you will need a link to the video to submit your project.

Note: On-campus students may have different requirements, please speak with your instructor.

### Jupyter Notebook Must-Haves

For this project, your Jupyter Notebook should meet the following specifications:

#### Organization/Code Cleanliness

* The notebook should be well organized, easy to follow,  and code should be commented where appropriate.  
    * Level Up: The notebook contains well-formatted, professional looking markdown cells explaining any substantial code.  All functions have docstrings that act as professional-quality documentation
* The notebook is written for technical audiences with a way to both understand your approach and reproduce your results. The target audience for this deliverable is other data scientists looking to validate your findings.

#### Visualizations & EDA

* Your project contains at least 4 meaningful data visualizations, with corresponding interpretations. All visualizations are well labeled with axes labels, a title, and a legend (when appropriate)  
* You pose at least 3 meaningful questions and answer them through EDA.  These questions should be well labeled and easy to identify inside the notebook.
    * **Level Up**: Each question is clearly answered with a visualization that makes the answer easy to understand.   
* Your notebook should contain 1 - 2 paragraphs briefly explaining your approach to this project.


### Non-Technical Presentation Must-Haves

Another deliverable should be a Keynote, PowerPoint or Google Slides presentation delivered as a pdf file in your fork of this repository with the file name of `presentation.pdf` detailing the results of your project.  Your target audience is non-technical people interested in using your findings to make decisions for creating movies.

Your presentation should:

* Contain between 5 - 10 professional-quality slides.  
    * **Level Up**: The slides should use visualizations whenever possible, and avoid walls of text.
* Take no more than 5 minutes to present.   
* Avoid technical jargon and explain the results in a clear, actionable way for non-technical audiences.   

### Blog Post Must-Haves

Refer back to the [Blogging Guidelines](https://github.com/learn-co-curriculum/dsc-welcome-blogging-v2-1) for the technical requirements and blog ideas.



## The Process
(Note: On-campus students may have different processes, please speak with your instructor)

### 1. Getting Started

Please start by reviewing this document. If you have any questions, please ask them in Slack ASAP so (a) we can answer the questions and (b) so we can update this repository to make it clearer.

Be sure to let the instructor team know when you’ve started working on a project, either by reaching out over Slack or, if you are in a full-time or part-time cohort, by connecting with your Cohort Lead in your weekly 1:1. If you’re not sure who to reach out to, post in the #online-ds-sp-000 channel in Slack.

Once you're done with the 10 sections in module 1, please start on the project. Do that by forking this repository, cloning it locally, and working in the `student.ipynb` file. Make sure to also add and commit a pdf of your presentation to the repository with a file name of `presentation.pdf`.

### 2. The Project Review

_Note: On-campus students may have different review processes, please speak with your instructor._

> **When you start on the project, please also reach out to an instructor immediately to schedule your project review** (if you're not sure who to schedule with, please ask in Slack!)

#### What to expect from the Project Review

Project reviews are focused on preparing you for technical interviews. Treat project reviews as if they were technical interviews, in both attitude and technical presentation *(sometimes technical interviews will feel arbitrary or unfair - if you want to get the job, commenting on that is seldom a good choice)*.

The project review is comprised of a 45 minute 1:1 session with one of the instructors. During your project review, be prepared to:

#### 1. Deliver your PDF presentation to a non-technical stakeholder.
In this phase of the review (~10 mins) your instructor will play the part of a non-technical stakeholder that you are presenting your findings to. The presentation  should not exceed 5 minutes, giving the "stakeholder" 5 minutes to ask questions.

In the first half of the presentation (2-3 mins), you should summarize your methodology in a way that will be comprehensible to someone with no background in data science and that will increase their confidence in you and your findings. In the second half (the remaining 2-3 mins) you should summarize your findings and be ready to answer a couple of non-technical questions from the audience. The questions might relate to technical topics (sampling bias, confidence, etc) but will be asked in a non-technical way and need to be answered in a way that does not assume a background in statistics or machine learning. You can assume a smart, business stakeholder, with a non-quantitative college degree.

#### 2. Go through the Jupyter Notebook, answering questions about how you made certain decisions. Be ready to explain things like:
    * "How did you pick the question(s) that you did?"
    * "Why are these questions important from a business perspective?"
    * "How did you decide on the data cleaning options you performed?"
    * "Why did you choose a given method or library?"
    * "Why did you select those visualizations and what did you learn from each of them?"
    * "Why did you pick those features as predictors?"
    * "How would you interpret the results?"
    * "How confident are you in the predictive quality of the results?"
    * "What are some of the things that could cause the results to be wrong?"

Think of the first phase of the review (~30 mins) as a technical boss reviewing your work and asking questions about it before green-lighting you to present to the business team. You should practice using the appropriate technical vocabulary to explain yourself. Don't be surprised if the instructor jumps around or sometimes cuts you off - there is a lot of ground to cover, so that may happen.

If any requirements are missing or if significant gaps in understanding are uncovered, be prepared to do one or all of the following:
* Perform additional data cleanup, visualization, feature selection, modeling and/or model validation
* Submit an improved version
* Meet again for another Project Review

What won't happen:
* You won't be yelled at, belittled, or scolded
* You won't be put on the spot without support
* There's nothing you can do to instantly fail or blow it

**Please note: We need to receive the URL of your repository at least 24 hours before and please have the project finished at least 3 hours before your review so we can look at your materials in advance.**


## Submitting your Project

 You’re almost done! In order to submit your project for review, include the following links to your work in the corresponding fields on the right-hand side of Learn.

 1. **GitHub Repo:** Now that you’ve completed your project in Jupyter Notebooks, push your work to GitHub and paste that link to the right. (If you need help doing so, review the resources [here](https://docs.google.com/spreadsheets/d/1CNGDhjcQZDRx2sWByd2v-mgUOjy13Cd_hQYVXPuzEDE/edit#gid=0).)
_Reminder: Make sure to also add and commit a pdf of your non-technical presentation to the repository with a file name of presentation.pdf._
2. **Blog Post:** Include a link to your blog post.
3. **Record Walkthrough:** Include a link to your video walkthrough.

 Hit "I'm done" to wrap it up. You will receive an email in order to schedule your review with your instructor.

## Grading Rubric

Online students can find a PDF of the grading rubric for the project [here](https://github.com/learn-co-curriculum/dsc-mod-1-project-v2-1/blob/master/module1_project_rubric.pdf). On-campus students may have different review processes, please speak with your instructor.


