---

title: "Session 0: Pre-meeting technical support for account logins and data uploads"
author: Moe Richert
excerpt: Please complete this pre-meeting checklist ahead of time if you plan to participate in any of the interactive follow-along tutorials (Sessions 4-10). Pre-meeting SCINet Account Login Assistance.
categories: [Geospatial Workshop]  
provider: Geospatial Working Group
type: workshop
tags: Geospatial
layout: nav

sessions:
  - session: 
    time: 10:00am-11:00am MDT
 #   instructor: placeholder
 #   register: No registration required
 #   register_url: https://kerriegeil.github.io/SCINET-GEOSPATIAL-RESEARCH-WG/


alerts: 
  - alert: 
    type: warning
    text: Please register by 8/22/2022 to ensure you will receive event updates.
  - alert: 
    type: error
    text: If you have issues accessing Ceres (either thru SSH or Open OnDemand) please attend Session 0 - Pre-meeting Technical Support on 8/25/2022 at 10am MDT. We cannot provide individual assistance for login issues in any other session.

subnav:
  - text: Tutorials
    href: '#tutorials'
  - text: Access to the SCINet Ceres HPC System
    href: '#access-to-the-scinet-ceres-hpc-system'
  - text: Software + Hardware + Nomenclature Overview
    href: '#software-+-hardware-+-nomenclature-overview'


---

<br>

Please complete this pre-meeting checklist ahead of time if you plan to participate in any of the interactive follow-along tutorials (Sessions 4-10).



<div class="usa-card max-tablet">
    <div class="usa-card__container">
      <div class="usa-card__header bg-primary-lighter">
        <h2 class="usa-card__heading">PreMeeting Checklist</h2>
      </div>
      <div class="usa-card__body">
            <ol>
          <li>Have a SCINet account and be able to login. Apply for an account if you don't have one by 8/15/2022.</li>
          <li>If you need help accessing your SCINet account, attend Session 0: Pre-meeting Technical Support on 8/25/2020 at 10am MDT.</li>
          <li>Register for the sessions you wish to attend by 8/22/2022.</li>
          <li>Familiarize yourself with the brief background information below.</li>
          <li>Optional but suggested: If using your laptop for these tutorials you may want to connect to a larger monitor so that you will have enough monitor space to see the zoom demonstration while also having your browser or terminal workspace open at the same time.</li>
        </ol>
      </div>
    </div>
  </div>


<br>
{:.border-bottom}

# Background Information

<br>
{:.border-bottom}

## Tutorials

The tutorials span the range from beginner to more advanced. If you have questions about the material, please do not hesitate to contact the organizing committee.

In general, these tutorials assume some level of knowledge in scientific programming, but beginners are still welcome.

<br>
{:.border-bottom}


## Access to the SCINet Ceres or Atlas HPC Systems

You must apply for a SCINet account to get access to the Ceres or Atlas HPC systems. Usually, the account approval process takes 1-2 weeks. After your account is approved, there are a couple more steps to complete before you will be able to successfully login to your account. You will receive instructions by email on how to access your account for the first time upon account approval. Please make sure you can login to your account before joining our tutorial sessions.

Visit the [Ceres](https://scinet.usda.gov/guide/ceres/) and [Atlas](https://www.hpc.msstate.edu/computing/atlas/) user guides for more information about how to login and brief information about the HPC systems.

How to test Open OnDemand login: ...

**If you have issues accessing Ceres or Atlas (either thru SSH or Open OnDemand) please attend Session 0: Pre-meeting SCINet Account Login Assistance on 8/25/2022 at 10am MDT. We cannot provide individual assistance for login issues in any other session.**

<br>
{:.border-bottom}

## Software + Hardware + Nomenclature Overview

The software discussed and shown in the workshop is largely open source, can run on a desktop, HPC, or cloud environment, and can be installed with software management systems that support reproducibility (such as Conda, Singularity, and Docker). Below is a quick overview of some of the software, hardware, and confusing nomenclature that will be used during this workshop.

**SCINet vs. Ceres vs. Atlas**

SCINet is the USDA ARS Scientific Computing INitiative that aims to improve access to high performance and cloud computing, improve networking to facilitate high speed data transfer, and facilitate scientific computational training. The [Virtual Research Support Core (VRSC)](https://scinet.usda.gov/support/vrsc/) 

Ceres is one of the HPC systems (located in Iowa) connected to the SCINet infrastucture. The system is largely maintained by staff at Iowa State University called the SCINet . 

Atlas is the more recently added HPC system 

For more information on the HPC systems that SCINet offers, see the [Computer Systems page of the SCINet website.](https://scinet.usda.gov/about/compute)

**Open OnDemand**

Jupyter is an open-source, non-profit project to support interactive data science and scientific computing. Jupyter is language agnostic with support for >130 different scientific programing language kernels. This workshop will use the following two applications from the Jupyter software stack:

1. Open OnDemand: A software to serve JupyterLab to multiple users (this is how we will launch an instance of JupyterLab on Ceres without having to to SSH into the cluster). Documention at: [https://jupyterhub.readthedocs.io/en/stable/](https://jupyterhub.readthedocs.io/en/stable/)
1. JupyterLab: A web-based interactive development environment. Documentation at: [https://jupyterlab.readthedocs.io/en/stable/](https://jupyterlab.readthedocs.io/en/stable/)

**SLURM**

SLURM (Simple Linux Utility for Resource Management) is the workload manager used on the Ceres and Atlas HPC system to allocate computational resources. From the [SLURM documentation](https://slurm.schedmd.com/quickstart.html), SLURM is “an open source… cluster management and job scheduling system for large and small Linux clusters. As a cluster workload manager, SLURM has three key functions. First, it allocates exclusive and/or non-exclusive access to resources (compute nodes) to users for some duration of time so they can perform work. Second, it provides a framework for starting, executing, and monitoring work (normally a parallel job) on the set of allocated nodes. Finally, it arbitrates contention for resources by managing a queue of pending work.”

**Scientific Coding Languages - Python and R**

The tutorials in this workshop will use Python, but we will make an effort to discuss alternative approaches in R. Python and R appear to be the most common scientific programming languages used across ARS. We choose to focus on Python simply due to instructor expertise/background. However, many of these examples could also be run in other programming languages such as R, Julia, Go, IDL/ENVI, etc…

**Containers and Environments**

Environments are a method of isolating a set of software installed on a computing system. In this workshop, we will largely be discussing environments in the context of the [Anaconda (Conda)](https://www.anaconda.com/products/individual) package/environment management system. However, other software management systems impliment similiar approaches.

Containers are a unit of isolated software that include an entire runtime environment (applications, dependencies, libraries, and binaries). These systems were created to be able to reliably run computing environments across hetereogenous infrastructure (operating systems). The container system used on Ceres (and most other HPC systems) is [Singularity](https://sylabs.io/docs/). However, Singularity is able to run a container from a Docker image, a much more prevalent containerization software.

The use of both containers and environments can vastly improve the reproduciblity of computatoinal research. Environments are able to acheive this by keeping a detailed list of the exact software environment used for the computation. Containers are able to further this effort by essentially archiving/saving the exact environment in a “container file”, which others can access and use on other systems.

**Git & GitHub**

Git & GitHub allow you to version and archive your scientific codes (and more).

Git is version control software that you use at the command line to keep track of edits to your scientific codes over time.

GitHub is an online repository hosting service where you can archive your scientific codes online. You can [create a free personal Github account](https://github.com/join) where you can archive your scientific codes into different "repositories" within your account. If you keep your Github repos up to date, it also allows you to access your codes from anywhere.

Much of the workshop materials will be accessible through the workshop's GitHub repository at (repo address coming soon).

You don't have to have your own Github account to participate in the workshop tutorials, but it is a good idea to create one for yourself (they are free) ahead of the workshop sessions if you want to begin to learn how to use Git/Github. Note: creation of a personal Github account is required if you want to follow along with the Github portion of the Session 4 Tutorial: Computational Reproducibility Tools.