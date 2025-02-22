---
layout: page
title: Project Final Deliverable
permalink: /Assignments/project-deliverable
parent: Assignments
nav_order: 6
---
# Project: Final Deliverable **Due Wednesday November 30, 11:00am EDT**{: .label .label-red }
The final project deliverable is the implementation, available in github and deployed on Netlify and Heroku, and the documentation turned in to Canvas. It also includes demos and/or posters.

# Project Implementation and Documentation

Your final team deliverable will be a "release" of your new feature on GitHub (with tests), and will be accompanied by a demo.
*Optionally,* you may also open a pull request to merge your feature into our main repository (submitting a pull request, or the pull request being merged into our
codebase is independent of the grade you receive, but provides a platform for more visibility of your project). 

## Contents

Your final team deliverable will include:
* The implementation of your new feature, deployed to Netlify + Heroku
* Automated tests for your new feature
* A report that describes how to use your new feature
* A poster
    
Accompanying the final team deliverable will be an *individual reflection*, which every student must submit on their own which will include your reflections on:
* The evolution of your project concept: How does the project that you delivered compare to what you originally planned to deliver? What caused these deviations?
* The software engineering processes that you feel could have been improved in your project: were there any processes that in hindsight, you wish that you followed, or wish that you followed better?
* Your team dynamic: Provide a frank (and ideally, blameless) postmortem of your and your teammates collaborative performance and participation. If you had to do this same project over with the same teammates, what would *you* have done differently (or not) to improve your team's overall performance?


### Submission Instructions

#### Code and documentation
 After you have pushed all of your code (and documentation) to your team's GitHub repository, create [a release](https://docs.github.com/en/free-pro-team@latest/github/administering-a-repository/managing-releases-in-a-repository) on GitHub, and apply the tag version `final-submission`. After your release is created, you'll find that there is now a `.zip` that can be downloaded from GitHub that contains a snapshot of your entire repository. Download this zip file, unpack it, and follow the instructions that you provided in your README to double-check that the course staff will be able to run your project (this step is handy to make sure that you didn't forget to include some key files in git). If needed, you can delete the release, make some changes, and re-release up until the deadline. **Submit this zip file to Canvas** under the assignment "Project: Code Submission". Submit your report separately to Canvas, under the assignment "Project: Report".

#### Project Poster & Demo
Each team will submit a poster. Your poster will be a single-page document, that will include the following aspects:

* Short description of the project (OK to reuse text from the project plan/report)
* Link to public demo site, link to source repo (OK to make the repo public now, or OK to leave as private)
* Short description of the technology stack and overall design decisions
* Short description of future work that could build on your project - additional features that you think could be interesting, or ideas for refactoring the code.
* Screenshots of the feature, visually demonstrating the main functionality that you implemented.

We've created a [sample poster for the "Conversation Areas" feature]({{ site.baseurl }}{% link Examples/conversation-areas-poster.pdf %}), which you might find useful in deciding how to format your poster. It's fine to use a different aspect ratio (e.g. portrait instead of landscape), and there are no specific requirements for font size or amount of text. Please try to create a document that you feel represents your project, imagine your target audience as a recruiter for a software engineering role: your goal is to demonstrate that you have some experience working on some non-trivial software engineering project.

Some sections will have live (in-person) demos and others may ask you to record a demo video. Details for project demos will be provided during class by each instructor. **Posters and/or demo videos (and presentations) will be submitted on Canvas**, under the assignment "Project: Poster / Demo".
 
#### Individual Reflection
Create a PDF of your reflection, and submit it to Canvas, under the assignment "Project: Individual Reflection". 

## Grading
Each project will be graded by the team's assigned TA mentor and the instructor. We do not expect all teams to deliver all of the features that were initially proposed - in the five-week implementation period, there are sure to be some teams that encounter unexpected technical hurdles. As described in greater detail in the rubrics below, teams that have regular communication with their TA regarding their project status may be permitted variances to their project scope. For most of the submission components below, we provide two benchmark rubrics: one for a submission that is satisfactory (full marks), and one that would be meeting our minimum expectations (a pass). Rubric for remaining components will be provided by individual instructors. In practice, when grading projects we will usually assign numeric grades and provide partial credit, using these rubrics as guidelines for those two extremes. 

In cases where team members do not equally contribute to the project, we may assign different grades to different individuals, up to an extreme of deducting 50% of the marks from a student. We will evaluate each individual's contribution on the basis of a variety of factors, including progress reports at weekly meetings, through inspecting version control history, through each student's self-reflection, and through each team's (or student's) peer evaluations during and/or at the end of the project. We will make regular efforts to collect and distribute this feedback throughout the project. Our ultimate goal is for all students to participate and receive full marks.

### Summary of grading
* Planning Documents
  * 10% Preliminary Project Plan (already graded)
  * 10% Revised Project Plan (already submitted)
* Activities During the Project
  * 10% Weekly Meetings with TA Mentor and Team Surveys
  * 5% Ongoing development progress, including code reviews
* Final Deliverables
  * Code 
    * 20% Final implementation of your feature
    * 10% Final test suite of your feature
  * Report
    * 5% Feature Overview
    * 10% Technical Overview
    * 10% Process Overview
  * 10% Demonstration & Posters

This adds up to 100%; this sum is worth 40% of the course grade.

Here are the detailed rubrics for the final deliverables:
### 20% Delivered Features 
We will grade each delivered project holistically using the following two rubrics:

#### Satisfactory:
* Implemented feature satisfies the conditions of satisfaction as proposed by the team and as agreed to by the course staff. If technical difficulties resulted in features being dropped, the project may still earn full marks on "delivered features," but these difficulties must have been documented with the course staff as you encountered them during development.
* Implemented feature is deployed to a publicly-accessible URL, using Netlify and Heroku for hosting. Detailed instructions for deployement will be supplied later.
* Implemented feature contains no ESLint warnings or errors; does not include any eslint-disable or ts-ignore flags

#### Meets minimum requirements:
* Implemented feature largely satisfies acceptance criteria as proposed by the team, but may not meet the course staff’s interpretation of those criteria.
* Implemented feature is deployed to a publicly-accessible URL, using Netlify and Heroku for hosting. Detailed instructions for deployement will be supplied later.
* The implementation may have some obvious flaws, but largely works without crashing.
* Implemented feature does not include any eslint-disable or ts-ignore flag

### 10% Testing
The project must include evidence of testing. Ideally, all new features will be accompanied by fully automated tests, but in some circumstances (particularly when engaging with Phaser, the game library, or Tiled, the map editor), this may not be feasible. If automated tests are not possible, include a discussion of your manual testing strategy, including a script that a future developer could use to manually test the feature.

#### Satisfactory:
* Any new or modified backend features include tests that validate that the feature works as intended. These tests cover the changed code, and also contain well-written assertions that thoroughly check the expected behaviors.
* Tests contains no ESLint warnings or errors; does not include any eslint-disable or ts-ignore flags

#### Meets minimum requirements:
* Any new or modified backend features include at least one test, which may or may not be an effective test.
* Tests may contain ESlint warnings (but no errors); does not include any eslint-disable or ts-ignore flags

### Activities During the Project


#### 10% Weekly Meetings with TA Mentor and Team Surveys
Throughout the semester, each team will be meeting with their TA mentor and with the instructor to discuss their project progress. Attendance at these meetings and demonstrations of progress will, cumulatively, account for 10% of the project grade. You will also be asked to complete Team Surveys and/or Peer evaluations to help track the progress. Each instructor will provide a more detailed rubric for this section of the assignment.

#### 5% Ongoing development progress, including code reviews
Each team is expected to use their GitHub repository, regularly committing changes while developing their project. You will also be expected to use pull-requests and code reviews.

##### Satisfactory:
* There is a clear development history visible from the git repository: features were delivered incrementally, and not in a single (or several) commits at the end of the project
* There is evidence of code review - for example, pull requests that have comments on them
* There is a correspondence between commit messages and the technical tasks that they are associated with; there are few (if any) commits with meaningless commits messages like `.` or `Add files via upload`.
* Each team member has made at least 4 commits over the lifespan of the project

##### Meets minimum requirements:
* There is a clear development history visible from the git repository: features were delivered incrementally, and not in a single (or several) commits at the end of the project
* Each team member has made at least 2 commits over the lifespan of the project

### Final Report 
The final report should consist of three sections:

#### 5% Report -- Feature Overview

##### Satisfactory:
* The Feature section contains sufficient documentation for a user to interact with your updated version of Covey.Town.
* The documentation covers all steps that the user would need to take to exercise all of your user stories.
* Screenshots are included that capture the key interactions between a user and your new feature.
* Course staff were able to follow these instructions to successfully interact with your project implementation.
* The section is at most 4 pages (roughly 2,000 words maximum), NOT including figures. Fewer pages are absolutely acceptable, consider this a rough limit

##### Meets minimum requirements:
* The Feature contains documentation for a user to interact with your updated version of Covey.Town, but perhaps does not fully describe how.
* The documentation includes at least one or two screenshots, but screenshots do not capture interactions with all of the user stories.
* The course staff were able to figure out how to use it through trial and error.
* The section is at most 4 pages, NOT including figures. Fewer pages are absolutely acceptable, consider this a rough limit

#### 10% Report - Technical Overview
##### Satisfactory:
* Technical Overview contains a description of any substantive changes to the existing Covey.Town codebase, and of the architecture of your new code.
* It uses UML diagrams, CRC cards, state diagrams or any of the other techniques that help describe the structure.
* It provides a well-reasoned rationale for why this is the "right" design. 
* The document is at most 2 pages (fewer pages are absolutely acceptable, consider this a rough limit) 
##### Meets minimum requirements:
* Technical Overview includes a description of all major changes to the code compared to our existing Covey.Town codebase.
* The document is at most 2 pages (fewer pages are absolutely acceptable, consider this a rough limit) 

#### 10% Process Overview
##### Satisfactory:
* Process overview contains a detailed description of the manner in which agile project management processes were used during the project (i.e., sprints, sprint reviews, retrospectives and blameless reviews).
* It provides a summary of what was planned to happen in each sprint vs what actually happened, with a discussion of what was revised as a result. 
* The document is at most 2 pages (fewer pages are absolutely acceptable, consider this a rough limit) 

#### Meets minimum requirements:
* It provides a summary of what was planned to happen in each sprint vs what actually happened, with a discussion of what was revised as a result. 
* The document is at most 2 pages (fewer pages are absolutely acceptable, consider this a rough limit) 

### 10% Demonstration / Posters
Each team will be required to submit a poster. In addition, some sections may have a demo (live in-person, via zoom or by recorded video). Each instructor will provide details regarding expectations for the demo and/or presentation. The schedule and manner of these demos might also vary from section to section.

Select projects will be hosted in our project showcase. Here are the projects from Spring 2022 [project showcase](https://neu-se.github.io/CS4530-Spring-2022/assignments/project-showcase).

## Individual Reflection

Accompanying the final team deliverable will be an individual reflection, which every student must submit on their own.
Satisfactory completion of all parts of this reflection is required to receive an "A" grade in the course, and may be used to calibrate project scores across multiple team members.
The individual reflection also provides an opportunity for students to provide confidential feedback on the performance of their teammates.

### Project Concept

Reflect on the evolution of your project concept: How does the project that you delivered compare to what you originally planned to deliver? What caused these deviations?

#### Satisfactory:
* Is at least 2 paragraphs long;
* Includes at least 1 paragraph describing all variances from original project concept;
* Includes at least 1 paragraph of personal reflection on the cause of any variances from the project concept.

### Project Process

Reflect on the evolution of your development process: How did the process by which you designed and implemented evolve from your original project plan? Were there any processes that in hindsight, you wish that you followed, or wish that you followed better?

#### Satisfactory:
* Is at least 2 paragraphs long;
* Includes at least 1 paragraph describing all variances from the software development processes envisioned in your original project plan;
* Includes at least 1 paragraph describing software processes (described in class or not) that you wish you had followed, or wish you had followed better, supported by evidence from your personal experience working on the project.

### Project Team

Reflect on your team dynamic: Provide a frank (and ideally, blameless) postmortem of your and your teammates collaborative performance and participation. If you had to do this same project over with the same teammates, what would you have done differently (or not) to improve your team’s overall performance? Do you think that each of your teammates are deserving of the same grade as you?

#### Satisfactory:
* Is at least 2 paragraphs long;
* Includes at least 1 paragraph reflecting on your own performance as a team member on this project, including what you would have done differently, given what you know now;
* Includes at least 1 paragraph reflecting on your overall team dynamic, including strengths and weaknesses. Reflect on how you might have organized your team differently given what you know now.


### Change Log
* 10/26: Initial Release
* 10/29: Added details about the poster 

