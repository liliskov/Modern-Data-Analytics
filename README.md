# Modern-Data-Analytics
Exam Project GOZ39a

## Summary
There is no exam for this course, instead a project has to be handed in. The project involves a data analytics assignment. The projects are assigned (randomly) to the different teams :
*	Water Security
*	Uncovering the network
*	Politicians and Climate Change
*	Heat Waves Impacts
*	ECB Bond Purchases
* Cities and Greenhouse Gas Emissions

Each of the projects are described in detail in the appendices of this document. 

## Open Research Questions
The research questions are really "open". In other words: these are just a start. The same holds for the initial dataset. By no means are you restricted by the suggested data. On the contrary, a good data-scientist is capable to "think out of the box" and to retrieve data from other sources and blend these together.

The teaching team would be sad, if the only thing you achieved in our course, is producing a vanilla Jupyter Notebook where you make us some standard charts. With this course, you should have advanced much further on the learning curve.

## What do we expect from each Team ?
*	In a nutshell, we want you to think as a data-scientist throughout the whole production pipeline: retrieving & pre-processing data, exception handling, building a model, hyperparameter optimization, etc...
*	We expect that you bring the topics explained during the course into practice. Your team should be able to bring value to the data. You can use techniques that were not covered during the course and can bring other python packages into the project. 
*	Make sure you start from the same python environment, used in the course. Of course you can update packages, install new ones,...
*	Make sure that you understand the underlying mathematics in the approach that you use (supervised, unsupervised, nlp, AI,..). A data-scientist is much more than an expert in Sklearn, NLTK, Pytorch,etc...

## What do you need to hand in ?
The deliverables shall consist of:
*	a program (python only !)
*	a report
*	a presentation

## Deliverable
The project is a group-effort which has to result in Three deliverables
1.	Your Python Code shared on a GitHub account
This should be either Jupyter Notebook(s) or an App
2.	Report (pdf) of maximum 3 pages
3.	Each team will be invited for a presentation on-campus or on-line (teams are free to choose). 

## Presentation
I have asked the examination committee to schedule 4 days during which the presentations can take place (June). During this presentation the team will present their findings (15 min) and will answer questions (5 minutes). 

## Assigned Project
You will receive a mail before March 31st, with the project that has been assigned to your team.

## Delivery Date
Before June 1st, 2021
Failure to deliver the report in time, results in a no-pass grade for this course

## Delivery Mechanism
Each team will be assigned an S3-bucket on AWS. There is no need to have an AWS account yourself. The team-captains will receive an invite with access to the S3 buckets.
This bucket has three folders "data","code" and "report". 

### Data
In this folder you save all the data you have used (or links to the data) to solve your project

### Code
If you are not able to deliver your python code in a GitHub folder, you can use this folder in 	the AWS S3-bucket.

### Report
In this S3-bucket you can drop your report (pdf)

## Grading
*	15% on the presentation
*	20% on the written report
*	60% on the work done (project)
*	5% peer evaluation

## Grading Criteria 
Below is in bullet-point format a non-exhaustive list of the criteria that we will take into account when we evaluate your work.
### Modeling
*	Are you able to reach out to different data-sets outside the assigned dataset ?
*	Visualisation
*	Code: Style & Organisation of your Python Code. 
*	Does the code actually work ?
We should be able to clone your code on github and run it on our computer. Make sure that you use a requirements.txt file to specify the python packages you require.
*	Delivery App
If you deliver an App, the code should be on S3. The app should be deployed.
Note that after the Easter break, we plan a course on app-building in Python.
### Content of the report
*	Your pipeline : from retrieving data to the actual model
*	Introduction and problem statement
*	Research method & scientific character of the work done
*	Argumentation
*	Results: discussion / interpretation
*	General conclusion
*	Coherence / logical composition
*	Originality & creativity
*	References
### Presentation 
*	Presentation: used language
*	Presentation: content / accessibility
*	Presentation: form / composition / timing
*	Understanding underlying mathematics
*	Answering questions on Python and ML Code
## Failure
There are two ways to obtain a "no-pass" result:
*	Your project did not receive a pass grade
*	Your team did not hand in a report in time.

In case of a "no-pass" result, students can participate in the August exam. Here new projects will be made available. The August session will be individual, not in team work.

## Q&A
There will be extra Q&As where you can ask questions. The schedules of these Q&A's will be made available on Toledo. If you think that your question is too specific to be covered on the Q&A session, you can drop me an email.

 
# Topic
**Water Security**

Introduction
The current climate change scenario predicts that almost half of the world’s population will live in areas of high water stress by 2050 with limited access to fresh clean water. Governments, national, and international institutions, as well as water management companies, are looking for solutions that can address this growing global water demand. Cities are encouraged to take action on water security, to build resilience to water scarcity and manage this finite resource for the future. 

Proposed Research Question
Are all cities reporting consistent data ? Are there data gaps in some regions ? Can you predict the likelihood of a water shortage ? What about the population densities in those areas ?

Initial Data Set
The place to start your enquiry is (data.cdp.net and www.cdp.net). The climate disclosure panel (CDP) is a not-for-profit charity that runs the global disclosure system for investors, companies, cities, states and regions to manage their environmental impacts. The data for cities and regions is free for access & downloading.
