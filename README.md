<h1 align="center"> Creating Virtual Machines in Azure 


<p align="center">
<img src="https://i.imgur.com/1YZUp65.png" height="80%" width="80%"/>
</p>

 <h1>Introduction</h1>
In this step-by-step guide, we will be using Microsfot Azure to create and deploy a virtual machine. 

<h2>Step-By-Step Guide</h2>

<h3>Step 1: Creating a resource group</h3>

You will first log into your Microsoft Azure account and type in "Resource Groups" in the search bar. Next, click on the blue box named "Create resource group."
 <p align="center">
 <img src="https://i.imgur.com/TH8sbTs.png">
 <img src="https://i.imgur.com/JdYSnU8.png">
 
Name your resource group, choose a region, and then click on "Review + create." In the following example, the name of the resource group is "VM1" and the region is "West US 3." 
Once your validation is completed, click "Create" at the bottom.

<p align="center">
  <img src="https://i.imgur.com/UikYyK4.png">
</p>

<p align="center">
  <img src="https://i.imgur.com/6oNkl1O.png">
</p>

<h3>Step 2: Creating a virtual machine</h3>

Type and click on "Virtual machines" in the search box. Click on the blue box named "Create" and select "Azure virtual machine."

<p align="center">
  <img src="https://i.imgur.com/GWynCbF.png">
</p>
  <img src="https://i.imgur.com/JjpOdYa.png">

Next to the "Resource group", select the name of the resource group that you just made and then type in a name for your virtual machine. Make sure to choose the same region that selected for your resource group. Next to "Image" select the operating system that you believe would serve you best in your virtual machine. 

 <p align="center">
  <img src="https://i.imgur.com/3KteC88.png">

Next you will create a username and password in order to access the VM. Save your username and password as you will need it to access your virtual machine. 

Check the box that states "I confirm I have an eligible Windows 10/11 license with multi-tenant hosting rights" and then click "Review + create." 

 <p align="center">
  <img src="https://i.imgur.com/9DLKMhI.png">


<h3>Step 3: Logging into your virtual machine</h3>

Type and click on "Virtual machines" in the search bar and the virtual machine that we created will appear. Click on it and you will details regarding the virtual machine that you just created. We will need the VM's public IP address, which will allow us to access it. You can copy the IP address by clicking on the "Copy to clipboard" icon next to it.

 <p align="center">
  <img src="https://i.imgur.com/lK4J2wx.png">

Next you will go to your Windows search bar, type and select "Remote Desktop Connection." Paste the VM's public IP address and click connect.

<p align="center">
  <img src="https://i.imgur.com/uSWCo9k.png">

You will next be asked for your username and password that you created for your virtual machine. Type in the username and password that you created and click on OK. You will see another window stating that "The identity of the remote computer cannot be verified. Do you want to connect anyway?" select Yes.
 
<p align="center">
  <img src="https://i.imgur.com/Wt9YTXc.png">
 
 <p align="center">
  <img src="https://i.imgur.com/dqQh2Gg.png">


As the virtual machine begins to start, you will see a screen related to privacy settings for your device. Select no for each option and hit "Accept." Your virtual machine is now ready to be used.

<p align="center">
  <img src="https://i.imgur.com/grG4HKs.png">
 
<h3>Step 4: Deleting Your Resource Group</h3>
  
Once you are done using your virtual machine, you will need to delete the resource group so you are not being charged when you are not using it. In order to do this, type "Resource groups", click on the Resource group that you would like to delete, select "Delete resource group", copy and paste the name of the resource group below and then hit "Delete."

<p align="center">
  <img src="https://i.imgur.com/WzE2BHF.png">
