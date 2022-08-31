---

title: "Session 6: Geospatial analyses and how to parallelize them in R"
author: Moe Richert
excerpt: R packages for geospatial analyses and parallel processing with multiple tutorials 
categories: [Geospatial Workshop]  
provider: Geospatial Working Group
type: workshop
tags: Geospatial R-project
layout: nav

sessions:
  - session: 
    time: 11:00am-1:30pm MDT
 #   instructor: placeholder
 #   register: No registration required
 #   register_url: https://kerriegeil.github.io/SCINET-GEOSPATIAL-RESEARCH-WG/
    prerequisites:
      - text: Have a SCINet account and be able to login 
        href: https://scinet.usda.gov/about/signup
        external: true
      - text: Basic R or other basic programming skill helpful (expertise not required)
      - text: RStudio on Ceres via Open OnDemand will be used, so attending Session 4 may be helpful


alerts: 
  - alert: 
    type: info
    slim: true
    text: This session overlaps with Session 8 which covers the same content but in python instead of R.


subnav:
  - text: Learning objectives
    href: '#learning-objectives'
  - text: Agenda
    href: '#agenda'
  - text: Tutorial material
    href: '#tutorial-material'

summarybox:
  header: Session Rules
  list:
    - point: <b>Green Light, Red Light</b> - Use the Zoom participant feedback indicators to show us if you are following along successfully as well as when you need help. To access participant feed back, click on the “Participants” icon to open the participants pane/window. Click the green “yes” to indicate that you are following along successfully, click the red “no” to indicate when you need help. Ideally, you will have either the red or green indicator displayed for yourself throughout the entire tutorial. We will pause every so often to work through solutions for participants displaying a red light.
    - point: <b>Chat questions/comments take first priority</b> - Chat your question/comments either to everyone (preferred) or to the chat moderator (Ryan Lucas) privately to have your question/comment read out loud anonymously. We will answer chat questions first and call on people who have written in the chat before we take questions from raised hands.
    - point: <b>Share your video when speaking</b> - If your internet plan/connectivity allows, please share your video when speaking.
    - point: <b>Keep yourself on mute</b> - Please mute yourself when not speaking.

---

<br>

## Learning objectives
<br>
{:.border-bottom}

This session will include tutorials exploring examples of handling geospatial data, performing geospatial calculations, and applying parallel processing approaches to geospatial processing workflows in R. RStudio via Open OnDemand (see [Session 4](events/2022-8-30-Geospatial-Workshop-4/)) will be used for a portion of the tutorials. 

* Read in and manipulate raster data with the *terra* and *stars* packages
* Read in and manipulate vector data with the *sf* package
* Time chunks of code in your R script
* Identify package functions with parallelization options built-in
* Parallelize R code of many independent geospatial tasks 

## Agenda
<br>
{:.border-bottom}

This session will be an interactive tutorial:

* Geospatial packages
* Parallel processing packages
* Vector tutorial 
* Raster tutorial 
* Vector-raster tutorial


A recording of this session and discussion summary notes will be made available here after the workshop is complete. Each tutorial will be converted to [Geospatial Workbook](https://geospatial.101workbook.org) entries. 

<br>
## Tutorial material
<br>
{:.border-bottom}

Steps to prepare for the tutorial:

1. **Login to Ceres Open OnDemand** at [https://ceres-ood.scinet.usda.gov](https://ceres-ood.scinet.usda.gov). Your username is typically *firstname.lastname*. For the password, enter your SCINet account password followed by the 6-digit verification code, e.g. from a Google Authenticator app on your phone, with no spaces. Do not add a '+' between your password and code. 

2. **Copy the Session 6 material from the workshop project space to your temporary workshop folder.** To get to a shell to do so, you can use the *Clusters* tab at the top of your Open OnDemand page to select 'Ceres Shell Access' (if prompted for a password, enter your SCINet account password without the verification code). If you are comfortable ssh-ing in instead from terminal or powershell, feel free to do so.

    If you have already made your workshop folder in previous sessions, you will only need to run the following commands, replacing *firstname.lastname* with your actual name: 

    ```bash
    cd /90daydata/shared/firstname.lastname
    cp -r /project/geospatialworkshop/session6/
    ```

    If you have not created your workshop folder yet, run these commands instead, replacing *firstname.lastname* with your actual name:

    ```bash
    cd /90daydata/shared
    mkdir firstname.lastname
    cd firstname.lastname
    cp -r /project/geospatialworkshop/session6/ 
    ```

3. **Launch a RStudio session.** Choose the following values from the menu:

    * Account: geospatialworkshop
    * Slurm Partition: workshop
    * R version: 4.2
    * Number of hours: 3
    * Number of cores: 16
    * Memory required: 64G
  
    Click *Launch*.

4. **The tutorials:** The first two tutorials will follow Rmarkdown documents in RStudio. For the third tutorial, we will submit a job to SLURM directly. If your shell from Step 2 has expired when we start the third tutorial, please reconnect, and change directory to your session 6 folder:

    ```bash
    cd /90daydata/shared/firstname.lastname/session6
    ```

<br>