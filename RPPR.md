# Budget
Don't edit this - the RPPR generater populates this section

# Research Design
Research Strategy
Significance
Much has been written in the contemporary scientific literature and general media concerning the promise of leveraging advanced computational technologies and methods to enable new paradigms for clinical and translational research.  Ultimately, such research can and should generate health benefits at both the patient and population levels, informed by the knowledge generated and disseminated via said efforts.  We believe that these types of emergent clinical and translational research paradigms can and should be predicated on the collection, analysis, and dissemination of relevant, timely, and comprehensive data and knowledge by a variety of end-users in a highly liquid and democratic manner.  Recent reports have show the substantial benefits when employing these types of approaches to clinical and translational research, which can be summarized as the  ability to conduct investigations in a timely and resource efficient manner, often working across and between traditional organizational boundaries (Jones, Rudin et al. 2014, King, Patel et al. 2014).  The pursuit of clinical and translational research at a national level, emblematic of the NCATS-funded CTSA consortium, represent an exciting inflection point in the history of the health and life sciences.  It is our perspective that capitalizing on this opportunity requires the democratization and wide-spread use of computational technologies by a broad spectrum of researchers with variable degrees of technical capability and training. Such democratization of research-relevant computing will require us to: 1) enable effective end-user adoption and utilization of computational platforms and tools in  a broad variety of settings (Bates, Kuperman et al. 2003, Garg, Adhikari et al. 2005, Kawamoto, Houlihan et al. 2005, Goldspiel, Flegel et al. 2014); 2) ensure that technology deployment and user experience are compatible with “real world” workflows and environments (Kawamoto, Houlihan et al. 2005, King, Patel et al. 2014, Kinvey 2014); 3) overcome limitations in vendor-specific technologies that may make it difficult to leverage such systems for the purposes of integrating and interacting with diverse and complex data types across and between traditional organizational boundaries (Mandl and Kohane 2012, Masys, Jarvik et al. 2012, Bender and Sartipi 2013); and 4) ensure that such platforms are elastic, scalable, and sustainable from both a technology and resource perspective.  In response to these challenges and opportunities, the CD2H Tool and Cloud Architecture Core (TCA) will focus upon the following specific aim, as was found in our original application for funding:
(Aim 2) Realize a software tool ecosystem: Guided by FAIR-TLC principles, we will collaboratively develop, advance, and promote an ecosystem for open-source translational software development projects and the creation of aligned communities of practice.  In this context, we define an ecosystem as the combination of people, technologies, and methods needed to predispose and enable successful collaborative projects. This ecosystem will support CTSA teams across the full lifecycle of software development and dissemination, including: 1) access to relevant expertise and knowledge resources to inform project design and execution; 2) collaborative innovation platforms for methodological development and benchmarking; and 3) rapid dissemination and interaction mechanisms for the discovery and use/reuse of software and associated data assets across a full spectrum of maturity levels. 
Our approach to satisfying the aforementioned aim, during the forthcoming performance period, can be broadly divided into four major areas of activity, as follows: 1) creating a common cloud computing architecture that can enable the rapid deployment and sharing of reusable software components by CTSA hubs; 2) demonstrating the use of shared tools and platforms for the collaborative analysis of clinical data in a manner that transcends individual CTSA hub “boundaries”; 3) disseminating a common set of tools that can be employed for the both local and collaborative query of common data warehousing platforms and underlying data models; and 4) piloting the “cloudification” of software artifacts that can be shared across CTSA hubs to address common and recurring information needs.  The specific methods to be used in these contexts are outlined in more detail later in this document.
Innovation
We believe that the aim and approach associated with the TCA are innovative as a result of the following factors:
To-date, CTSA hubs have developed, deployed, and managed computational technologies and tools in support of clinical and translational research in a localized and highly heterogeneous manner.  This approach does not allow for economies-of-scale in terms of technology infrastructure and/or operations, nor does it facilitate the rapid and efficient sharing of software components as a result of substantial local variation and dependencies therein.  By establishing a common cloud computing architecture, along with reproducible technology deployment workflows and tools, CD2H will provide CTSA hubs with an easy to use, elastic, and scalable alternative to local technology deployment paradigms.  We envision that such an alternative approach will serve as the basis for creating a robust and efficient software sharing ecosystem that involves collaborative development, deployment, and use of such technologies across and between CTSA hubs.
In a similar manner, a critical area of activity for many clinical and translational researchers is the collection and analysis of patient-derived data, such as that which can be extracted from Electronic Health Record (EHR) systems.  However, mirroring the challenges described above concerning localized technology deployment, to-date, most CTSA hubs have conducted such analyses at a local level, due to concerns over data sharing, privacy, confidentiality, and the ability to ensure the reproducibility and rigor of the analytical methods being used.  This “silo” based approach to data analysis often precludes the aggregation and interrogation of large-scale data sets, as are frequently needed to assess state-of-the-art research hypotheses, especially with the advent of precision medicine based approaches to the diagnosis and treatment of conditions with relatively low population-level prevalence.  By demonstrating a secure, shared, cloud-based environment in which shared analysis of such patient-derived data can be conducted, and where critical issues of data “ownership”, privacy, confidentiality, and methodological reproducibility/rigor are addressed, CD2H will introduce a new model for shared data analytics that fully leverages the breadth and depth of the national CTSA consortium.
Finally, by showing how common software tools and artifacts that meet shared information needs across and between CTSA hubs, can be readily shared and deployed both locally and in a common cloud environment, CD2H will demonstrate the economies-of-scale that a software sharing ecosystem can achieve for the national CTSA consortium.  Ideally, these economies-of-scale would include: 1) reduced development costs; 2) sustainable technology deployment models and associated resourcing needs; and 3) improved ability to share and integrate data, information, and knowledge products amongst CTSA hubs.
When viewed collectively, we believe that these innovative dimensions of our work will serve as the foundation for the creation of s software ecosystem, consisting of a combination of people, technologies, and methods, which can collectively predispose and enable successful and collaborative clinical and translational research projects.


# Methodology

# Expected Outcomes

# Timeline (monthly)

Task| Name|	Start	|Finish
Concept Phase	14-Apr	13-May
Identify Project Goals	14-Apr	13-May

Planning Phase	14-May	31-May

Define the project scope	14-May	17-May

Define the cloud resources required and draft design	20-May	24-May

Coordinate with NCATS on cloud design and access	20-May	24-May

Coordinate with Mortality-Prediction and LNP CD2H projects	27-May	31-May
Implementation Phase	3-Jun	30-Jun-20
Documenting deployment guidebook/workflow	3-Jun	12-Jul
Create the project image in NCATS Cloud	3-Jun	6-Jun
Cloud access request submitted to NCATS	6-Jun	6-Jun
Build the CD2H GitLab project container from the NCATS image.	7-Jun	10-Jun
Install GitLab in the CD2H GitLab Container	11-Jun	14-Jun
GitLab validation	17-Jun	19-Jun
Cloud access request submitted to NCATS to create the Mortality - Prediction container	19-Jun	20-Jun
Build the Mortality Prediction project container from the NCATS image.	21-Jun	24-Jun
Request access to CD2H GitLab	25-Jun	25-Jun
Create Mortality Prediction repo	25-Jun	25-Jun
Deploy to the Mortality prediction container (app and required system libraries)	26-Jun	12-Jul
Enhance the Guidebook/workflow with experience from the M-P deployment and perform editing.	15-Jul	23-Jul
Cloud access request submitted to NCATS by CD2H NLP team member	24-Jul	25-Jul
Build the NLP App project container from the NCATS image	26-Jul	31-Jul
CD2H NLP team creates NLP repo	30-Jul	30-Jul
Deploy to the NLP container (app and required system libraries)	1-Aug	15-Aug
Enhance the Guidebook/workflow with experience from the NLP deployment and perform editing.	16-Aug	27-Aug
CD2H teams deploy app, algorithms, tools to the CD2H Cloud using the deployment workflow and examples.  The process and workflow documentation continues to be improved.	9/2/2019	6/30/2020



# Potential Pitfalls and Alternative Strategies
