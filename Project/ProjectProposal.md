# Project Proposal

There are four requirements that your proposed project must meet:

1. The goal of your project must be grounded in external reality, not in something that you have made up. In particular, your project must have one or more external customers who you believe actually need what you will build.  These can be actual people who you know (e.g., a friend of yours who needs a payroll management system for a startup they are creating), or it can be a group of people who you know about (e.g., first-year MIM students who want to be matched with second-year MIM students as mentors).  The person who needs what you will create cannot be a member of your team -- your project must be grounded in the real needs of others.
2. Your project must be designed for use in some organizational context.  This means, for example, that you can't create a video game for use by an individual.  But you could, for example, create a learning management system for use in a course.
3. You must use one or more technologies that we have studied (or will study) in this course.  Open possible choice would be a content management system for use by some actual organization.  Another would be a media monitoring system to detect and categorize brand mentions.  Just browse the list of topics for the course to see what most interests you, and then see what kind of an organizational need there might be for that kind of technoligy.
4. The goals must be suitably ambitious (substantially more ambitious than a homework assignment, for example). Specifically, the project should be scoped to be accomplished by four people working together for 6 weeks, each working a total of 7 hours per week. That's 168 person-hours, or roughly a person-month of effort (i.e., the scope of the project should be roughly what one professional could reasonably expect to achieve in a month of full time work).

You will be assigned to a specific role (project manager, designer, implementation lead, or implementor) on a specific project team by October 5, and your team will then have 13 days to prepare this project proposal.  We recommend that you discuss your project ideas with the professor before submitting the proposal because the timing allows for only one proposal submission -- in order to avoid a delayed start, proposals that do not meet the requirements will result in the professor assigning a project to the team. 

The project plan should be about 3 pages (single-spaced; please don't waste "paper" by double-spacing). It should identify the students and their assigned roles, specifically identify the external stakeholder(s) who need the project and the organizational context in which it will be used, describe the task that the project helps to accomplish and identify specific requirements for the system that will be built, describe the computational infrastructure needs of the project and how they will be satisfied, and include a schedule and a task division among the team members.

Only one project member needs to upload the project proposal to ELMS per project team.  Approvals or assignment to a different project are expected to be completed within at most four days so that you will have time to work on your detailed design.  At that time you will also be assigned a project mentor, who will either be the professor or the TA.  Your mentor will be your primary source for advice as you work on your project.

<div style="page-break-after: always"></div>

## Submission

Team 9

Angela Tseng

Yogesh Boricha

Abdul Shaik

Sadaf Davre

<p align="center"> Project Proposal </p>

Team 9 consists of 4 members. Angela Tseng acts as the Project Manager, monitoring
the activities of the team and supporting wherever is needed. Yogesh Boricha handles the role
of Designer, creatively. Sadaf Davre works as the Programmer, also known as the implementor.
As Programming Mentor, also known as the implementation lead, Abdul Shaik oversees the implementor.

The external stakeholders in this scenario would be the social media users who are
interested in fact checking the news that they get from their social media platforms. By simply
searching for the hashtags or some keywords related to the post they want to check on our
platform, they will pull up articles from reliable news outlets which would clarify if the news they
just saw was correct or false. This website will be used as a means to stop the spread of
misinformation on social media platforms. It will be implemented as a handy add-on feature for
the social media users concerned about the reliability of their viral feeds.

As a team, we are first going to extract top 100 hashtags which are related to social or
political events. These hashtags may have a specific indication or also may be a source that
creates misinformation on social media platforms. So, we will then undertake a comparison
analysis of these hashtags with reliable news platform sources which can help us to do
fact-checking. For example, #metoo tag went viral a couple of years back but it indicated a
different meaning when it was used popularly on social media. So, fact-checking will help us
with the correctness of information. To conclude, the primary goal of our task is to put out the
news article on a website which has more than 60% accuracy. The requirement for the project
would be a database management system to store and retrieve the data like Microsoft Access.
We will also use tools to do web scraping for extracting the data from a website.

We plan to develop a fact checking system via python and data mining. We will start off
by data extraction through popular social media platforms. To be more specific, we begin by
using Twitter as our primary source of hashtags. We build a simple hashtag extracter using the
tweepy library. Our goal here is to provide solid news sources. We are going to use the
PyGoogleNews module which acts as a wrapper library for the Google RSS feed. Once we do
this, we will need a database for information storage. For this, we will be using Access and
integrating with real-time data extraction and manipulation. Finally, in order to make it
user-accessible we plan to build this on a Drupal web page which will have the functionality to
be able to search through those hashtags.

|Date Due |Task |Parties Responsible|
| ----------- | ----------- |  ----------- |
|30 October |Requirements consolidation |PM|
|30 October |Website wireframing |Designer|
|30 October |Database design |Implementation Lead, Implementor|
|1 November |Project Detailed Design |PM, Designer,Implementation Lead, Implementor|
|6 November |Website programming |PM, Designer|
|6 November |Database programming |PM, Implementation Lead, Implementor|
|6 November |System description |PM|
|8 November |Prototype evaluation |PM, Designer, Implementation Lead, Implementor|
|11 November |Prototype fixing |PM, Designer, Implementation Lead, Implementor|
|15 November |Project Prototype |PM, Designer, Implementation Lead, Implementor|
|20 November |Prototype fixing |PM, Designer, Implementation Lead, Implementor|
|22 November |Prototype evaluation |PM, Designer, Implementation Lead, Implementor|
|26 November |Prototype finishing touches |Designer, Implementation Lead, Implementor|
|26 November |Project change documentation |PM|
|26 November |System documentation |Implementation Lead, Implementor|
|26 November |Project test plan/result documentation |PM, Designer, Implementation Lead, Implementor|
|29 November |Project Test Report |PM, Designer, Implementation Lead, Implementor|
|2 December |Slide deck design |PM, Designer|
|2 December |Documentation consolidation |PM|
|4 December |Slide content |PM, Designer, Implementation Lead|
|4 December |Demo creation |Implementation Lead, Implementor|
|4 December |Project reflection |PM, Designer, Implementation Lead, Implementor|
|6 December |Project Presentation |PM, Designer, Implementation Lead, Implementor|

Websites which we can use for coding and development:
1. https://medium.com/the-brainwave/how-to-get-trending-hashtags-on-twitter-in-2022-with-
python-ba4e18f3da64
2. https://python.plainenglish.io/building-a-news-scraping-twitter-bot-in-python-28eabe17823e
3. https://newscatcherapi.com/blog/python-web-scraping-libraries-to-mine-news-data

## Feedback
- try SolR and not Drupal
- database component not necessary
- this is a 3 part project; data parsing, database, and website
  - not feasible; pick one part to attempt

