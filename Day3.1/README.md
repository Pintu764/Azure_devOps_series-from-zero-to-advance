# Day 3: Mastering Git and Source Control in Azure DevOps

* Introduction to Source Control and Azure Repos
* Git vs TFVC
* Configure Visual Code
* Cloning the repo
* Commit changes
* Reviewing history
* Working with branches
* Tagging a release
* Managing repository
* Managing Pull requests
* Sample application code

  ### Azure Repos is a set of version control tools within Microsoft Azure DevOps Services (formerly known as Visual Studio Team Services or VSTS) that provides Git repositories or Team Foundation Version Control (TFVC) for source control of your code.

### Here's a breakdown of what Azure Repos offers:

### Git Repositories: Azure Repos provides Git repositories, which are distributed version control systems. Git allows you to work on your codebase offline and then synchronize your changes with a central repository. It supports branching, merging, and other collaborative features.

### TFVC Repositories: Azure Repos also supports Team Foundation Version Control (TFVC), which is a centralized version control system. TFVC offers a more traditional approach to version control, where each user checks out files from a central repository, makes changes, and then checks them back in.

### Code Collaboration: With Azure Repos, teams can collaborate on code development using features like pull requests, code reviews, and branch policies. This facilitates collaboration and helps maintain code quality.

### Integration with Azure DevOps: Azure Repos seamlessly integrates with other services in Azure DevOps, such as Azure Pipelines for continuous integration and continuous deployment (CI/CD), Azure Boards for project management, and Azure Artifacts for package management.

### Security and Compliance: Azure Repos provides robust security features to protect your source code, including access controls, branch policies, and audit logs. It also helps you comply with regulatory requirements by providing features like code signing and access control.

  ### Version control systems are software that help you track changes you make in your code over time. As you edit your code, you tell the version control system to take a snapshot of your files. The version control system saves that snapshot permanently, so you can recall it later if you need it. Use version control to save your work and coordinate code changes across your team.

### Even if you are working on a personal project, version control helps you stay organized as you fix bugs and develop new features. Version control keeps your development history so you can quickly review and even roll back to any code version.

* Helps you track changes in the codebase
* Maintains the history of your codebase, who made the changes, what changes were made, why the changes were made, etc
* Helps you stay organized
* Gives you the ability to rollback the changes as needed



  # Azure DevOps Demo Generator
 ### Use these steps to load dummy data into your Azure DevOps project. We will use this data in the demo.

1. #### [Navigate to https://azuredevopsdemogenerator.azurewebsites.net](https://azuredevopsdemogenerator.azurewebsites.net). This utility site will automate the creation of a new Azure DevOps project within your account that is prepopulated with content (work items, repos, etc.) required for the lab.
2.  ### Sign in using the Microsoft account associated with your Azure DevOps subscription.

 ![Deveops generator](C:\Users\Pintu Kumar Sah\Pictures\Screenshots\deveops_image.png)
       ![Uploading deveops_image.png…](C:\Users\Pintu Kumar Sah\Pictures\Screenshots\deveops_image.png)
        ![Uploading deveops_image.png…]()
        ![Uploading deveops_image.png…](
<img width="557" alt="deveops_image" src="https://github.com/Pintu764/Azure_devOps_series-from-zero-to-advance/assets/159055209/484dc3f1-e195-4be6-9f85-1d4bf8e7451b">)

3. ### Accept the permission requests for accessing your subscription.

4. ### Select the PartsUnlimited template and click Select Template.

![PROJECT CREATION](‪C:\Users\Pintu Kumar Sah\Pictures\Screenshots\DEVEOPS_IMAGE-2.png)

5.### Click Create Project and wait for the process to complete.
![create](C:\Users\Pintu Kumar Sah\Pictures\Screenshots\deveops_image-3.png)
  
