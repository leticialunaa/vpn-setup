

<h1>(NSGs) VPN setup and usage </h1>
In this tutorial, we will setup VPN and usage using Proton VPN.. <br />





<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Various Command-Line Tools
- Various Network Protocols (SSH, RDH, DNS, HTTP/S, ICMP)
- Proton (VPN)

<h2>Operating Systems Used </h2>

- Windows 10 (21H2)
- Ubuntu Server 20.04
- https://whatismyipaddress.com/
- http://accountprotonvpn.com/signup?plan=free&language=en
- www.portal.azure.com

<h2>High-Level Steps</h2>

- Step 1: Browse https://whatismyipaddress.com/
- Step 2: Create a resource group through Azure
- Step 3: Login to the VM Remote Desktop
- Step 4: Sign up for http://accountprotonvpn.com/signup?plan=free&language=en
- Step 5: Browse What is my ip and view differences
- Step 6: Erase lab and all Resource Groups

<h2>Actions and Observations</h2>


![image](https://github.com/leticialunaa/vpn-setup/assets/146797387/738efc20-02a9-4cbb-98bd-66fc88e9080b)



Browse to http://whatismyipaddress.com/ keep note as a reminder

Second create a Resource Group in Azure: www.portal.azure.com


![image](https://github.com/leticialunaa/vpn-setup/assets/146797387/9b8580aa-f2b0-49ce-b984-b2dd6366da54)


Create a Windows 10 Virtual Machine in another geographic location (try a different country)

Log into the VM with Remote Desktop

Browse to https://whatismyipaddress.com/ take note as a reminder

![unnamed (2)](https://github.com/leticialunaa/vpn-setup/assets/146797387/81703198-54a7-4e2d-82f4-51eb28ebb778)


Create an account ProtonVPN from your computer and test the VPN connection
The website is the following: https://account.protonvpn.com/signup?plan=free&language=en


![unnamed (3)](https://github.com/leticialunaa/vpn-setup/assets/146797387/fa0eb083-6423-4f5d-bf46-7bd2f6984945)


Within your VM, download the Proton VPN client


![unnamed (6)](https://github.com/leticialunaa/vpn-setup/assets/146797387/ced2a220-6b2d-4fa2-87ed-4e8451f5f674)


Login to the VPN and choose a VPN server in another country (such as Japan)


![unnamed](https://github.com/leticialunaa/vpn-setup/assets/146797387/61bc352c-9c22-4844-92ea-ba61335b5d45)


Browse to the following website: https://whatismyipaddress.com/ and take a note as a reminder.

Browse to Google, Disney and other websites and see if there is anything different about the sites in relation to the location of your VPN server. 

Last step delete the resouce group and verify that resouces/ Resouce groups have been deleted. 

Lab complete. 




