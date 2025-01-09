# Remote Desktop (VMs)
<p align="center">

![step 1](https://github.com/user-attachments/assets/47b50c9a-08f7-4252-92d8-0a7b2bdb8a6f)

<h1>Azure VMs - How to create and use a Azure Virtual Machine</h1>
This tutorial is based on how to create and connect to a Azure Virtual Machine.<br />

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines)
- Remote Desktop

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>STEPS INCLUDED</h2>

- STEP 1 - Create A VM using astra
- STEP 2 - Locate The Public IP Address In The Azure VM
- STEP 3 - Open Remote Desktop Connection
- STEP 4 - Copy And Paste The Required Information Into Remote Desktop (Public IP Address, Usernames, and Passwords) 
- STEP 5 - Press Connect and you will be connected to the virtual machine

<h2>Installation Steps</h2>

STEP 1 - Locate your own personal IP address by going to "www.whatismyipaddress.com" which will be able to show you your local IP address. We will use this later as well. See EXAMPLE 1A below.

EXAMPLE 1A
<p>
<img src="https://i.imgur.com/qDgu5K6.png)" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>

Next we will set up a virtual machine on Azure. 
  
</p>
<br />

STEP 2 - Go to www.portal.azure.com and find Virtual Machines. (Create a free account with $200 if you need to). See Example 2A looking at the Virtual Machine set up page. 

EXAMPLE 2A
<p>
<img src="https://i.imgur.com/K9oaS2z.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>

Creating the Virtual Machine on Example 2B the VM as “VM-FranceCentral” and select that for the REGION as well. Ensure the other items are selected as shown in EXAMPLE 2B & 2C.

EXAMPLE 2B
<p>
<img src="https://i.imgur.com/u3vclL3.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>

For the Username and Password you can create your custom information, just record it personally.
  
</p>
<br />

EXAMPLE 2C
<p>
<img src="https://i.imgur.com/rXIj3Zb.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>

Select the “Networking” tab towards the top of the page and view EXAMPLE 2D inputs to match. 
  
</p>
<br />

EXAMPLE 2D
<p>
<img src="https://i.imgur.com/OgYgNLK.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>

Then select “Review and Create”, once it passes validation select “Create” at the bottom. 
  
</p>
<br />

NEXT: At the Virtual Machine we find that the IP to the Virtual Machine is “20.216.176.18”. See EXAMPLE 2E

EXAMPLE 2E

<p>
<img src="https://i.imgur.com/ZlH9zI5.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>


STEP 3 – Log Into the VM and Find IP Address
<p>
Now that we have set up the Virtual Machine we will connecting to it using the application “Remote Desktop Connection” (EXAMPLE 3A) and input the IP address for the VM that we located in EXAMPLE 2E and then input the set credentials we set when creating the VM (see EXAMPLE 3B). Once logged in, we will open the web browser and again look up www.whatismyipaddress.com (EXAMPLE 3C).

  
</p>
<br />
EXAMPLE 3A
<p>
<img src="https://i.imgur.com/YPBkMau.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>

  
</p>
<br />

EXAMPLE 3B
<p>
<img src="https://i.imgur.com/oPJr2w2.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>

When we look up the IP address for this VM through www.whatismyipaddress.com we see that this VM is showing the location for France (EXAMPLE 3C).
  
</p>
<br />



  
</p>
<br />
If you no longer need the VM, ensure to remove it from the Asure account for unwanted charges.

END OF TUTORIAL





