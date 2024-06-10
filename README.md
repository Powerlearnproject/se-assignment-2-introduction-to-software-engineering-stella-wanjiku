[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/-ucQIGTc)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-718a45dd9cf7e7f842a935f5ebbe5719a5e09af4491e668f4dbf3b35d5cca122.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15243847&assignment_repo_type=AssignmentRepo)
# SE-Assignment-2
Assignment: Introduction to Software Engineering
Instructions:
Answer the following questions based on your understanding of software engineering concepts. Provide detailed explanations and examples where appropriate.

Questions:
Define Software Engineering:

What is software engineering, and how does it differ from traditional programming?
It is the branch of computer science that deals with the design, development, testing, and maintenance of software applications.
Software engineering deals with the aspect of the software creation, concept, design and coding. Traditional programming is mainly concerned with wring code to solve a specific problem.

Software Development Life Cycle (SDLC):

Explain the various phases of the Software Development Life Cycle. Provide a brief description of each phase.
1. Planning & Analysis
The first phase of the SDLC is the project planning stage where you are gathering business requirements from your client or stakeholders. This phase is when you evaluate the feasibility of creating the product, revenue potential, the cost of production, the needs of the end-user.

2. Define Requirements
This phase is critical for converting the information gathered during the planning and analysis phase into clear requirements for the development team.his process guides the development of several important documents: a software requirement specification (SRS) or product specification.
3. Design
The original plan and vision are elaborated into a software design document (SDD) that includes the system design, programming language, templates, platform to use, and application security measures. This is also where you can flowchart how the software responds to user actions.
4. Development
The actual development phase is where the development team members divide the project into software modules and turn the software requirement into code that makes the product. 
5. Testing
Before getting the software product out the door to the production environment, it’s important to have your quality assurance team perform validation testing to make sure it is functioning properly and does what it’s meant to do. The testing process can also help hash out any major user experience issues and security issues.
6. Deployment
During the deployment phase, final product is delivered to your intended user. 
7. Maintenance
The maintenance phase is the final stage of the SDLC.
In the maintenance stage, users may find bugs and errors that were missed in the earlier testing phase. These bugs need to be fixed for better user experience and retention.

Agile vs. Waterfall Models:

Compare and contrast the Agile and Waterfall models of software development. What are the key differences, and in what scenarios might each be preferred?
Waterfall is a linear, sequential approach, where each phase of the project must be completed before moving on to the next phase. Flexibility: Agile is flexible and adaptable to change, allowing teams to respond quickly to changing requirements and to incorporate new ideas and feedback as they arise.

Requirements Engineering:

What is requirements engineering? Describe the process and its importance in the software development lifecycle.
Requirements Engineering is the process of identifying, eliciting, analyzing, specifying, validating, and managing the needs and expectations of stakeholders for a software system.
Feasibility Study is the most important part of the feasibility analysis and the Legal Feasibility Study is less considered feasibility analysis
2. Requirements Elicitation
It is related to the various ways used to gain knowledge about the project domain and requirements. The various sources of domain knowledge include customers, business manuals, the existing software of the same type, standards, and other stakeholders of the project.
3. Requirements Specification
This activity is used to produce formal software requirement models. All the requirements including the functional as well as the non-functional requirements and the constraints are specified by these models in totality.
4. Requirements Verification and Validation
Verification: It refers to the set of tasks that ensures that the software correctly implements a specific function. 
Validation: It refers to a different set of tasks that ensures that the software that has been built is traceable to customer requirements.
5. Requirements Management
Requirement management is the process of analyzing, documenting, tracking, prioritizing, and agreeing on the requirement and controlling the communication with relevant stakeholders. 
Requirements management is a critical step in the software development life cycle as it helps to ensure that the software system being developed meets the needs and expectations of stakeholders and that it is developed on time, within budget, and to the required quality. It also helps to prevent scope creep and to ensure that the requirements are aligned with the project goals.

Software Design Principles:

Explain the concept of modularity in software design. How does it improve maintainability and scalability of software systems?
Modularity in software design is a technique where complex software is divided into smaller, independent modules, such as functions, classes, or components. It facilitates easier management and understanding of complex systems by breaking them down into digestible parts.

Testing in Software Engineering:

Describe the different levels of software testing (unit testing, integration testing, system testing, acceptance testing). Why is testing crucial in software development?
testing crucial in software development?
1. Unit testing
Unit tests are very low level and close to the source of an application. They consist in testing individual methods and functions of the classes, components, or modules used by your software.
2. Integration testing
Integration tests verify that different modules or services used by your application work well together. For example, it can be testing the interaction with the database or making sure that microservices work together as expected. 
3. System testing
System Testing is the phase where a tester checks a complete and fully integrated system as a whole. At this stage, QA Engineers integrate all units to verify whether the developed product works properly and meets the specified requirements. 
4. Acceptance testing
Acceptance Testing is the last level of software testing that is carried out before the product goes live. Testers conduct this type of testing to help the customer evaluate the obtained result and check whether the system meets the acceptance criteria. 

Version Control Systems:

What are version control systems, and why are they important in software development? Give examples of popular version control systems and their features.
Version control systems are a category of software tools that helps in recording changes made to files by keeping a track of modifications done in the code. 
Why its important in software development?
A version control system is a kind of software that helps the developer team to efficiently communicate and manage(track) all the changes that have been made to the source code along with the information like who made and what changes have been made. 
Enhances the project development speed by providing efficient collaboration,
Leverages the productivity, expedites product delivery, and skills of the employees through better communication and assistance,
Reduce possibilities of errors and conflicts meanwhile project development through traceability to every small change,
Types of Version Control Systems: 
Local Version Control Systems
-  It is one of the simplest forms and has a database that kept all the changes to files under revision control. RCS is one of the most common VCS tools
Centralized Version Control Systems
Contain just one repository globally and every user need to commit for reflecting one’s changes in the repository.Makes collaboration amongst developers along with providing an insight to a certain extent on what everyone else is doing on the project 
Distributed Version Control Systems
Distributed version control systems 
Contain multiple repositories and each user has their own repository and working copy.The most popular distributed version control systems are Git, and Mercurial. They help us overcome the problem of single point of failure.


Software Project Management:

Discuss the role of a software project manager. What are some key responsibilities and challenges faced in managing software projects?
Software Maintenance:
The project manager is responsible for day-to-day management of the project and must be competent in managing the six aspects of a project, i.e. scope, schedule, finance, risk, quality and resources.  
Challenges faced are:  lack of the necessary skills on your team.
Undefined Goals. One of the most common challenges in project management is identifying project goals. Lack of accountability, Improper Risk Management, ambiguous Contingency Plans, poor Communication and Impossible deadlines.

Define software maintenance and explain the different types of maintenance activities. Why is maintenance an essential part of the software lifecycle?

Software Maintenance refers to the process of modifying and updating a software system after it has been delivered to the customer.
Corrective Maintenance: This involves fixing errors and bugs in the software system.
Patching: It is an emergency fix implemented mainly due to pressure from management. Patching is done for corrective maintenance but it gives rise to unforeseen future errors due to lack of proper impact analysis.
Adaptive Maintenance: This involves modifying the software system to adapt it to changes in the environment, such as changes in hardware or software, government policies, and business rules.
Perfective Maintenance: This involves improving functionality, performance, and reliability, and restructuring the software system to improve changeability.
Preventive Maintenance: This involves taking measures to prevent future problems, such as optimization, updating documentation, reviewing and testing the system, and implementing preventive measures such as backups.
Software maintenance is also an important part of the Software Development. To update the software application and do all modifications in software application so as to improve performance is the main focus of software maintenance.

Ethical Considerations in Software Engineering:

What are some ethical issues that software engineers might face? How can software engineers ensure they adhere to ethical standards in their work?
Ethics refers to the moral principles that guide a person's behavior or decision-making. In the context of software engineering, ethical decision-making is about considering the impact of one's choices on individuals, society, and the environment. It goes beyond simply following legal regulations and instead focuses on doing what is morally right.
here are several reasons why ethical decision-making is important in software engineering:

1. User Trust: Building and maintaining user trust is crucial for the success of any software product or service. 
2. Avoiding Harm: Software can have a profound impact on people's lives.
3. Long-Term Sustainability: Ethical decisions are often aligned with long-term sustainability.
4. Legal and Regulatory Compliance: Ethical decision-making serves as a foundation for complying with legal and regulatory requirements.
   References:
https://www.geeksforgeeks.
https://moldstud.com/articles.

Submission Guidelines:
Your answers should be well-structured, concise, and to the point.
Provide real-world examples or case studies wherever possible.
Cite any references or sources you use in your answers.
Submit your completed assignment by [due date].
