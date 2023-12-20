# CNCF Project Lifecycles - an Overview

_Version 2.0_

The Cloud Native Computing Foundation (CNCF) leverages a maturity project lifecycle with periodic check points to recognize, elevate, or archive projects within the Foundation. The Moving Levls process describes the levels a project may be accepted under and what the criteria and expectations are for a given level, as well as the evaluation criteria for a project to move from one level to another. It leverages the Due Dilligence process as a mechanism to assess and evaluate expected project maturity for each level against the defined critiera.

Project progression, movement from one level to another, allows projects to participate within the ecosystem and receive benefits of that participation at the level that is most appropriate for them given where they are in their lifecycle.


## Levels - Definitions & Expectations

CNCF projects have a maturity level of sandbox, incubating, or graduated. Archived is for projects no longer in active development or sustainment. A project's maturity level is a signal by Technical Oversight Committee (TOC), and subsequently the CNCF, as to what sorts of enterprises should be adopting different projects. 

Projects demonstrate their maturity achievements by providing a self-assessment in the form of a Pull Request on the TOC repo when they have completed all criteria. The criteria are designed for projects to achieve adoption, software engineering practices, security, release stability, community advancement, and sustainable governance among a variety of other characteristics that support projects in their long term susccess. 

![Project Stages](https://github.com/cncf/toc/blob/main/process/project-stages.png)

### Sandbox

The CNCF [Sandbox](https://sandbox.cncf.io) is the entry point for early maturity projects and has four goals:

* Encourage public visibility of experiments or other early work that can add value to the CNCF mission and build the ingredients of a successful Incubation level project
* Facilitate alignment and interoperability with existing projects if (and only if) this is desired
* Nurture projects (e.g. via CNCF Service Desk requests)
* Remove possible legal and governance obstacles to adoption and contribution by ensuring all projects adhere to CNCF legal, Code of Conduct, and IP Policy requirements

Projects being applying to the CNCF at the sandbox level are intended to be the entry point for early stage projects and are not required to undergo due diligence. Sandbox projects should be early-stage projects that the CNCF TOC believes warrant experimentation.

* New projects that are designed to extend one or more CNCF projects with functionality or interoperability libraries.
* Independent projects that fit the CNCF mission and provide potential for a novel approach to existing functional areas (or are an attempt to meet an unfulfilled need)
* Projects commissioned or sanctioned by the CNCF, including initial code for CNCF WG collaborations, and "experimental" projects
* Any project that realistically intends to join CNCF Incubation in future and wishes to lay the foundations for that

Projects apply through the Sandbox Repo's *[Issue Form](https://github.com/cncf/sandbox/issues/new)*. More information on this process is found on the main [Sandbox repo page](https://github.com/cncf/sandbox).
Frequency of reviews can be found on the [repo's README under "Frequency"](https://github.com/cncf/sandbox/blob/main/README.md#Frequency).

The TOC reviews sandbox applications on a rotating basis, approximately every two months as of Novemeber 2023. The TOC reviews approximately 10-15 projects per review cycle. Throughput of reviews is limited by project complexity, information presented in the application, technical capabilities of the project, and general understanding of the problem space being addressed.

### Incubating

Incubating projects are mid-maturity projects that have a well defined vision, are growing in their adoption, and developing stability and resiliency in their development and governance practices. Incubating projects have access to all resources listed at https://cncf.io/services-for-projects, and have a presence at KubeCon+CloudNativeCon.

Incubating projects are required to undergo Due Diligence as a part of the process to move from Sandbox to Incubation. The Due Diligence is completed by one or more TOC sponsors and may take five months or more to complete the document. Once complete, the TOC performs and internal review and then may open the application and due diligence for public comment lasting two weeks before a vote is called.

### Graduated

Graduated projects signal the highest level of maturity for a CNCF project and are characterized by refined governance, well-maintained communities, production-ready releases, and a variety of other factors that allow adopters to achieve and retain confidence in the project. Graduated projects have access to all resources listed at https://cncf.io/services-for-projects, and have a presence at KubeCon+CloudNativeCon.

### Archived

Archived projects are no longer in active development or maintenance. Projects are only archived after completion of the [Archiving process](archiving.md) which includes a vote for archival by the TOC.

Open source projects have a lifecycle and there are times that projects become inactive due to a variety of reasons. There are also cases where a project may no longer want to be supported by the TOC, or the TOC may no longer wish to recommend the use of a project. For more information on the Archiving, please refer to the[Archiving process document](archiving.md).

## Project Application Process

This governance policy sets forth the application process for projects to be accepted into the CNCF.
The process is the same for both existing projects which seek to move into the Foundation, and new projects to be formed within the CNCF.

### Application to join the CNCF

In addition to the Sandbox level, projects may also apply to join the CNCF at the Incubation level. Directly applying for Graduation level is typically discouraged as growing into Graduation level maturity has dependencies on ecosystem, community, and project interactions. If a project applies and is accepted at Incubation level, they may apply to Graduation level when they feel they are ready. Provided no significant time has passed or no substantial changes have incurred since Incubation Due Diligemce, the Graduation Due Diligence may be completed more readily. 

Projects interested in joining the CNCF should review the [**Maturity Criteria**](maturity-criteria.md) to understand the most appropriate maturity level for them to apply.

#### Submitting the Application

The Application process for Incubation and Graduation is initiated by submitting a pull request to the TOC repo leveraging the Project Application Template.

### Annual Reviews

All CNCF projects are subject to a semi-automated annual review that is designed to understand the health of the project, its maturity progress for the level is exists within, and to ascertain any needs or challenges the project may experience. The Annual Review is intended to be a lightweight process to ensure that projects are on track, and getting the support they need. It leverages data collected from the project's repositories and includes an interactive assessment to help inform the TOC on areas of the project that are unobservable programmatically.

The content of an Annual Review may trigger a project to be archived or to be recommended to apply for the next level of maturity.

The TOC understands that each project may reach the next stage of maturity in its own time while it reamins active. The Annual Review supports the TOC in understanding a project's progress to the next level as well as understanding the current, overall health of projects within the ecosystem.
