---

title: "Session 1: Introduction to SCINet with lightning presentations"
author: Moe Richert
excerpt: This page contains all the info you need to participate in Session 1 of the SCINet Geospatial Workshop 2020.
categories: [Geospatial Workshop]  
provider: Geospatial Working Group
type: workshop
tags: Geospatial
layout: nav

sessions:
  - session: 
    time: 11:00am-1:00pm MDT
 #   instructor: placeholder
    register: No registration required
 #   register_url: https://kerriegeil.github.io/SCINET-GEOSPATIAL-RESEARCH-WG/

alerts: 
  - alert: 
    type: info
    slim: true
    text: Zoom session recording (USDA eAuthentication required)
    href: https://web.microsoftstream.com/video/e469908f-bc92-4199-a875-21f513c113b2
  - alert:
    type: info
    slim: true
    text: Zoom session chat
    href: https://kerriegeil.github.io/SCINET-GEOSPATIAL-RESEARCH-WG/docs/2020-08-25_SCINet-Geospatial-WG_Workshop-Session1-Annual-Meeting_CHAT.txt

subnav:
  - text: Tutorials
    href: '#tutorials'
  - text: Access to the SCINet Ceres HPC System
    href: '#access-to-the-scinet-ceres-hpc-system'
  - text: Software + Hardware + Nomenclature Overview
    href: '#software-+-hardware-+-nomenclature-overview'


---

<br>

## Session Rules

<br>
{:.border-bottom}

CHAT QUESTIONS/COMMENTS TAKE FIRST PRIORITY - Chat your question/comments either to everyone (preferred) or to the chat moderator (Rowan Gaffney) privately to have your question/comment read out loud anonamously. We will answer chat questions first and call on people who have written in the chat before we take questions from raised hands.

SHARE YOUR VIDEO WHEN SPEAKING - If your internet plan/connectivity allows, please share your video when speaking.

KEEP YOURSELF ON MUTE - Please mute yourself unless you are called on.

## What is the SCINet Geospatial Research Working Group?

<br>
{:.border-bottom}

See our working group page on the SCINet website.

Our main goals are to:
* provide continued input on the development of SCINet,
* improve the computational capacity of ARS geospatial researchers, and
* develop collaborative research projects.

The goals of the 2020 workshop are to:
* provide hands-on learning using the Ceres high-performance computing (HPC) system to conduct geospatial and machine learning research,
* foster research efforts that had previously been un-attainable due to technical limitations or inexperience, and
* inspire new research ideas and collaborations.



## Review of the 2019 Workshop

<br>
{:.border-bottom}

2019 Workshop Agenda and Participants (opens pdf)

2019 Workshop Notes (opens pdf)


At last year’s workshop we:
* heard from ARS scientists about successes and challenges of using SCINet for geospatial analysis,
* identified common issues and barriers to using SCINet for geospatial research workflows,
* generated recommendations for overcoming these issues/barriers,
* created the SCINet Geospatial Research Working Group to follow through with workshop recommendations, and
* learned about machine learning, deep learning, and some of the ways ML/DL are being used for research at New Mexico State University and the Jornada Experimental Range.


Computational Needs of the ARS Geospatial Research Community:

* data access, sharing, and storage
    * securely store data
    * rapid access to data
    * share large data files that aren’t publicly available
    * make research data publicly assessible (distribution and archiving)
    * access to AgCROS and PDI data servers from SCINet
    reproducibility and collaboration
    * improve data provenance and versioning
    * collaborate on models and code development in real time
    computation and data manipulation
    * explore/visualize large data
    * build capacity for using SCINet/HPC and knowing when to use
    * cloud computing and storage for operational projects with large input and output data
    * decision support/agro-informatics applications for our stakeholders


Recommendations for improving access to SCINet HPC/cloud computing and enhancing general computational skill in the ARS geospatial research community:

Key: progress made in FY20, progress beginning FY21

A) Improve data access, sharing, and storage.

* Implement better methods for getting massive input data into the computational environment.
* Build/expand higher speed connections to SCINet.
* Build a common data library on SCINet to reduce duplication of popular datasets and reduce the barrier to adopting HPC workflows.
* Hold trainings in data management for long-term datasets and archiving of data from retired scientists.

B) Enhance reproducibility of our science and increase collaboration.

* Hold trainings on using Git, containers, and other reproducibility tools.
* Hold hands-on group work sessions in R and Python.

C) Build capacity for using HPC/cloud computing.

* Hold trainings on how to access and compute on the SCINet HPC systems (including how to parallelize code) to reduce the learning curve.
* Develop a collection of tutorials from ag/geo-relevant applications with example scripts that run on the SCINet HPCs, including ML/DL techniques. (Geospatial Workbook)
* Hire personnel, including postdocs, with multi-disciplinary computational backgrounds.
* Hold trainings in R, Python, and Unix through The Carpentries or similar.
* Repeat the 2019 AI Training by Adam Rivers and University of Florida collaborators.
* Hold trainings in image processing.

D) Expand SCINet HPC system software, hardware, and support to focus on our research community needs.

* Contract a “GeoTeam” that would help our research community with workflow development, parallelization, and code optimization.
* Deploy a better forum for searchable SCINet questions/answers.
* Purchase community GPUs when the priority GPU gets to be a limited resource.
* Install Pix4D Engine software on SCINet.

return to agenda

## Details on the Upcoming 2020 Sessions

<br>
{:.border-bottom}

The following links will take to you to our workshop homepage where you can register for each session if you haven’t already.

If you are unable to join a session, you will still be able to access and work through all the tutorials on your own using the session tabs at the top of our workshop homepage. We will also eventually make the Zoom recordings available as well.

* 8/27/2020, 11am-1pm MDT, Session 2: Tutorial: Intro to the Ceres HPC System Environment

* 8/27/2020, 1:30-2:30pm MDT, Session 3: Tutorial: Intro to Distributed Computing on the Ceres HPC System Using Python and Dask

* 8/28/2020, 10:30am-12:30pm MDT, Session 4: Tutorial: Computational Reproducibility Tools

* 8/28/2020, 1:00-2:30pm MDT, Session 5: Tutorial: Distributed Machine Learning: Using Gradient Boosting to Predict NDVI Dynamics

* 9/1/2020, 11am-2pm MDT, Session 6: Symposium: Challenges and opportunities in leveraging machine learning techniques to further sustainable and intensified agriculture

### Preparation for the tutorial sessions (2, 3, 4, 5)

The most important item is make sure you can successfully login to your SCINet account before (preferably days before) the tutorials start. There are many tutorial registrants with expired passwords that may need assistance from the SCINet Virtual Research Support Core (VRSC) if old passwords have been forgotten. If it’s your first time logging in, use the Quick Start Guide and if you are still having trouble and contact the VRSC for help scinet_vrsc@usda.gov.

Try to set yourself up on a large monitor or Google how to connect your laptop to your tv. Ideally, you will want enough screen space to have a side by side set up where one side is the live Zoom session and the other side you can have JupyterLab open in a browser window so you can work through the tutorials in real time. This set up is nearly impossible on a laptop screen alone.

If you plan to follow along with the Git/Github portion of the Session 4 Tutorial: Computational Reproducibility Tools, Create a free personal Github account. Make sure you remember your Github username and password.

Lastly, visit the premeeting page to familiarize yourself with the software/HPC terminology that will be used in the tutorial sessions.

## Other Upcoming Activities of the Working Group

We’re planning to hold a working group Zoom session quarterly at minimum (monthly if we have enough content ideas).

The sessions could include:

* research presentations from inside or outside ARS,
* short tutorials or demonstrations of software or computational techniques,
* productivity presentations such as
    * how to design collaborative research,
    * how to make better scientific figures/presentations,
    * reproducible workflow techniques and HPC etiquette, etc.
* working sessions for
    * common data library
    * geospatial workbook
    * bring your own coding question/data problem
* development of new cross-location research ideas

Discussion Question: What content would you like to see in quarterly working group meetings?

Discussion Notes:

* ENVI/IDL training/tutorials for satellite data processing
* Sessions for informal coding questions in various languages
* Session on data persistence on Ceres. For example, if a model outputs a large amount of results how long can this data stay on CERES? Does it stay for the lifecycle of the study which could be multiple years? Or how do we design the studies to account for the data storage?

return to agenda

## Introduction to the SCINet Postdocs

<br>
{:.border-bottom}

The first cohort of postdocs funded by the SCINet Computing Initiative has arrived at ARS! SCINet postdocs are tasked with developing cross-site collaborative research projects that utilize the ARS SCINet high-performance computing resources. They will also contribute to non-research projects that further the SCINet Computing Initiative such as the SCINet website, newsletter, and various computational trainings. Here is a short introduction to everyone.

## Working Session: SCINet Common Data Library

<br>
{:.border-bottom}

Lead: Yanghui Kang, SCINet Postdoc

During the 2019 SCINet Geospatial Workshop, the working group identified the need to develop a shared repository to serve commmonly used geospatial datasets to ARS users. The common data library/repository aims to enable easy access to popular datasets and reduce the barrier of adoption for SCINet HPC clusters. Before the 2020 SCINet Geospatial Workshop, we invited the working group and workshop participants to complete a survey about the data and computational needs of ARS geospatial researches and applications. In this session, we will present the preliminary results of the survey and discuss important aspects of the common data library development.

Tentative Agenda

* Brief introduction (5 mins)
* Preliminary results of the SCINet Geospatial Data and Computational Needs Survey (10 mins)
* Discuss (45 mins)
    * What kind of datasets and which ones will be stored on the clusters?
    * How to store, manage, and serve data to the users?
    * How to allow easy access to data that does not make it to the library/repository?
    * Other topics brought by the audience …

Discussion Notes:

Q: Will the Common Data Library offer security for highly sensitive data?

A: We Will probably only store publicly available data in the common data library. The library will be accessible by everyone on Ceres so we won’t be able to put data with PII or other sensitive data in it. Developing a shared spaced for sensitive data with access available only to a small group of Ceres users should be spearheaded by those with the sensitive data with assistance from the SCINet VRSC.

Q: Can we store high spatial or high temporal resolution data in the common data library?

A: We are not creating a data center and do not know how much storage we will have on SCINet for the common data library. We will need to communicate our needs to SCINet leadership and work with them to have space carved out for the libary. We will certainly not be able to store very large data (i.e. the LandSAT archive), but may store subsets of large dataset. For example, for a large dataset organized by site, we could store one site and then share a code/workflow for accessing/downloading the data from other sites. These types of details will be worked on in follow-on meetings about the common data library.

Q: What is the relationship between SCINet and the authors of the datasets we store there and how do we site data from the common data library?

A: We are intending to store mostly publicly available data in the common data library. There would be no relationship between the data author and SCINet. You would cite data you used from the common data library in the manner that is requested by the data authors- referencing the original source of the data, not the common data library. Maybe the common data library should provide metadata on how to cite each dataset. You should also be citing/acknowledging your use of SCINet- guidance on acknowledging SCINet can be found in the SCINet Quick Start Guide.

Q: How do we deal with updated versions of datasets?

A: We will have to store metadata including download date, version, etc.

C: Some datasets already have good APIs for obtaining the data – this should be considered when deciding which data to host. For example if you just need timeseries for individual locations from daymet, their API can provide this in a few minutes. But MODIS datasets have always been a pain to obtain, so that would be a great one to host.

Q: After downloading, it can be quite time consuming to stitch together raster datasets that are distributed as tiles (like aerial imagery). Would the common data library provide access to the individual tiles or could there be an option to obtain a larger spatial area as one raster file?

A: This is probably out of scope for the common data library project, but depending on how the project develops we could possibly add this to a future wish list.

return to agenda

## Working Session: Geospatial Workbook

<br>
{:.border-bottom}


Lead: Kerrie Geil, SCINet Postdoc

One product generated by our working group will be the geospatial workbook, which will be an online resource with all kinds of useful information for the USDA-ARS geospatial research community. Styled after the bioinformatics workbook, the geospatial workbook will contain computing and data visualization tutorials, research best practices, and more. This effort is just beginning, lead by Kerrie Geil and Andrew Severin, but we hope to have contributions from many of the working group members.

Discussion Questions:

* What content do we want in the Geospatial Workbook?
* What content formats are the most useful?
* Are there best practices that exist in our research community that we should cover?
* What’s the process for contributing content to the workbook?

Discussion Notes:

Content Ideas

* Share common applications and work flows for downloading/subsetting data
* Recipe/example application of ENVI/IDL in the GS Workbook
* Spectral unmixing analysis
* The same analysis but written in multiple languages could be really helpful
* Provide a good example of a publication supplement in a Jupyter Notebook format
* A couple tutorials that give examples of individual scripts, then a different tutorial showing how they could be run in sequence using Nextflow
* embarassingly parallel example using Python- specifically a workflow that runs a Python script many times with different input data for each job
* How to get a DOI for your container/analysis scripts
* Document how to access wsl2 – Windows Subsystem Linux

C: We could poll our community to find out what are some low hanging fruit as far as repeated analyses, like querying a zone or a set of points in a data cube.

C: I’m in favor of running inside docker containers as it’s much more flexible although a bit more to setup. However, in the end you will then have all the code and more importantly, runtime environment, that the study used which you can get a DOI for. There is a great interface with VS Code which has built in jupyter support.

Q: Who can contribute to the geospatial workbook?

A: Anyone associated with USDA-ARS with relevant content to contribute! An example code or short tutorial can be made out of almost any research analysis. We hope that many of our members (and non-members of the working group) will contribute content.

Q: How do we contribute content to the geospatial workbook?

A: For experienced Github users you can do a pull request to the workbook’s github repo (once it’s created). If you aren’t experienced with Github, you can contact Andrew Severin’s team at gifhelp @ iastate.edu with content.

C: The main focus of the geospatial workbook (at least in the beginning) will be tutorials that deal with heavy computing and run on the ARS HPC systems. We can eventually expand the workbook to include tutorials that run on laptops.

C: There is software called Nextflow Pipeline – wrapper around scripts – that allows you to deploy various codes in parallel on an HPC system and has built in support for containers. This software is used currently in ARS by our bioinformaticians. The geospatial research community should look into whether this software can be helpful to us.

return to agenda

## Proposals for New Working Group Initiatives

<br>
{:.border-bottom}


Discussion Question: What other projects should the working group pursue to enhance access to and use of high-performance computing and to improve ARS researcher computing skills in general?

Discussion Notes:

C: Continuity of online training even after COVID would be good. This helps to include people from various backgrounds who would not necessarily be able to justify traveling to their RLs but are still interested in these topics.

C: I think SCINet has some Amazon Cloud agreements which are not well utilized. Or not readily available. Maybe the group can help get clarity on what cloud computing is available through SCINet

Q: Do we still want to pursue contracting a “GeoTeam”, which was one of the original recommendations made by this group last year? The GeoTeam would help our research community with workflow development, parallelization, and code optimization.

A: We should first identify needs that a GeoTeam could help us with. But we could also first look to the VRSC to help with workflow development, parallelization, and code optimization. The next time we have questions/need help in these areas let’s contact the VRSC for help and see how their staff can assist us. It’s important to note though that the VRSC is not going to conduct your analysis for you!