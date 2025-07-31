# Azure DevOps
https://platform.qa.com/learning-paths/az-400-exam-prep-microsoft-azure-devops-solutions-1-1368/

### Introduction

Azure DevOps is a suite of services that allow for collaboration on software development, following DevOps principles. 
The main services Azure DevOps includes are:

1. **Azure Repos** for hosting Git repositories for source control of your code
2. **Azure Boards** for planning and tracking your work using proven agile productivity tools
3. **Azure Pipelines** for continuous integration and delivery of your software
4. **Azure Test Plans** for testing your software
5. **Azure Artifacts** for publishing software packages

![1. Services.png](1.%20Services.png)

Projects in Azure DevOps is the medium through which you can access these services. It serves as the container to host 
source code and a place for users to manage and build software solutions.

There are different plans available for using Azure DevOps. There are generous free limits that allow you to get your 
hands dirty and try out a lot of what Azure DevOps has to offer if you were to make your own organization. You can pick 
and choose the pieces you want to use and integrate them with external tools that you may already be using. Azure DevOps
was built to support that level of customization and you will see several places where you have options to integrate 
with tools outside of Azure DevOps. In this lab, you will not need to worry about any limitations.


### Service breakdown

**Azure Repos** are Git-based repositories in the Azure DevOps tool suite. You can have an unlimited number of private 
Git repos for free. On top of the Git repository is an array of features to integrate repos with workflows, making it 
easier to manage your code and related processes. Some of the features include pull request based workflows, branch 
policies to enforce high quality of merged code, and semantic-aware code search. As a Git-based repo, you can use all of
your favorite tools that support Git with repositories in Azure Repos.

![2. Repos.png](2.%20Repos.png)

**Azure Boards** provide tools for planning, tracking, and collaborating using agile tools. Boards support several 
processes including Scrum and Agile. Each process can plan and prioritize work in backlogs, keep a limit on work in 
progress on kanban boards, organize and track work in sprints, and use analytics to optimize your agile processes. 
In Azure Boards, you use work items for everything you need to track. Work items represent different types of work such 
as epics, issues, or tasks. Work items can also have relationships with other work items, such as parent-child. There 
are a variety of views for work items. Each provides you with an optimized view of the different tasks at hand.

![3. Boards.png](3.%20Boards.png)

**Azure Pipelines** is the Azure DevOps service for continuous integration and continuous deployment. At a high level, 
there are two distinct types of pipelines in Azure Pipelines, which can be confusing if not made aware of early on. 
There are build pipelines, sometimes referred to simply as pipelines in the UI, and release pipelines. The build 
pipelines are focused on the continuous integration of source code while release pipelines are focused on continuous 
deployment. Although build pipelines can also deploy code, they should only be used to deploy to development or test 
environments. Your production deployments are better performed using release pipelines.

Build pipelines connect to a code repository and perform a build to produce build artifacts. They are a generic tool 
that can integrate with any Git-based repository and can satisfy any of your build requirements. The build is described 
in a YAML file that is included in the repo.

![4. Pipelines.png](4.%20Pipelines.png)

**Azure Test Plans** is a service used to plan manual testing of your code to help improve the overall code quality. 
You are also able to do user acceptance testing (UAT) to verify the value delivered to the customer. Test Plans service 
is not included with the basic plan of Azure DevOps (although you can get 30 days free).  
[To learn more about Test Plans check out the product page](https://azure.microsoft.com/en-ca/services/devops/test-plans/)

![5. Test Plans.png](5.%20Test%20Plans.png)

**Azure Artifacts** give devs the opportunity to use packages from various public directories. You can even publish and 
share different types of packages. There are various supported packages such as:
- NuGet
- Npm
- Maven
- Python
- Universal Packages

![6. Artifacts.png](6.%20Artifacts.png)

### Summary

In this lab step, you learned about the various services that Azure DevOps provides in its suite to help users 
collaborate on software development, following DevOps principles.



