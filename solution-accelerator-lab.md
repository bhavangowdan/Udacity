# Getting Started with Lab

1. Once the environment is provisioned, a virtual machine (JumpVM) and lab guide will get loaded in your browser. Use this virtual machine throughout the workshop to perform the the lab.
1. To get the lab environment details, you can select **Lab Environment** tab. 

  <p align="left">
<img width="1900" height="1900" img src="images/solution2.PNG"/>
</p>
 
 
 
## Login to Azure Portal
1. In the JumpVM, click on Azure portal shortcut of Microsoft Edge browser which is created on desktop.

   ![azure portal.](images/solution2.PNG)
   
1. When you click on Azure portal, edge browser welcome screen will come up, select **Get started**.

   ![](images/17.png "Get started")
   
1. On next window, click on **Confirm**.

   ![](images/18.png "Confirm")
   
1. Now, you can close the popup which is coming up.

   ![](images/19.png "Confirm")
   
1. Now, you will see two tabs in edge browser, close first tab named with **Microsoft Edge**.

   ![](images/20.png "Close Tab")
   
1. On **Sign in to Micsoft Azure** tab you will see login screen, in that enter following email/username and then click on **Next**. 
   * Email/Username: <inject key="AzureAdUserEmail"></inject>
   
     ![](images/21.png "Enter Email")
     
1. Now enter the following password and click on **Sign in**.
   * Password: <inject key="AzureAdUserPassword"></inject>
   
     ![](images/22.png "Enter Password")
     
1. If you see the pop-up **Stay Signed in?**, click No

1. If you see the pop-up **You have free Azure Advisor recommendations!**, close the window to continue the lab.

1. If a **Welcome to Microsoft Azure** popup window appears, click **Maybe Later** to skip the tour.
   
1. Now you will see Azure Portal Dashboard, click on **Resource groups** to see the resource groups.

   ![](images/23.png "Resource groups")
   
1. Confirm you have all resource group are present as shown below.

   ![](images/solution5.png "Resource groups")
   
1. Now, click on the **Resource group** 

## Resource Start/Stop

If your environment is stopped due to inactivity feature, please follow the below steps to start the resources: 

   
In Lab Resources, please select the start all virtual machines button to start the resources
![azure portal.](images/solution4.png)

Identify all container images not hosting a specific technology​.
    <details>
        <summary>Q1-Answer</summary>
            From the All Technologies list on the Inventory > Technologies page, click on a technology, such as NGINX, to open the drawer. In the Area below the review status, click on the <b>Hosting Containers</b> link, which jumps you to the graph and displays all of the containers hosting that technology. Now click once on the **THAT** in the clause THAT Runs Hosted Technology WHERE Technology ID equals NGINX. This action should add a THAT NOT as part of the clause, which is the negated form of the clause and a correct answer. **Tip:** Try clicking on the THAT clause multiple times to see what happens... 
    </details>
