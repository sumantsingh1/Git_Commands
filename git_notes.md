# Source Code Management Tool
## A source code management tool is essential for managing application code.
* Version Control: Tracks and records all changes, enabling rollbacks to previous versions when needed.
* Collaboration: Allows multiple developers to work together simultaneously using features like branching and merging.
* Code Review: Facilitates peer review for code changes before merging into the main branch.
* Backup and Recovery: Acts as a central repository to store all versions, ensuring easy recovery after failures.
* Continuous Integration (CI): Integrates with CI/CD pipelines to automate testing, builds, and deployments.
* Debugging: Helps trace and fix issues by comparing different versions of the code.

## Which SCM should we use?
1. Git is a proven and popular SCM tool to use.
2. Git is opensource
3. Companies are providing GIT as a service
* GitHub (Microsoft)
* GitLab
* Bitbucket
* AWS CodeCommit
* Azure Repos

## Available source code management tools are
* Git
* SVN
* IBM Cearcase
* Mercurial

## Git Architecture
![image alt](https://github.com/sumantsingh1/Git_Commands/blob/f0b4495fe00cd0fcfde49d2810452e724a5696cf/Images/git_architecture.PNG)

## Setting Up a Central repository
### Central repositories could be set up in two ways,
* Hosted (Means installing Gitserver in our servers)
* Using one of the providers
  * GitHub
  * Gitlab
  * BitBucket
  * CodeCommit AWS
## Create Account in Github (Git Server Setup)
 * Go to [github.com](https://github.com)
 * Click on Sign Up
 * Provide email ID
 * Set password
 * Go to your inbox and click the link and activate the account
## Create Git remote repository for practice
 * Goto Github.com and → Click on “+” icon in the top right and create repository.

## Install git client on your laptops
 * We can either install CLI(Command Line Interface) or GUI (Graphical User Interface)
 * We are going to use CLI throught Git course
   * Install gitbash
      * [git-scm.com](https://www.git-scm.com/downloads)
## Configure GitBash (One time activity)
  * Open Git Bash
       * Open from start menu by searching gitbash
       * Another way is Right click → More Options → Open Gitbash here
  * Configure Email & User Name
    * This information is recorded when you commit
    * Inside gitbash run following commands
        * git config --global user.name "Sumant Singh"
        * git config --global user.email "sumant.singh@gmail.com"
     
## Install Visual Studio Code (Most DevOps & Cloud engineers use this)
   ### Follow instructions from this
   * [Download Link](https://code.visualstudio.com/download)








