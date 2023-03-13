# DevOps-Project
First Devops Project

# Softwares Required:
- Git
- Java v17
- Jenkins v9
- Tomcat Server
- Apache Ant

# Plugins installed in Jenkins
- Github
- Ant
- warning next generation
- Junit
- Deploy to container
- Build pipeline plugin

# Jobs created in Jenkins dashboard
- GithubPull
- Build and Code review
- Unit Test 
- Deploy

# Steps Invovled
Step-1: clone a sample web application
	  https://github.com/bhupinderjnu/SampleWebApp.git

Step-2: Create a job in jenkins as githubpull
        Install github plugin on jenkins
 
Step-3 Create another job as build and code review
       Install 2 plugins Ant & warning next generation plughin

Step-4: Create a job for continious testing as Unit test
        Install Junit plugin and configure

Step-5: Create a job for Deployement as Deploy
        Install Deploy to container Plugin to deploy on Tomcat Container

Step-6: Crete a job for CI/CD pipeline
        Install Build pipeline plugin and then configure in each job in post build section so that the action is done contnious
