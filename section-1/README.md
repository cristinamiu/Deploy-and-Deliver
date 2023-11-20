# Section 1 - Introduction

## Software Development Lifecycle (SDLC)

**The Software Development Life Cycle (SDLC)** refers to a methodology with clearly defined processes for creating high-quality software. in detail, the SDLC methodology focuses on the following phases of software development:

- **Planning and Requirement Analysis:** Here, security requirements and appropriate security choices that can mitigate potential threats and vulnerabilities are identified in this stage. What security design principles and best practices to be used are also thought about here.
- **Architectural Design:** The development team uses the security design principle and architecture to consider potential risks. This stage involves threat modelling, access control, encryption mechanism, and architecture risk analysis.
- **Software Development and Testing:** The code reviews are done to ensure software follows code standards and security controls are implemented. Security vulnerability tests like penetration testing are also done to identify potential issues.
- **Deployment:** Automated DevSecOps tools are used to improve application security. To ensure the software is deployed securely, firewalls, access controls, and security settings are configured.
- **Maintenance:** Security continues after deployment. The team must continuously monitor the software for security vulnerabilities. The team would also update the software with security patches and updates as necessary.

![SDLC](/images/section-1/sdlc.png)

## SDLC Models

### Waterfall
The Waterfall Model was the first Process Model to be introduced. It is also referred to as a linear-sequential life cycle model. It is very simple to understand and use. In a waterfall model, each phase must be completed before the next phase can begin and there is no overlapping in the phases.

![Waterfall](/images/section-1/waterfall.jpg)

### Agile
The meaning of Agile is swift or versatile."Agile process model" refers to a software development approach based on iterative development. Agile methods break tasks into smaller iterations, or parts do not directly involve long term planning. The project scope and requirements are laid down at the beginning of the development process. Plans regarding the number of iterations, the duration and the scope of each iteration are clearly defined in advance.

Each iteration is considered as a short time "frame" in the Agile process model, which typically lasts from one to four weeks. The division of the entire project into smaller parts helps to minimize the project risk and to reduce the overall project delivery time requirements. Each iteration involves a team working through a full software development life cycle including planning, requirements analysis, design, coding, and testing before a working product is demonstrated to the client.

![Agile](/images/section-1/agile.png)

### DevOps Lifecycle
![DevOps](/images/section-1/dev_ops.jpg)



## CI/CD

### Continuous Integration
With continuous integration, developers frequently commit to a shared repository using a version control system such as Git. Prior to each commit, developers may choose to run local unit tests on their code as an extra verification layer before integrating. A continuous integration service automatically builds and runs unit tests on the new code changes to immediately surface any errors.

![CI](/images/section-1/ci.png)

### Continuous Delivery

Continuous delivery is a software development practice where code changes are automatically prepared for a release to production. A pillar of modern application development, continuous delivery expands upon continuous integration by deploying all code changes to a testing environment and/or a production environment after the build stage. When properly implemented, developers will always have a deployment-ready build artifact that has passed through a standardized test process. 

Continuous delivery lets developers automate testing beyond just unit tests so they can verify application updates across multiple dimensions before deploying to customers. These tests may include UI testing, load testing, integration testing, API reliability testing, etc. This helps developers more thoroughly validate updates and pre-emptively discover issues. With the cloud, it is easy and cost-effective to automate the creation and replication of multiple environments for testing, which was previously difficult to do on-premises

With continuous delivery, every code change is built, tested, and then pushed to a non-production testing or staging environment. There can be multiple, parallel test stages before a production deployment. The difference between continuous delivery and continuous deployment is the presence of a manual approval to update to production. With continuous deployment, production happens automatically without explicit approval. 

![CD](/images/section-1/cd.png)