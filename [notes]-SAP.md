<h1 align="center"> SAP - Systems Applications and Products in data processing </h1>

----------

Costa Rica

Belinda Brown, belindabrownr04@gmail.com

April, 2021

----------

<h2 align="center"> Useful SAP transaction codes: ABAP, Data Dictionary, FI and CO </h2>
From [20]

[embed]https://github.com/brown9804/SAP_initial_path/blob/main/_docs/ref/transaction-codes-list.pdf[/embed]

<h2 align="center"> Acronyms </h2>

- `TP or tp ` - The Transport Control Program: SAP program that admins use for performing and planning transports between systems and also in upgrades of the SAP systems`
- `CBP` - Critical Business Process
- `PTM` - Project Transport Manager
- `UAT` - User Acceptance Testing 
- `SIT` -  System Integration Testing.
- `LOP` - Line Opener Program
- `SRU` - SAP Release Upgrade
- `ERP` - Enterprise Resource Planning
- `SO` - Service Operation
- `CAB` - Change Advisory Board
- `CI` - Continuous Improvement or Continuous Integration (Related to Agile Methodology)
- `ELS` - Engineered Labor Standards or Early Life Support 
- `GTP` - Global Technical Process
- `SID` - System Identifier or System Instances
- `NNIT` - Non-Negative Impact Testing
- `MDF` -  Market Development Funds
- `OOP` - Object-Oriented-Programming
- `TDD` - Test-Driven-Development
- `MADF` - Modern Application Development Framework
-`gCTS` - Git-enabled Change and Transport
- `RFC` - Request for a Change
- `LEM` - Local Enterprise Model
- `BADI` - Bussiness Add-ins
- `CDS` - Core Data Services 
- `DCL` - Data Control Language
- `ICM` - Integrated Change Management 
- `TNC` - Transport Naming Convention 
- `TSP` - Test System Protection 
- `CMP` - Change Management Process 




<h2 align="center"> Implementation Basic Steps  </h2>

An SAP implementation has five basic steps:

1. Project preparation
2. Business blueprint 
3. Realization
4. Final preparation
5. Go Live support


<h2 align="center"> Protocols for Remote Connections  </h2>

|Protocol  | Definition |
|---|---|
| HTTP	| Hypertext Transfer Protocol | 
| HTTPS | Hypertext Transfer Protocol Secure |
| SSH	| Secure Shell |
| WTS	| Windows Terminal Server |
|ERP | 	Enterprise Resource Planning |
|LOP	 | Line Opener Program |
| SID	(SAP)  | System ID |
| SNOW	 | Service Now Tool |

<h2 align="center"> Active Control   </h2>

`DevOps Automation Technology, Engineered for SAP` <br/>
Similar functionality of Transport Express.Delivers a fundamentally new approach to change and release with automation that enables companies to adopt agile development, DevOps and Continuous Delivery.


<h2 align="center"> Dual Maintenance  </h2>

> The entire objective of dual maintenance is to keep the current 
> and the upgraded system in sync with each other. Dual maintenance 
> starts as soon as the upgraded system becomes available.
> 
> We mostly have two types of transports which qualify for dual maintenance:
> - New Transports: These are the new transports that will be created once the 
> system becomes available to the team for dual maintenance.
> - Retro Transports: These are the existing transports that have 
> been in Dev and QA system and never made to Production.
> 
> Assumptions:
>  - DC1 – Existing ECC Dev System
>  - DC2 – Upgraded ECC Dev System
>
> Prerequisites:
> RFC Connection between upgraded(DC1) and non-upgraded system(DC2).
> 
> -- <cite> SAP Community  </cite>

 
 
 
<h2 align="center"> Application Management Security  </h2>

> SAP security is a balancing act that involves all the tools, 
> processes, and controls set in place in order to restrict what 
> users can access within an SAP landscape. This helps ensure that 
> users only can access the functionality they need to do their job. 
> They should be prevented from viewing or altering data they aren’t 
> authorized to see. At the same time, the access controls need to be
> seamless, so people don’t get locked out of their workflows and 
> spend unproductive time getting back to work.
> 
> -- <cite> Symmetry  </cite>


<h2 align="center"> Landscape Management    </h2>
A landscape is defined as an arrangement of SAP servers. Based on SAP configurations, customizations and combinations of SAP and third-party modules.

### Types 
> SAP is divided into three different landscape DEV, QAS and PRD.
>
> – DEV would have multiple clients for ex: 190- Sandbox, 100- Golden, 180 – Unit Test. <br/>
> – QAS may again have multiple clients for ex: 300- Integration Test, 700 to 710 Training. <br/>
> – PRD may have something like a 200 Production. <br/>
> -- <cite> Denis from SAP Community </cite>
 
 ### Layers 
 Three main layers:
 - Development 
 - QA (might have multiple instances)
 - Production
 
 Required: 
 
 1. Development 
 2. SIT
 3. UAT
 4. Production
 
 Additional:
 
 1. Sandbox
 2. Training 
 3. Deployment
 4. Fire-fighting
 
 ### Modules 
- SAP Financial Accounting (FI)
- SAP Controlling (CO)
- SAP Sales and Distribution (SD)
- SAP Production Planning (PP)
- SAP Materials Management (MM)
- SAP Quality Management (QM)
- SAP Human Capital Management (HCM)

### Boxes 
Each box is divided considering three characteristics:
1. Region 
2. Process or Action 
3. Environments 

Following this convention:
-`E` - Engineering <br/>
-`D` - Development <br/>
-`R` - Rollout <br/>
-`A` - Acceptance <br/>
-`C` - Deployment Rehearsal <br/>
-`P` - Production <br/>
-`Q` - Quality assurance <br/>

### Environments
- `E` - Sandbox <br/>
- `D` - Development <br/>
- `R` - SIT <br/>
- `A` - UAT <br/>
- `C` - Deployment Releasal systems <br/>
- `P` - Production <br/>
- `Q` - Fire-fighting systems <br/>

And Lower Level SAP Release Update System (e.g. KLM).

### Tables 
Standard tables:
| Table Name  |  Acronym | 
|---|---|
| Customer   | KN*  |
| Sales  | VB*,VA*,VK*  |
| Shipping | VT*,VB*,VE*  |
| Delivery | LI*  |
| Material Master  | MA*, MB*, MK*, MS*, MV*  |
| Billing  | VB*,VR*,VK*  |
| Pricing  | KO*  |
| Purchasing   | EK*,EI*  |
| Vendor Master | LF* |
| FI Tables | BS*   |
| Cost Centre Accounting | CO*CS* |
| Organizational Elements | T001*|

### UAT 
Basic steps:
1. User Acceptance Test (UAT) Planning
2. Designing UA Test Cases
3. Selecting a Team that would execute the (UAT) Test Cases
4. Executing Test Cases
5. Documenting the Defects found during UAT
6. Resolving the issues/Bug Fixing
7. Sign Off

### Logical System Layer
- DEV
- SIT
- BAT
- TCO
- Prod

<h2 align="center"> Requirements    </h2>

The requirements most be defined. All the requirements are established so the project period is defined.

<h2 align="center"> Design    </h2>

The project's separated into several phases which are linear dependent on each other. Every stage or phase depends on the deliverables of the previous one and so on. It's acceptable a 2 % of bad namings since it's required to follow a TNC. And it's not right to have transports open for more than a hundred years.

<h2 align="center"> Build    </h2>

Considering Agile Methodologies:
> Agile methodology is a type of project management process, 
> mainly used for software development, where demands and solutions 
> evolve through the collaborative effort of self-organizing and 
> cross-functional teams and their customers.
> 
> The Agile methodology is a collection of principles that
> value adaptability and flexibility. Agile  aims to provide better 
> responsiveness to changing business needs and therefore focuses on 
> enabling teams to deliver in workable increments.
>  
> -- <cite> Zenkit  </cite>

And it's importante to consider the Object-Oriented-Programming and Test-Driven-Development.


<h2 align="center"> Test    </h2>
Try to test using automated processes. It will help to decrease the defects leaking past the application building phase. Consider TSP.

<h2 align="center"> Deploy    </h2>

We need to watch the transports. The transport (like pipeline: `a pipeline is the continuous and somewhat overlapped movement of instruction to the processor or in the arithmetic steps taken by the processor to perform an instruction` ) is the mobile for any changes that are recorded for technical deployment. Try to do CD/CD which means Continuous Delivery and Continuous Deployment. Consider CMP.

<h2 align="center"> Virtual Data Model    </h2>


![Google Images diagram for VDM ](https://images.contentstack.io/v3/assets/bltd28bcb63149827a2/blt5814251608278d07/5f34665b48d3b57cb974a25f/Architecture_with_frame.png?disposition=inline)

<h2 align="center"> SAP Hana Architecture   </h2>

From PWC | India 
![SAP Hana Architecture  ](https://github.com/brown9804/SAP_initial_path/blob/main/_docs/img/%5Bimg%5D_sap_hana_infractructure.png)


<h3 align="center"> SDI Architecture    </h3>


![HANA SDI Architecture ](https://datacadamia.com/_media/db/hana/hana_sdi_architecture.png?cache=)





## References 
[1] What is an SAP Implementation - From https://symmetrycorp.com/blog/expert-insight-sap-implementation-2/ <br/>
[2] System Landscape & Architecture - From https://www.tutorialspoint.com/sap_basis/sap_basis_system_landscape_architecture.htm#:~:text=SAP%20system%20landscape%20is%20defined%20as%20an%20arrangement%20of%20SAP%20servers.&text=A%20system%20landscape%20consists%20of,time%20unlike%20the%20system%20landscape. <br/>
[3] TRANSPORT EXPRESS - From https://answers.sap.com/questions/6847117/transport-express.html <br/>
[4] Active Control - From https://www.basistechnologies.com/products/activecontrol/ <br/>
[5] UAT AND SIT - From https://answers.sap.com/questions/5412262/uat-and-sit.html <br/>
[6] Semi-Automatic Service Line Opener (LOP) - From https://support.sap.com/en/tools/connectivity-tools/line-opener.html <br/>
[7] SRU - From https://help.sap.com/doc/e2048712f0ab45e791e6d15ba5e20c68/2020/en-US/FSD_OP2020_latest.pdf <br/>
[8] Landscape types - From https://blogs.sap.com/2012/06/14/what-is-sap-landscape/#:~:text=SAP%20is%20divided%20into%20three,Golden%2C%20180%20%E2%80%93%20Unit%20Test. <br/>
[9] SAP Modules - From https://www.simplilearn.com/sap-modules-sap-fi-sap-co-sap-sd-sap-hcm-and-more-rar111-article <br/>
[10] SAP Tables - From https://blogs.sap.com/2013/07/20/sap-standard-tables/ <br/>
[11] CAB SAP - From https://blogs.sap.com/2016/08/30/why-do-you-need-an-sap-change-advisory-board-cab-who-should-be-on-it-part-iii-of-iv/ <br/>
[12] CI - From https://www.atlassian.com/continuous-delivery/continuous-integration <br/>
[13] ELS - From https://help.sap.com/saphelp_ewm700_ehp02/helpdata/en/ec/cacb53ad377114e10000000a174cb4/content.htm?no_cache=true#:~:text=Configuring%20Engineered%20Labor%20Standards%20(ELS)%20%2D%20SAP%20Documentation <br/>
[14] GTP - From https://blog.purestorage.com/news-events/sap-global-technology-partnership/ <br/>
[15] SID - From http://www.cvosoft.com/glosario-sap/sap/sid-674.html <br/>
[16] SAP project - From https://www.linkedin.com/learning/transitioning-from-waterfall-to-agile-project-management-6/agile-paradigm-shift?u=2095204 <br/>
[17] Agile Methodologies - From https://www.agilealliance.org/agile101/ <br/>
[18] Dual Maintenance - From https://blogs.sap.com/2019/05/31/dual-maintenance-management/ <br/>
[19] SAP Application Management Security - From https://symmetrycorp.com/blog/sap-security-basics-what-you-need-to-know/ <br/>
[20] Useful SAP commands - From https://www.system-overload.org/sap/transaction-codes-list.pdf <br/>
