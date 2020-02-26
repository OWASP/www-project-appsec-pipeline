---

layout: col-sidebar
title: OWASP Appsec Pipeline
tags: example-tag
level: 0
type: documentation

auto-migrated: 1
---
# Main

![OWASP_Project_Header.jpg](OWASP_Project_Header.jpg "OWASP_Project_Header.jpg")


The OWASP AppSec Rugged DevOps Pipeline Project is the place to find the information you need to increase the
speed and automation of your AppSec program. Using the sample implementation, documentation and references of
this project will allow you to setup your own AppSec Pipeline.

## Description

The AppSec pipeline project is a place to gather together information, techniques and tools to create your own
AppSec Pipeline. AppSec Pipelines takes the principles of DevOps and Lean and applies that to an application
security program. The project will gather references, code, and specific guidance for tools/software which
would compose an AppSec Pipeline.

## Licensing

The OWASP AppSec Pipeline Project documentation is licensed under the [Creative Commons Attribution-ShareAlike 3.0 license](http://creativecommons.org/licenses/by-sa/3.0/")
so you can copy, distribute and transmit the work, and you can adapt it, and use it commercially, but all
provided that you attribute the work and if you alter, transform, or build upon this work, you may distribute
the resulting work only under the same or similar license to this one.

## What is the OWASP AppSec Pipeline Project?

The AppSec Pipeline project is a place to gather together information, techniques and tools to create your own AppSec Pipeline.

## Project Leaders

* [Matt Tesauro](mailto:matt.tesauro@owasp.org)
* [Aaron Weaver](mailto:aaron.weaver2@gmail.com)

## Contributors

## Related Projects

* [OWASP_Web_Testing_Environment_Project](OWASP_Web_Testing_Environment_Project)
<p>| valign="top" style="padding-left:25px;width:200px;" |</p>
<p>| valign="top" style="padding-left:25px;width:200px;" |</p>
<h2 id="news_and_events">News and Events</h2>
<h2 id="news_and_events">News and Events</h2>
<p><a href="https://raw.githubusercontent.com/appsecpipeline/AppSecPipeline-Specification/master/reference/diagrams/pipeline-static.png">AppSecPipeline Specification Diagram</a></p>
<p><a href="https://raw.githubusercontent.com/appsecpipeline/AppSecPipeline-Specification/master/reference/diagrams/pipeline-static.png">AppSecPipeline Specification Diagram</a></p>
<h2 id="in_print">In Print</h2>
<h2 id="in_print">In Print</h2>
<p><a href="http://www.slideshare.net/weaveraaaron/building-an-appsec-pipeline-keeping-your-program-and-your-life-sane">Building an AppSec Pipeline</a><br />
<p><a href="http://www.slideshare.net/weaveraaaron/building-an-appsec-pipeline-keeping-your-program-and-your-life-sane">Building an AppSec Pipeline</a><br />
<a href="http://www.slideshare.net/mtesauro/mtesauro-keynote-appseceu">Taking DevOps practices into your AppSec Life</a></p></td>
<a href="http://www.slideshare.net/mtesauro/mtesauro-keynote-appseceu">Taking DevOps practices into your AppSec Life</a></p></td>
</tr>
</tr>
</tbody>
</tbody>
</table>
</table>


# Pipeline Tools
# Pipeline Tools


## What are DevOp Security Pipeline Tools?
## What are DevOp Security Pipeline Tools?


DevOp security pipeline tools are written with the mindset of API first.
DevOp security pipeline tools are written with the mindset of API first.
The goal is that a security tool will expose all the core functionality
The goal is that a security tool will expose all the core functionality
of the product as an API. Tools need to have an API so that the 'All the
of the product as an API. Tools need to have an API so that the 'All the
things' can be automated. Each tool will be evaluated with the criteria
things' can be automated. Each tool will be evaluated with the criteria
outlined below including example pipeline use cases.
outlined below including example pipeline use cases.


## Evaluation Criteria
## Evaluation Criteria


**Application Description:** Overview of the security tool, description
**Application Description:** Overview of the security tool, description
and product web page.
and product web page.
**API:** The type of API (REST, SOAP), API coverage (% of total features
**API:** The type of API (REST, SOAP), API coverage (% of total features
available via the API) and API Docs.
available via the API) and API Docs.
**Pipeline Position:** Where in the AppSec pipeline the tool would be
**Pipeline Position:** Where in the AppSec pipeline the tool would be
best suited to reside
best suited to reside
**Cloud Scalable:** Is the tool cloud aware and can the tool scale based
**Cloud Scalable:** Is the tool cloud aware and can the tool scale based
on demand?
on demand?
**Runs as a Service:** Can the tool run as a service or in headless
**Runs as a Service:** Can the tool run as a service or in headless
mode?
mode?
**Pipeline Example:** Link to an example use case of the tool in the
**Pipeline Example:** Link to an example use case of the tool in the
pipeline
pipeline
**Client Libraries:** What client libraries are written to assist in
**Client Libraries:** What client libraries are written to assist in
integration. For example a python or Go library.
integration. For example a python or Go library.
**CI/CD Plugins:** Does the tool have CI/CD plugins for integration into
**CI/CD Plugins:** Does the tool have CI/CD plugins for integration into
a DevOps pipeline. For example a Jenkins plugin.
a DevOps pipeline. For example a Jenkins plugin.
**Data Sent to the Cloud:** What kind of data, if any, is sent off
**Data Sent to the Cloud:** What kind of data, if any, is sent off
premise to the cloud? Is there an option to keep all data in-house?
premise to the cloud? Is there an option to keep all data in-house?


## Results
## Results


We are currently working on gathering a list of the current tools and
We are currently working on gathering a list of the current tools and
evaluating each tool based on the criteria listed. The goal is to create
evaluating each tool based on the criteria listed. The goal is to create
a one page wiki document of the application.
a one page wiki document of the application.


## Sample Tooling by Phase
## Sample Tooling by Phase


![<File:DevOps_AppSec_Tool_Integration.png>](DevOps_AppSec_Tool_Integration.png
![<File:DevOps_AppSec_Tool_Integration.png>](DevOps_AppSec_Tool_Integration.png
"File:DevOps_AppSec_Tool_Integration.png")
"File:DevOps_AppSec_Tool_Integration.png")


## Get Involved
## Get Involved


Interested in participating or having your product included in the
Interested in participating or having your product included in the
review? Contact [Aaron Weaver](mailto:aaron.weaver2@gmail.com)
review? Contact [Aaron Weaver](mailto:aaron.weaver2@gmail.com)


# Pipeline Design Patterns
# Pipeline Design Patterns


## What is an AppSec Pipeline?
## What is an AppSec Pipeline?


An AppSec Pipelines takes the principles of DevOps and Lean and applies
An AppSec Pipelines takes the principles of DevOps and Lean and applies
that to an application security program. An AppSec pipeline is designed
that to an application security program. An AppSec pipeline is designed
for iterative improvement and has the ability to grow in functionality
for iterative improvement and has the ability to grow in functionality
organically over time. When starting out an AppSec Pipeline choose the
organically over time. When starting out an AppSec Pipeline choose the
area that is your greatest pain point and work on a reusable path for
area that is your greatest pain point and work on a reusable path for
all the AppSec activities that follow.
all the AppSec activities that follow.


Pipelines have four distinct areas which will be covered in depth. The
Pipelines have four distinct areas which will be covered in depth. The
first is the "Intake process" or "first impression." This is where
first is the "Intake process" or "first impression." This is where
customers request AppSec services such as dynamic, static or manual
customers request AppSec services such as dynamic, static or manual
assessments from the AppSec team. The intake process consists of an
assessments from the AppSec team. The intake process consists of an
application repository that a requestor will either choose from a
application repository that a requestor will either choose from a
listing of applications or provide the details of the application. The
listing of applications or provide the details of the application. The
second part is "triage" where the determination is made for applying the
second part is "triage" where the determination is made for applying the
requested services. An application request may have an automated scan in
requested services. An application request may have an automated scan in
which case a request would be made to conduct a ZAP scan. The third part
which case a request would be made to conduct a ZAP scan. The third part
is "test" which is the heart of the pipeline. It is here where all the
is "test" which is the heart of the pipeline. It is here where all the
AppSec tools are automated, results are fed into a central repository
AppSec tools are automated, results are fed into a central repository
and reviewed for false positives. Finally the end of the pipeline is
and reviewed for false positives. Finally the end of the pipeline is
"deliver" where the results are distributed to the customer. This will
"deliver" where the results are distributed to the customer. This will
vary by organization, however most pipelines will integrate with a
vary by organization, however most pipelines will integrate with a
defect tracker and will produce summary metrics and reporting for senior
defect tracker and will produce summary metrics and reporting for senior
management.
management.


The goal of an AppSec Pipeline is to provides a consistent process from
The goal of an AppSec Pipeline is to provides a consistent process from
the application security team and the constituency which typically is
the application security team and the constituency which typically is
developers, QA, product managers and senior stakeholders. Throughout the
developers, QA, product managers and senior stakeholders. Throughout the
process flow each activity has well-defined states. The pipeline relies
process flow each activity has well-defined states. The pipeline relies
heavily on automation for repeatable tasks so that the critical
heavily on automation for repeatable tasks so that the critical
resource, AppSec personnel, is optimized.
resource, AppSec personnel, is optimized.


![AppSec_Pipeline_Rugged_DevOps.png](AppSec_Pipeline_Rugged_DevOps.png
![AppSec_Pipeline_Rugged_DevOps.png](AppSec_Pipeline_Rugged_DevOps.png
"AppSec_Pipeline_Rugged_DevOps.png")
"AppSec_Pipeline_Rugged_DevOps.png")


























































\===Pipeline - Intake (“First Impression”)=== The intake portion of the
\===Pipeline - Intake (“First Impression”)=== The intake portion of the
pipeline is one of the most important aspects of the pipeline. It is
pipeline is one of the most important aspects of the pipeline. It is
here where services are requested from the team. Each service request
here where services are requested from the team. Each service request
should be clearly stated and defined. For example consider grouping
should be clearly stated and defined. For example consider grouping
service requests into bundles. An application security assessment
service requests into bundles. An application security assessment
usually consists of a dynamic scan, static scan and manual review.
usually consists of a dynamic scan, static scan and manual review.
Bundle these into one request and title it 'Application Security
Bundle these into one request and title it 'Application Security
Assessment'.
Assessment'.


The pipeline request should feed into an application repository that
The pipeline request should feed into an application repository that
keeps track of the metadata on the application, key contacts, prior
keeps track of the metadata on the application, key contacts, prior
engagements and current vulnerabilities.
engagements and current vulnerabilities.


**Application Metadata**
**Application Metadata**
Knowing the background details about an application is an important part
Knowing the background details about an application is an important part
of carrying out a successful application assessment. By gathering this
of carrying out a successful application assessment. By gathering this
data key decisions can be automated. For example if you know that the
data key decisions can be automated. For example if you know that the
application being assessed is a critical application, has PII and has 1
application being assessed is a critical application, has PII and has 1
million records then you can automatically recommend and or require
million records then you can automatically recommend and or require
certain activities. These activities could include a threat model, an
certain activities. These activities could include a threat model, an
automated assessment with manual review.
automated assessment with manual review.
Key fields recommended for intake are the following:
Key fields recommended for intake are the following:


  - **Application General Information**: Name, Brief Description,
  - **Application General Information**: Name, Brief Description,
    Business Line
    Business Line
  - **Application Metadata**: Business Criticality, Platform, LIfecycle,
  - **Application Metadata**: Business Criticality, Platform, LIfecycle,
    Origin, User Records, Revenue, External Audience, Internet
    Origin, User Records, Revenue, External Audience, Internet
    Accessible
    Accessible
  - **Technologies**: Coding Language, Data Store, DDoS Protection,
  - **Technologies**: Coding Language, Data Store, DDoS Protection,
    Firewall, Framework, Hosting Provider, Operation System, Third-Party
    Firewall, Framework, Hosting Provider, Operation System, Third-Party
    Component, Web Server
    Component, Web Server
  - **Regulations**: Examples: PCI, SOC, FERPA DPA, SOX etc.
  - **Regulations**: Examples: PCI, SOC, FERPA DPA, SOX etc.
  - **Data Elements**: PII (First name, Last name, Email, Address,
  - **Data Elements**: PII (First name, Last name, Email, Address,
    Postal Code, Social)
    Postal Code, Social)


**Key Concepts**
**Key Concepts**


  - Bundle application service requests instead of offering al la carte.
  - Bundle application service requests instead of offering al la carte.
  - Ask for data about applications only once
  - Ask for data about applications only once
  - Have data reviewed periodically. (A great time is when new services
  - Have data reviewed periodically. (A great time is when new services
    are requested on the application.)
    are requested on the application.)


**Recommended Tools** A complete listing of tools and review will be in
**Recommended Tools** A complete listing of tools and review will be in
the Pipeline Tools section.
the Pipeline Tools section.


  - : An application security utility to assist in the organization and
  - : An application security utility to assist in the organization and
    prioritization of software security activities and defect tracking
    prioritization of software security activities and defect tracking
    application.
    application.
      - Dashboard showing entire application portfolio and last
      - Dashboard showing entire application portfolio and last
        engagement dates
        engagement dates
      - Applications requiring engagements
      - Applications requiring engagements
      - Importers for many scanners
      - Importers for many scanners
      - Integration with Jira
      - Integration with Jira
      - API for integration with security tools
      - API for integration with security tools


### Pipeline - Triage
### Pipeline - Triage


  - Inbound request triage
  - Inbound request triage
      - Ala Carte App Sec
      - Ala Carte App Sec
      - Dynamic Testing
      - Dynamic Testing
      - Static Testing
      - Static Testing
      - Re-Testing mitigated findings
      - Re-Testing mitigated findings
      - Mix and match based on risk
      - Mix and match based on risk


**Key Concepts**
**Key Concepts**


  - Activities can be run in parallel
  - Activities can be run in parallel
  - Automation on setup, configuration, data export
  - Automation on setup, configuration, data export
  - People focus on customization rather than setup
  - People focus on customization rather than setup


### Pipeline - Test
### Pipeline - Test


### Pipeline - Deliver
### Pipeline - Deliver


Source of truth for all AppSec activities
Source of truth for all AppSec activities


  - Dedupe / Consolidate findings
  - Dedupe / Consolidate findings
  - Normalize scanner data
  - Normalize scanner data
  - Generate Metrics
  - Generate Metrics
  - Push issues to bug trackers
  - Push issues to bug trackers
  - Report and metrics automation REST + tfclient
  - Report and metrics automation REST + tfclient
  - Source of many touch points with external teams
  - Source of many touch points with external teams


### How do I integrate an AppSec Pipeline into my existing pipeline(s)?
### How do I integrate an AppSec Pipeline into my existing pipeline(s)?


![DevOps_AppSec_Pipline_Integration.png](DevOps_AppSec_Pipline_Integration.png
![DevOps_AppSec_Pipline_Integration.png](DevOps_AppSec_Pipline_Integration.png
"DevOps_AppSec_Pipline_Integration.png")
"DevOps_AppSec_Pipline_Integration.png")


































## AppSec Pipeline Example \#1
## AppSec Pipeline Example \#1


![AppSec-Pipeline-Example.png](AppSec-Pipeline-Example.png "AppSec-Pipeline-Example.png")
"AppSec-Pipeline-Example.png")


































# Presentations
# Presentations


**AppSec Pipeline Presentations**
**AppSec Pipeline Presentations**


  - [Building An AppSec
  - [Building An AppSec
    Pipeline](https://www.youtube.com/watch?v=1CDSOSl4DQU) Aaron Weaver
    Pipeline](https://www.youtube.com/watch?v=1CDSOSl4DQU) Aaron Weaver
    - AppSec EU 2015
    - AppSec EU 2015
  - [Taking DevOps Practices Into Your AppSec
  - [Taking DevOps Practices Into Your AppSec
    Life](https://www.youtube.com/watch?v=tDnyFitE0y4) Matt Tesauro -
    Life](https://www.youtube.com/watch?v=tDnyFitE0y4) Matt Tesauro -
    AppSec EU 2015
    AppSec EU 2015


**Rugged DevOp Interviews**
**Rugged DevOp Interviews**


  - [DevOps, Security and Development w/ Matt Tesauro, Jez Humble and
  - [DevOps, Security and Development w/ Matt Tesauro, Jez Humble and
    Shannon
    Shannon
    Lietz](http://www.sonatype.org/nexus/2015/09/28/devops-security-and-development-w-matt-tesauro-jez-humble-and-shannon-lietz/)
    Lietz](http://www.sonatype.org/nexus/2015/09/28/devops-security-and-development-w-matt-tesauro-jez-humble-and-shannon-lietz/)
    AppSec USA 2015
    AppSec USA 2015
  - [Pipeline Project Interview](https://youtu.be/h3sw-N2KKfo) Matt
  - [Pipeline Project Interview](https://youtu.be/h3sw-N2KKfo) Matt
    Konda - AppSec USA 2015
    Konda - AppSec USA 2015


**Rugged DevOps**
**Rugged DevOps**


  - [The Road to Being
  - [The Road to Being
    Rugged](http://gotocon.com/dl/goto-london-2015/slides/ShannonLietz_TheRoadToBeingRugged.pdf)
    Rugged](http://gotocon.com/dl/goto-london-2015/slides/ShannonLietz_TheRoadToBeingRugged.pdf)
    Shannon Lietz - GOTO 2015
    Shannon Lietz - GOTO 2015
  - [When Devops Meets
  - [When Devops Meets
    Security](http://gotocon.com/dl/goto-london-2015/slides/MichaelBrunton-Spall_WhenDevopsMeetsSecurity.pdf)
    Security](http://gotocon.com/dl/goto-london-2015/slides/MichaelBrunton-Spall_WhenDevopsMeetsSecurity.pdf)
    Michael Brunton-Spall - GOTO 2015
    Michael Brunton-Spall - GOTO 2015
  - [Rugged Building Materials and Creating Agility with
  - [Rugged Building Materials and Creating Agility with
    Security](http://gotocon.com/dl/goto-london-2015/slides/DavidEtue_RuggedBuildingMaterialsAndCreatingAgilityWithSecurity.pdf)
    Security](http://gotocon.com/dl/goto-london-2015/slides/DavidEtue_RuggedBuildingMaterialsAndCreatingAgilityWithSecurity.pdf)
    David Etue - GOTO 2015
    David Etue - GOTO 2015
  - [How to effect change in the Epistemological Wasteland of
  - [How to effect change in the Epistemological Wasteland of
    Application
    Application
    Security](http://gotocon.com/dl/goto-london-2015/slides/JamesWickett_HowToEffectChangeInTheEpistemologicalWastelandOfApplicationSecurity.pdf)
    Security](http://gotocon.com/dl/goto-london-2015/slides/JamesWickett_HowToEffectChangeInTheEpistemologicalWastelandOfApplicationSecurity.pdf)
    James Wickett - GOTO 2015
    James Wickett - GOTO 2015


# Milestones
# Milestones


### Dockers Released
### Dockers Released


  - Released [AppSec Docker](https://hub.docker.com/u/appsecpipeline/)
  - Released [AppSec Docker](https://hub.docker.com/u/appsecpipeline/)


### Docker AppSec Pipeline Specification Released
### Docker AppSec Pipeline Specification Released


  - Beta Release: View the [Github
  - Beta Release: View the [Github
    repo](https://github.com/appsecpipeline/AppSecPipeline-Specification)
    repo](https://github.com/appsecpipeline/AppSecPipeline-Specification)
    and specification
    and specification


# FAQs
# FAQs


Got a question?
Got a question?


Ask us on Twitter:
Ask us on Twitter:


  - [@appsecpipeline](https://twitter.com/appsecpipeline)
  - [@appsecpipeline](https://twitter.com/appsecpipeline)
  - [@matt_tesauro](https://twitter.com/matt_tesauro)
  - [@matt_tesauro](https://twitter.com/matt_tesauro)
  - [@weavera](https://twitter.com/matt_tesauro)
  - [@weavera](https://twitter.com/matt_tesauro)


# Acknowledgements
# Acknowledgements


## Contributors
## Contributors


Besides the project leaders, contributions have been made by:
Besides the project leaders, contributions have been made by:


  -
  -
# Getting Involved
# Getting Involved


Involvement in the DevOps AppSec Pipeline is actively encouraged\!
Involvement in the DevOps AppSec Pipeline is actively encouraged\!


You do not have to be a security expert in order to contribute.
You do not have to be a security expert in order to contribute.


Some of the ways you can help:
Some of the ways you can help:


## Case Studies
## Case Studies


Share your AppSec Pipeline\! We would like to gather case studies on how
Share your AppSec Pipeline\! We would like to gather case studies on how
organizations are addressing AppSec at scale. Please email the project
organizations are addressing AppSec at scale. Please email the project
leaders to have your case study added.
leaders to have your case study added.


## Tools
## Tools


Is there a tool that is missing from our AppSec tooling review? Has your
Is there a tool that is missing from our AppSec tooling review? Has your
organization integrated or created a tool that integrates into the
organization integrated or created a tool that integrates into the
AppSec pipeline? Click on the 'Pipeline Tool's to contribute your
AppSec pipeline? Click on the 'Pipeline Tool's to contribute your
review/tool.
review/tool.


## Feedback
## Feedback


Please use our mailing list for feedback:
Please use our mailing list for feedback:


  - What do like?
  - What do like?
  - What don't you like?
  - What don't you like?


__NOTOC__ <headertabs />
__NOTOC__ <headertabs />


[Category:OWASP Project](Category:OWASP_Project "wikilink")
[Category:OWASP Project](Category:OWASP_Project "wikilink")
[Category:OWASP_Builders](Category:OWASP_Builders "wikilink")
[Category:OWASP_Builders](Category:OWASP_Builders "wikilink")
[Category:OWASP_Defenders](Category:OWASP_Defenders "wikilink")
[Category:OWASP_Defenders](Category:OWASP_Defenders "wikilink")
[Category:OWASP_Document](Category:OWASP_Document "wikilink") [AppSec
[Category:OWASP_Document](Category:OWASP_Document "wikilink") [AppSec
Pipeline](Category:Projects "wikilink") [AppSec
Pipeline](Category:Projects "wikilink") [AppSec
Pipeline](Category:Incubator_Projects "wikilink") [AppSec
Pipeline](Category:Incubator_Projects "wikilink") [AppSec
Pipeline](Category:OWASP_AppSec_Pipeline "wikilink")
Pipeline](Category:OWASP_AppSec_Pipeline "wikilink")
