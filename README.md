# Devop
Q. What is DevOps 
Ans - DevOps is a set of practices, tools, and a cultural philosophy that automates and integrates the processes between software development and IT teams. It emphasizes team empowerment, cross-team communication, collaboration, and technology automation.
Q. Cycle Of Devops 
Ans - The DevOps lifecycle is a series of automated development processes or workflows within an iterative development lifecycle. It aims to optimize the rapid delivery of high-quality software. There are  the seven phases of the DevOps lifecycle:

 1. Planning: In this phase, teams define project goals, requirements, and timelines.
    Tools: Jira, Trello, or other project management tools.
 
 2. Development: Developers write code based on the project requirements.
    Tools: Git, GitHub, or other version control systems.

 3. Testing: Automated and manual testing ensures code quality.
    Tools: JUnit, Selenium, or other testing frameworks.

 4. Deployment: Code is deployed to production or staging environments.
    Tools: Jenkins, GitLab CI/CD, or other continuous integration/continuous deployment (CI/CD) tools.

 5. Monitoring: Continuous monitoring of applications and infrastructure.
    Tools: Prometheus, Grafana, or other monitoring solutions.

 6. Feedback: Collect feedback from users, monitor performance, and address issues.
    Tools: User feedback channels, log analysis, or other feedback mechanisms.

 7. Operations: Maintain and operate the software in production.
    Tools: Kubernetes, Docker, or other containerization and orchestration tools.
/
Q. What is Monolithic and microlithic Architecture ?
Ans -
1. Monolithic Architecture: A monolithic application is built as a single unit.  It is a traditional model where all components (such as the user interface, business logic, and database) are tightly coupled and interconnected together within one codebase. 
= To make changes, you need to update the entire stack.
Deploymnet : Requires full apllication
Technology : Sinle language used
Maintain : Changes may impact the entire application.

2. Microservices Architecture: A microservices architecture consists of small, independently deployable services that communicate with each other via APIs (Application program interface).
Deploymnet : Independent deployment of service.
Technology : multiple language used
Maintain : Change in one service doesn't affect other.
