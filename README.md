# Guide to Creating a Spring Boot Application on Azure

Hello! I'm Anant, your Teaching Assistant for CMPT 276. In this tutorial, I will guide you through the process of deploying a Spring Boot application on Microsoft Azure.
To ensure simplicity and ease, I will provide step-by-step screenshots of the application deployment. Please follow each step carefully, and in no time, your app will be up and running.
So, get ready and enjoy the journey!

[![forthebadge](http://forthebadge.com/images/badges/built-with-love.svg)](http://forthebadge.com)

## Account Setup

Start by setting up an Azure account, which involves a simple process. Initially, you'll need to provide your credentials and later, it will prompt you to enter your credit card details. Rest assured, as you'll be signing up for a free account. Once you complete this process, you'll be ready to proceed further.

### Great!

## Setup "Resource Group"

Before deploying the application, the first step is to create a "Resource Group."

On the homepage, locate the search bar at the top and enter "Resource Group." From the search results, select the "Resource Group" option.

<img width="1200" alt="Screen Shot 2023-05-20 at 3 08 08 PM" src="https://github.com/anant00729/spring-app-for-cmpt-276/assets/20675885/5c70d9ea-a3ad-4f74-94e9-aaee88fa8aff"><br>

Currently, there are no existing "Resource Groups" visible. To proceed, click on the "Create resource group" option.

<img width="1200" alt="Screen Shot 2023-05-20 at 3 08 43 PM" src="https://github.com/anant00729/spring-app-for-cmpt-276/assets/20675885/089ab748-f6c2-4aca-909f-89a3facce1fb"><br>

As depicted in the image above, please provide a name for the resource group and select a region. Now click on "Review + Create"

<img width="1200" alt="Screen Shot 2023-05-20 at 3 08 55 PM" src="https://github.com/anant00729/spring-app-for-cmpt-276/assets/20675885/feab402d-e9b5-4247-8a10-19cd91425299"><br>

After successfully creating the resource group, a confirmation page will be displayed. On this page click on "Create".

<img width="1200" alt="Screen Shot 2023-05-20 at 3 09 13 PM" src="https://github.com/anant00729/spring-app-for-cmpt-276/assets/20675885/276a82b1-9978-4a38-90d6-a02960867bf9"><br>

## Creating "App Services"

Once completed, you will see your resource group name listed in the table. 

Now, return to the homepage and use the search bar to search for "App Services"

<img width="1200" alt="Screen Shot 2023-05-20 at 3 09 24 PM" src="https://github.com/anant00729/spring-app-for-cmpt-276/assets/20675885/a854cecc-fb5a-41a5-8978-be9e545f4cc6"><br>

On the App Services listing page, click on the "Create" button.

<img width="1200" alt="Screen Shot 2023-05-20 at 3 09 36 PM" src="https://github.com/anant00729/spring-app-for-cmpt-276/assets/20675885/baa0968e-527d-4b38-b149-6bc30fb08d5b"><br>

On this page, you need to provide a name for your application. Choose the publishing option as "Code" and select the appropriate Java runtime stack that matches the version of your Spring Boot application.

<img width="1200" alt="Screen Shot 2023-05-20 at 3 10 14 PM" src="https://github.com/anant00729/spring-app-for-cmpt-276/assets/20675885/c305e356-ce43-47bb-96cf-ea2d338d7f91"><br>

Leave the default options unchanged; there is no need to make any modifications to the default values that have been preselected.

And click on "Review + Create". On the next page click on "Create". 

<img width="1200" alt="Screen Shot 2023-05-20 at 3 10 26 PM" src="https://github.com/anant00729/spring-app-for-cmpt-276/assets/20675885/023994c3-6328-4411-8c9c-0fec19725c94"><br>

<img width="1200" alt="Screen Shot 2023-05-20 at 3 10 37 PM" src="https://github.com/anant00729/spring-app-for-cmpt-276/assets/20675885/cd5d114b-b29e-4cd1-998f-c3bfb890f643"><br>

After few secounds you will see a confirmation page 

<img width="1200" alt="Screen Shot 2023-05-20 at 3 11 38 PM" src="https://github.com/anant00729/spring-app-for-cmpt-276/assets/20675885/975b03e1-bbc0-4466-b3cf-f41b9dd04fce"><br>

## Creating Github Repository for the Spring Boot Application

Now, let's create a repository on your GitHub account.

First, create a new repository on GitHub.

Second, navigate to the root directory of your project. Open the terminal and execute the following command:


```
git init
git add .
git commit -m "<your-commit-message>"

git remove add origin <your-root-github-repository-url>

git push origin master
```

## Connecting Github Reposotory with App Service

Now, connect/link your GitHub account and repository to the "App Service" you have created on Azure, as illustrated below.


<img width="1200" alt="Screen Shot 2023-05-20 at 3 15 04 PM" src="https://github.com/anant00729/spring-app-for-cmpt-276/assets/20675885/3284625c-1018-4658-89d5-a112813feadb"><br>


Click on the "Save" button at the top left. Now click on the "Deployment Center" on the sidebar as shown below.


<img width="1200" alt="Screen Shot 2023-05-20 at 3 16 39 PM" src="https://github.com/anant00729/spring-app-for-cmpt-276/assets/20675885/7351fd61-b7a9-43fb-af57-b04e931b38e6"><br>


### Phew! We're almost there.

After finishing the previous step, click on the link located in the "Log" column. It will open a new tab with this page.

<img width="1200" alt="Screen Shot 2023-05-20 at 3 16 53 PM" src="https://github.com/anant00729/spring-app-for-cmpt-276/assets/20675885/3376ba48-417f-4576-bafd-9487b40a9ab6"><br>


Take a short break while your application is being deployed. It may take a few minutes to complete the process.

Once you notice that the deployment box turns green, it means your application is live and ready to be accessed! You're all set to get started.


<img width="1200" alt="Screen Shot 2023-05-20 at 3 21 24 PM" src="https://github.com/anant00729/spring-app-for-cmpt-276/assets/20675885/44cb3b52-0278-4966-b638-38b1308cfc3b"><br>

Click on the link provided in the deployment box to access your application, which should now be up and running at that URL. 

<img width="1438" alt="Screen Shot 2023-05-20 at 3 21 16 PM" src="https://github.com/anant00729/spring-app-for-cmpt-276/assets/20675885/7ab0ae9f-b407-473e-8b63-e453ff83f13c"><br>

### Well done!

You have successfully completed the deployment process! If you encounter any difficulties during any of the above steps, feel free to reach out to me on Discord (my discord id is anant_2909#3285). Additionally, if you find this tutorial helpful, don't forget to give a shout-out in our Discord #general channel. Your feedback is greatly appreciated!






