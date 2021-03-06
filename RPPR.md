# Budget
Don't edit this - the RPPR generater populates this section

# Research Design

Much has been written in the contemporary scientific literature and general media concerning the promise of leveraging advanced computational technologies and methods to enable new paradigms for clinical and translational research.  Ultimately, such research can and should generate health benefits at both the patient and population levels, informed by the knowledge generated and disseminated via said efforts.  We believe that these types of emergent clinical and translational research paradigms can and should be predicated on the collection, analysis, and dissemination of relevant, timely, and comprehensive data and knowledge by a variety of end-users in a highly liquid and democratic manner.  Recent reports have show the substantial benefits when employing these types of approaches to clinical and translational research, which can be summarized as the  ability to conduct investigations in a timely and resource efficient manner, often working across and between traditional organizational boundaries (Jones, Rudin et al. 2014, King, Patel et al. 2014).  The pursuit of clinical and translational research at a national level, emblematic of the NCATS-funded CTSA consortium, represent an exciting inflection point in the history of the health and life sciences.  It is our perspective that capitalizing on this opportunity requires the democratization and wide-spread use of computational technologies by a broad spectrum of researchers with variable degrees of technical capability and training. Such democratization of research-relevant computing will require us to: 1) enable effective end-user adoption and utilization of computational platforms and tools in  a broad variety of settings (Bates, Kuperman et al. 2003, Garg, Adhikari et al. 2005, Kawamoto, Houlihan et al. 2005, Goldspiel, Flegel et al. 2014); 2) ensure that technology deployment and user experience are compatible with “real world” workflows and environments (Kawamoto, Houlihan et al. 2005, King, Patel et al. 2014, Kinvey 2014); 3) overcome limitations in vendor-specific technologies that may make it difficult to leverage such systems for the purposes of integrating and interacting with diverse and complex data types across and between traditional organizational boundaries (Mandl and Kohane 2012, Masys, Jarvik et al. 2012, Bender and Sartipi 2013); and 4) ensure that such platforms are elastic, scalable, and sustainable from both a technology and resource perspective.  In response to these challenges and opportunities, the CD2H Tool and Cloud Architecture Core (TCA) will focus upon the following specific aim, as was found in our original application for funding:
(Aim 2) Realize a software tool ecosystem: Guided by FAIR-TLC principles, we will collaboratively develop, advance, and promote an ecosystem for open-source translational software development projects and the creation of aligned communities of practice.  In this context, we define an ecosystem as the combination of people, technologies, and methods needed to predispose and enable successful collaborative projects. This ecosystem will support CTSA teams across the full lifecycle of software development and dissemination, including: 1) access to relevant expertise and knowledge resources to inform project design and execution; 2) collaborative innovation platforms for methodological development and benchmarking; and 3) rapid dissemination and interaction mechanisms for the discovery and use/reuse of software and associated data assets across a full spectrum of maturity levels. 



# Methodology

Our approach to satisfying the aforementioned aim, during the forthcoming performance period, can be broadly divided into four major areas of activity, as follows: 1) creating a common cloud computing architecture that can enable the rapid deployment and sharing of reusable software components by CTSA hubs; 2) demonstrating the use of shared tools and platforms for the collaborative analysis of clinical data in a manner that transcends individual CTSA hub “boundaries”; 3) disseminating a common set of tools that can be employed for the both local and collaborative query of common data warehousing platforms and underlying data models; and 4) piloting the “cloudification” of software artifacts that can be shared across CTSA hubs to address common and recurring information needs.  The specific methods to be used in these contexts are outlined in more detail later in this document.


# Expected Outcomes

We believe that the aim and approach associated with the TCA are innovative as a result of the following factors:
To-date, CTSA hubs have developed, deployed, and managed computational technologies and tools in support of clinical and translational research in a localized and highly heterogeneous manner.  This approach does not allow for economies-of-scale in terms of technology infrastructure and/or operations, nor does it facilitate the rapid and efficient sharing of software components as a result of substantial local variation and dependencies therein.  By establishing a common cloud computing architecture, along with reproducible technology deployment workflows and tools, CD2H will provide CTSA hubs with an easy to use, elastic, and scalable alternative to local technology deployment paradigms.  We envision that such an alternative approach will serve as the basis for creating a robust and efficient software sharing ecosystem that involves collaborative development, deployment, and use of such technologies across and between CTSA hubs.
In a similar manner, a critical area of activity for many clinical and translational researchers is the collection and analysis of patient-derived data, such as that which can be extracted from Electronic Health Record (EHR) systems.  However, mirroring the challenges described above concerning localized technology deployment, to-date, most CTSA hubs have conducted such analyses at a local level, due to concerns over data sharing, privacy, confidentiality, and the ability to ensure the reproducibility and rigor of the analytical methods being used.  This “silo” based approach to data analysis often precludes the aggregation and interrogation of large-scale data sets, as are frequently needed to assess state-of-the-art research hypotheses, especially with the advent of precision medicine based approaches to the diagnosis and treatment of conditions with relatively low population-level prevalence.  By demonstrating a secure, shared, cloud-based environment in which shared analysis of such patient-derived data can be conducted, and where critical issues of data “ownership”, privacy, confidentiality, and methodological reproducibility/rigor are addressed, CD2H will introduce a new model for shared data analytics that fully leverages the breadth and depth of the national CTSA consortium.
Finally, by showing how common software tools and artifacts that meet shared information needs across and between CTSA hubs, can be readily shared and deployed both locally and in a common cloud environment, CD2H will demonstrate the economies-of-scale that a software sharing ecosystem can achieve for the national CTSA consortium.  Ideally, these economies-of-scale would include: 1) reduced development costs; 2) sustainable technology deployment models and associated resourcing needs; and 3) improved ability to share and integrate data, information, and knowledge products amongst CTSA hubs.
When viewed collectively, we believe that these innovative dimensions of our work will serve as the foundation for the creation of s software ecosystem, consisting of a combination of people, technologies, and methods, which can collectively predispose and enable successful and collaborative clinical and translational research projects.

# Deliverables

Building on the preceding research design, during the forthcoming performance period (spanning 6 months), we intend to execute upon the following tasks:

1.	We will deploy a CD2H instance of the GitLab platform, leveraging NCATS cloud resources.  This platform will provide a common environment for the development, documentation, and sharing of software artifacts, as well as core capabilities for continuous integration and deployment (CI/CD) as will be needed for future tasks related to establishing shared software quality “benchmarks”;

2.	We will integrate the aforementioned CD2H GitLab platform with one or more common authentication and authorization services supported by NIH/NCATS, in order to simplify community-member access and use of said environment;

3.	We will develop a set of technology deployment processes and documentation standards, working across the CD2H and NCATS teams, as are needed to support tasks 1 and 2, while informing future and analogous technology deployment activities; and

4.	In parallel, and working in coordination with the teams responsible for Projects 3 and 4, we will demonstrate the use of containerization technologies to enable the rapid “packaging” and deployment of such applications in the NCATS cloud environment, using either a SaaS and/or Virtual Server model.

In order to ensure the sustainability of our methodology and its associated technical deliverables (including software components, best practices, etc.), we will couple all project related efforts with a continuous program of documentation and version management.  Such activities will ensure that other cores, sites, or organizations could assume responsibility for the ongoing adoption or use of all research products described in this proposal.  Specific measures to be taken in this regard include:

•	Organization of all software development into discrete versions or releases that will be formalized, “checked-in” to the project’s GitHub/Lab site, and fully documented using community-accepted best practices;

•	Documentation of all project-related design processes, decisions, use cases, and evaluation metrics;

•	Use of software engineering best practices, in-line documentation, and quality assurance mechanisms; and

•	Consistent use of open-source and standards-based software technologies and architectures.


# Timeline (monthly)


| Milestone  | Due Date | 
| ------------- | ------------- | 
| A) Identify the goals of creating a cloud environment that facilities collaboration and software/data sharing across all CTSA hubs. |  Due by Apr, 2019 |  
| B) A joint effort with NCATS and CD2H resources will collect the technical, process and security requirements to design the cloud environment |  Due by Jul, 2019 |
| C) Design and implement a federated authorization and authentication process that will provide a common, reusable access process that will be available to all participating CTSA teams. |  Due by Sep, 2019 |  
| D) Deploy Competitions and Dream Challenge in the NCATS cloud as proof of concept.  | Due by Sept, 2019 |  
| E) NCATS technical staff and the application teams for Competitions and Dream Challenge will work as a team to identify the architecture resources required for these applications to be deployed in the cloud. |  Due by Jul, 2019 |  
| F) Leverage the experience gained from deploying Competitions and Dream Challenge to create and publish a simple, repeatable process and workflow for future CD2H deployments.  Responsibilities for each step will be identified.   | Due by Dec, 2019 | 
| G) The NCATS cloud environment and a well-documented deployment process/workflow is available for other CTSA teams to deploy application, tool, and algorithms.  |  Due by Jan, 2020  |
| H) The app store concept and governance and best practices have been identified as processes that must be defined, approved, and documented. |  Due by Nov, 2019  |
| I) Deploy the NLP solution in the NCATS cloud. |  Due by Jan, 2020  |


# Approach
Cloud-Tool-Architecture Project:

Our approach to the design and delivery of an elastic, scalable, and sustainable common cloud architecture for use by the national CTSA network will be based upon the NIST Enterprise Architecture Model (GAO, 2010: “A Framework for Assessing and Improving Enterprise Architecture Management”). The NIST Enterprise Architecture Model (EA) incorporated 5 interdependent layers of architectural planning and implementation, as is shown in Figure 1 below, spanning a spectrum from technical foundations to end-user defined use cases.

 ![](NIST.png)

Figure 1: Overview of NIST EA model, showing five interdependent layers of architectural planning and implementation. Given this model, we will pursue an iterative process of architecture design, implementation, verification/validation, and deployment, working in close coordination with all CD2H cores and projects, as well as a cross-section of CTSA informatics community members from throughout the national network. In doing so, we will take a use case driven approach, in which the ensuing architecture will be optimized to ensure the successful satisfaction of end-user information needs. Further, these activities will be interwoven with the architectural and planning activities being undertaken by the Resource Discovery and Development (RDD) Core, Next Generation Data Sharding (NGDS) Core, and the information technology team at NCATS (NCTAS-IT). A RACI model demonstrating these interdependencies as shown in Table 1 below. It is important to note that we anticipate some changes to this RACI model as we accrue project experience, various projects mature or are completed, and our collective teams establish standard operating procedures, and as such, it should be considered an “organic” framework that will evolve over time.

Table 1: Coordination of architectural design processes spanning CD2H and NCATS units (Key: R = Responsible, A = Accountable, C = Consulted, I = Informed)

| Design Layer  | TCA | RDR | NGDS | NCATS-IT | 
| ------------- | ------------- | ------------- | ------------- | ------------- |
| Use Cases  | R,A | R | C | I | 
| Information Needs  | R  |  R,A | C | I | 
| Information Systems  | R,A  |  C | C | I | 
| Data  | C  |  C | R,A | I | 
| Delivery Systems | C  |  C | C | R,A |  


# Timeline
| Milestone  | Due Date | 
| ------------- | ------------- | 
| A) Identify Project Goals |  Due by May 31, 2019 |  
| B) Define the project scope |  Due by May 31, 2019 |
| C) Coordinate with NCATS on cloud design and access |  Due by May 24, 2019 |  
| D) Coordinate with Mortality-Prediction and LNP CD2H projects  | Due by May 31, 2019 |  
| E) NCATS create project image in the cloud |  Due by June 06, 2019 |  
| F) Create the GitLab container and deploy a GitLab instance  | Due by June 10, 2019 | 
| G) Create Mortality-Prediction GitLab repo |  Due by June 25, 2019  |
| H) Create Mortality-Prediction container |  Due by June 24, 2019  |
| I) Deply Mortality-Prediction App to the cloud |  Due by June 28, 2019  |
| J) Create NLP container |  Due by July 31, 2019  |
|	K) Create NLP GitLab repo  |  Due by July 30, 2019 |  
|	L) Deploy the NLP app to the cloud |  Due by August 15, 2019 | 
|	M) Create Guidebook/workflow to instruct CD2H team on deploying to the cloud |  Due by August 27, 2019 | 



# Evaluation
We will evaluate the outcome of this project in the following ways:

A Git repository solution was identified and will be available for use by CD2H teams deploying to the NCATS cloud.
The Motality-Predition application was sucesfully deployed as a docker/container to the NCATS cloud.
An NLP application was sucesfully deployed as a docker/container to the NCATS cloud.
A guidebook/workflow was documented that other CD2H teams can use to deploy applications to the NCATS cloud.
Education
Project 1- Cloud Architecture: Development and Publication of Technical Best Practices and Standards

In a manner analogous to the aforementioned outreach, engagement, and educational activities, the cloud architecture team at WashU will also engage in a process of iterative development and publication of technical best practices and standards related to the quality, documentation, and development lifecycle management of software products intended for deployment in the NCATS cloud environment. These documents and standards will be generated concomitant with the technical deliverables and tasks associated with this Project as well as Projects 3 and 4, so as to be anchored in those practical deployment activities. Specific frameworks to be used to inform the generation of these documents and standards will include (but are not limited to):

•	ISO/IEC/IEEE 15289 (2017): Systems and software engineering – content of life-cycle information products (documentation). This standard specifies a minimum information content for software documentation from several perspectives: o	Purpose and common content for typical information items (generic types) o	Specific content needed for various life-cycle processes o	Types of data collected and used •	ISO/IEC 26513 (2009): Systems and software engineering - requirements for testers. This standard focuses on the development of systematized plans for software testing throughout the development lifecycle. The standard specifies the documentation need for verification and validation at the unit level, as well as processes for managing the output of reviews, and resolving problems discovered during reviews and tests.

These documents will be made available in a curated manner via the Guidebook, but also in a dynamic manner via the CD2H Git Repository. Further, they will be subject to comment, feedback, and stakeholder approval via the “Tools of the Trade” sessions described in the outreach, engagement, and educational plan.



# Engagement
Project 1- Cloud Architecture: Outreach, Engagement, and Education Plan

For the purposes of the interaction between Project 1 (cloud architecture) and Projects 3 and 4 (pilot deployment of “cloudified” applications), we will implement a multi-part outreach, engagement, and education plan, consisting of the following activities:

•	The cloud architecture team at WashU will conduct regularly scheduled and virtual “technical stand up meetings” with the teams developing and providing access to the applications to be “cloudified”; •	The project manager at WashU will generate a shared project charter for each “cloudification” effort, outlining: 1) project objectives; 2) technical deliverables; 3) timelines; 3) communications plans (beyond the preceding “technical stand up meeting”); and 4) risk management plans. These charters will be considered “living” documents (hosted in the CD2H Git Repository) and updated on a regular basis to reflect project milestones, achievements, and other relevant developments. •	During the course of the “cloudification” projects, we will also generate and regularly update a set of technical best practice documents and associated workflow and RACI models, focusing on the technology deployment process for both Virtual Server and SaaS solutions that are being containerized and deployed in the NCATS cloud environment. These documents will be made available in a curated manner via the Guidebook, but also in a dynamic manner via the CD2H Git Repository. •	On a regularly occurring basis (at least bi-monthly, and more frequently based upon demand), the cloud architecture team at WashU will host a cloud deployment “tools of the trade” webinar, which will be open to all CTSA hubs, and which will highlight recent activities of the team as well as the aforementioned technical best practice documents and findings. Similarly, a slack channel for CTSA hub affiliates interested or engaged in cloud architecture and deployment will be established to enable asynchronous communication in-between such webinars. •	Finally, the cloud architecture team at WashU will engage in regular environmental scanning of the IDTF and broader CTSA community to identify future opportunities for “cloudification” projects. Simultaneously, the team will also engage in broader scanning to identify and report back to interested individuals (via the above mechanisms) on emergent cloud computing and architectural models and frameworks that may impact the work of the CD2H and broader CTSA communities.



Working documents


# Potential Pitfalls and Alternative Strategies



# Y3 (July 1, 2019-June 30, 2020) Accomplishments 
The following content is from the June 30 - Dec 30, 2019 mid year progress report [here](https://docs.google.com/document/d/1LLe3uCfEUakWxIJyi5SA4ZocYDmINvhySTperaui1Bw/edit).  Please add progress for Jan 1 - June 30th, 2020. 

* We will deploy a CD2H instance of the GitLab platform, leveraging NCATS cloud resources. This platform will provide a common environment for the development, documentation, and sharing of software artifacts, as well as core capabilities for continuous integration and deployment (CI/CD) as will be needed for future tasks related to establishing shared software quality “benchmarks”;
  * In coordination with NCATs, we decided against a GitLab deployment in favor of using Github and Jenkins as the preferred source code repository and CI/CD system. Both Github and Jenkins are available in the NCATs cloud, and have been  leveraged as described in our [Cloud & Tool Architecture Proposal](https://docs.google.com/presentation/d/1O8C0Kj5AtX-69C0eY79zaftAQFPYAWAELAZ2Y7-vnnA/edit#slide=id.g5e2ce0d5ce_5_0) and on our [Core Website](https://data2health.github.io/tools-cloud-infrastructure/).

* We will integrate the aforementioned CD2H GitLab platform with one or more common authentication and authorization services supported by NIH/NCATS, in order to simplify community-member access and use of said environment;
  * See prior note on GitLab.

* We will develop a set of technology deployment processes and documentation standards, working across the CD2H and NCATS teams, as are needed to support tasks 1 and 2, while informing future and analogous technology deployment activities;
  * We have developed an intake process for teams who want to utilize the CD2H/NCATS cloud. The process begins with the team submitting a CD2H-NCATS Cloud Intake Request Form which captures information describing their tool/app and the technical resources required to support it.  Once the form is submitted and the request is approved by the governance team, the NCATS technical support team is engaged to provision the required cloud resources. This presentation describes the process. 

* In parallel, and working in coordination with the teams responsible for Projects 3 and 4, we will demonstrate the use of containerization technologies to enable the rapid “packaging” and deployment of such applications in the NCATS cloud environment, using either a SaaS and/or Virtual Server model.
  * We have successfully deployed two sandboxes: the Competitions platform and the EHR Algorithm Exercizer used in the EHR DREAM Challenge. For the latter, Dockerized algorithms are tested in the sandbox against SynPUF data to ensure operational validation of EHR algorithms.

* In order to ensure the sustainability of our methodology and its associated technical deliverables (including software components, best practices, etc.), we will couple all project related efforts with a continuous program of documentation and version management. | Such activities will ensure that other cores, sites, or organizations could assume responsibility for the ongoing adoption or use of all research products described in this proposal. Specific measures to be taken in this regard include: Organization of all software development into discrete versions or releases that will be formalized, “checked-in” to the project’s GitHub/Lab site, and fully documented using community-accepted best practices; documentation of all project-related design processes, decisions, use cases, and evaluation metrics; use of software engineering best practices, in-line documentation, and quality assurance mechanisms; and consistent use of open-source and standards-based software technologies and architectures.
  
   * Adoption of Github and Jenkins have helped to codify the format and structure for code management, and build systems. All pilot projects - Leaf, Competitions, and EHR Challenges - are hosted in Github, and developed, versioned, and deployed according to software best practices. Where possible, open source tools and libraries are used.
