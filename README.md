# Cloud-Tool-Architecture

## Problem statement

Demostrate the collaboration opportunies provided by deploying CD2H applications in the NCATS cloud.   

## Project description
Define and document a cloud deployment workflow that can be used by all CD2H sites to guide deploying applications and tools in the NCATS cloud. 
We will deploy a CD2H branded GitLab instance in the CD2H cloud.  This has a dual benefit, first we will use the creation of the NCATS-CD2H GitLab as a working/learning experience that directly feeds information into creating the deployment workflow mentioned prior.   Second, the cloud based GitLab will provide a location for other CD2H sites to create repositories.    Both AWS and Docker GitLab instances are planned.
In addition we will deploy the Mortality Prediction app code and documentation into the CD2H Gitlab. A Docker container will also be created as a sandbox environment for the Mortality Prediction app. Lessons learned in the Mortality Prediction deployment will be used to enhance the deployment workflow. 
Deployment of an NLP application into the NCATS cloud using the documented deployment workflow is also planned as part of this project. 

 

## Contact person

We require a contact person for each project for administrative purposes. Each project should also have a CD2H Program director assigned.

Point person (github handle) | Site | Program Director
----------|--------------|---------------
Tom Dillon (@tmdillon) | Washington University I2 | Melissa Haendel

## Leads 

Lead(s) (github handle) | Site
----------|--------------|
Justin Guinney, Director and EHR Challenge Project Lead (Sage Bionetworks)
Philip Payne, Co-Director and Cloud Architecture Project Lead (Wash U)

## Distro List
For project email addresses, please see bit.ly/cd2h-people-slim


## Team members 

Washington University I2: 
-	Philip Payne
-	Tom Dillon
-	Ricky Rodriguez
-	Albert Lai
-	TBN Cloud Architect

Sage:
-	Justin Guinney
-	James Eddy

NCATS:
-	Ken Gersing
-	Usman Sheikh
-	Kirsch, Keats (NIH/NCATS)
   


## Repositories
https://github.com/data2health/Cloud-Tool-Archtecture

## Approach

Cloud-Tool-Architecture Project: 

Our approach to the design and delivery of an elastic, scalable, and sustainable common cloud architecture for use by the national CTSA network will be based upon the NIST Enterprise Architecture Model (GAO, 2010: “A Framework for Assessing and Improving Enterprise Architecture Management”).  The NIST Enterprise Architecture Model (EA) incorporated 5 interdependent layers of architectural planning and implementation, as is shown in Figure 1 below, spanning a spectrum from technical foundations to end-user defined use cases.


 
Figure 1:  Overview of NIST EA model, showing five interdependent layers of architectural planning and implementation.
Given this model, we will pursue an iterative process of architecture design, implementation, verification/validation, and deployment, working in close coordination with all CD2H cores and projects, as well as a cross-section of CTSA informatics community members from throughout the national network.  In doing so, we will take a use case driven approach, in which the ensuing architecture will be optimized to ensure the successful satisfaction of end-user information needs.  Further, these activities will be interwoven with the architectural and planning activities being undertaken by the Resource Discovery and Development (RDD) Core, Next Generation Data Sharding (NGDS) Core, and the information technology team at NCATS (NCTAS-IT).  A RACI model demonstrating these interdependencies as shown in Table 1 below.  It is important to note that we anticipate some changes to this RACI model as we accrue project experience, various projects mature or are completed, and our collective teams establish standard operating procedures, and as such, it should be considered an “organic” framework that will evolve over time.

| First Header  | Second Header |
| ------------- | ------------- |
| Content Cell  | Content Cell  |
| Content Cell  | Content Cell  |

Table 1:  Coordination of architectural design processes spanning CD2H and NCATS units (Key: R = Responsible, A = Accountable, C = Consulted, I = Informed)
Design Layer	TCA 	RDR	NGDS	NCATS-IT
Use Cases	 | R | A	| R	||C |	I
Information Needs |	R|	R | A	| C |	I
Information Systems	R,A	C	C	I
Data	C	C	R,A	I
Delivery Systems	C	C	C	R,A


  
## Deliverables

-	Creation of a GitLab instance deployed in the NCATS cloud. (Dependant on GitLab being selected as the Git repo) 
-	A successful deployment of the Mortality-Prediction application in the NCATS cloud. 
-	A successful deployment of an NLP application in the NCATS cloud. 
-	Creation of an authentication process that can be used by all CD2H sites. 
-	Creation of a guidebook/workflow documentation that other CD2H teams can follow to deploy their apps/algorithms/tools to the CD2H cloud.


## Milestones

The milestones for this project is here:

https://github.com/data2health/Cloud-Tool-Archtecture/milestones



## Evaluation

We will evaluate the outcome of this project in the following ways:

- A Git repository solution was identified and will be available for use by CD2H teams deploying to the NCATS cloud.
- The Motality-Predition application was sucesfully deployed as a docker/container to the NCATS cloud.
- An NLP application was sucesfully deployed as a docker/container to the NCATS cloud.
- A guidebook/workflow was documented that other CD2H teams can use to deploy applications to the NCATS cloud.



## Education
Each project should propose a set of educational activities, listed separately in the Education Plan file. 
Please reference any of the following that apply: 
- Educational resources that will be generated (these can be milestones and/or files in the repo)
- Educational opportunities (please indicate for which type of learner and how to participate)
- Best practices guides

Please include education related issues where relevant, tagged with "education". 

## Get involved
We encourage the community to get involved. 

We require all CD2H projects to have non-CD2H CTSA participants, as CD2H is a CTSA coordinating center. Each project should include an Engagement plan file, example [here](https://github.com/data2health/project-repo-template/blob/master/engagement.md). 

Please tag any engagment related issues with "engagement".

## Working documents
Documentation may be natively in GitHub using the wiki or .md files in the appropriate folder, or in Google Drive.
[Documentating projects in Github](https://guides.github.com/features/wikis/)

[The project Google drive folder](https://drive.google.com/drive/u/0/folders/1vLp-H32KTNobiZF2cK82At90S6dVJNUf) is accessible to onboarded participants. 

## Slack room
[The project slack room](https://cd2h.slack.com/messages/CEY05KLPM/) is accessible to onboarded participants. You will not automatically be added to Slack, please join via the link above.

## Need help with GitHub? See the Managing Tranlational Informatics Projects (MTIP) tutorial

This [tutorial](https://data2health.github.io/mtip-tutorial/lessons/Lesson5.html) covers markdown basics and more.
