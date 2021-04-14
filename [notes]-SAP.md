# SAP - Systems Applications and Products in data processing
----------

Costa Rica

Belinda Brown, belindabrownr04@gmail.com

April, 2021

----------

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

## Acronyms

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

## Implementation Basic Steps 
An SAP implementation has five basic steps:

1. Project preparation
2. Business blueprint 
3. Realization
4. Final preparation
5. Go Live support


## Protocols for Remote Connections 
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

## Active Control 
`DevOps Automation Technology, Engineered for SAP` <br/>
Similar functionality of Transport Express.Delivers a fundamentally new approach to change and release with automation that enables companies to adopt agile development, DevOps and Continuous Delivery. 
 

## Landscape Management  
A landscape is defined as an arrangement of SAP servers. Based on SAP configurations, customizations and combinations of SAP and third-party modules.

### Types 
> SAP is divided into three different landscape DEV, QAS and PRD.
>
> – DEV would have multiple clients for ex: 190- Sandbox, 100- Golden, 180 – Unit Test. <br/>
> – QAS may again have multiple clients for ex: 300- Integration Test, 700 to 710 Training. <br/>
> – PRD may have something like a 200 Production. <br/>
> -- <cite> Denis from SAP Community </cite>
 
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




