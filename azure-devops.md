
# Interview Questions for Azure DevOps

1. what is Azure DevOps and its core services?

    Azure DevOps is Microsoft Integrated solution for managing the entire application lifecycle. Microsoft Says : "Azure DevOps is cloud based platform which provide you several tools for        software development, that includes everything you need to plan work, collaborate on code, build applications, test functionality and deploy them to production.

    - Dashboards
    - Wiki
    - Boards: Tracks your works using visual Kanban boards, assign the work to colleague and          collaborate
    - Repos: A set of version control tools, you can use to manage your code, 
    - Pipelines: A CI/CD service used to manage and deploy the code to any platform.
    - Test Plans: You have Azure Test Plans which provide several tools to test the code and          manage/track the bugs 
    - Artifacts: Azure Devops service to create, host and share the Software packages like ``npm``, ``maven``, ``python``, and universal package from public or private sources. 

2. Give an example of Azure DevOps to explain how it can benefit the work.

   Imagine a team is planning an implementation of a complex IT System, lets say a CRM system or a website, there are a lots of tasks to handle in this such as provision a server, document      the requirements, you probably need to migrate all the data, tweak the UI, integrate with other systems etc. Now Azure DevOps can be used here as a central digital board to track and         manage all the work that needs to be done to finish the project.

3. What is Azure Boards?

   Azure Boards provides an agile dashboard which helps you to plan, track and manage the     project for day to day activities using the agile methodologies. It has native support for Scrum    and Kanban. Azure boards consist of rich UI based dashboard, where you can track user stories, issues, bugs, and extract reports in quickest way possible.

4. What is Azure Pipelines?

   Azure Pipelines is the part of Azure DevOps which combines continuous integration, continuous testing and continuous delivery to automatically build, test and deploy code projects to any destination. Azure Pipelines supports all major language, project types and can also automate the workflow in your chosen technologies or framework whether app is on-premises or in the cloud.

   <img width="1526" height="615" alt="image" src="https://github.com/user-attachments/assets/2ca7c3fc-6a0a-4cce-89e3-f6f228ed90d7" />


6. What is Pipelines Triggers?

   A pipeline trigger simply tells a pipeline when to run on a specific event such as "creation of pull request" ; "on a schedule request" etc.

   - Continuous integration triggers (CI triggers) runs a pipeline when you push code to a branch
   - Pull request triggers: run a pipeline when you raise a PR or push code to the source branch of an open PR.
   - Schedule triggers: runs a pipeline on a predefined schedule.
   - Pipeline completion triggers run a pipeline when another pipeline( or another build finishes) completes. 

7. What is Azure Artifacts?

   Azure Artifacts is a package management service in Azure DevOps, which let your team create, host, and share the software packages like npm, Maven, Python from a single, central repository. It also simplifies dependency management and integrates directly with CI/CD pipelines.

8. How to manage secrets in Azure DevOps?

   There are two ways to manage secrets securely in Azure DevOps such as: 1) Azure Key Vault Integration for the native enterprise-grade management and 2) Native Pipeline Secret Variable for quick and localize configuration. Its recommended to not use the secret or any credential as hardcoded into the repository code. 
