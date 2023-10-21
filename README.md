![image](https://github.com/EdwinLamarWalker/configure-VM/assets/147763790/197c73f4-8b76-4b8c-8ccb-e28085f16a7b)

<h1>Azure - Configuring Virtual Machines</h1>
This tutorial outlines the steps and procedures of creating a virtual machine and accessing it through remote desktop as you would in a remote work setting using a real Pc.<br />




<h2>Environments and Technologies Used</h2>

- Microsoft Azure 
- Remote Desktop
- Virtual Machines

<h2>Operating Systems Used </h2>

- Windows 10Pro</b> (22H2)

<h2>List of Prerequisites</h2>

- Create Account/Subscription And Open Azure Homescreen.
- Firstly, Search And Create "Resource Groups"
- Create Your "Virtual Network"
- Search "Remote Desktop" in Windows Search Bar And Connect Using VM's Ip Address (Copy And paste).
- Delete Resources in Azure.

<h2>Installation Steps</h2>


![image](https://github.com/EdwinLamarWalker/configure-VM/assets/147763790/ce35dc2b-9dcf-4939-aa8d-56cb67245b1b)

</p>
<p>
First And foremost, Log Into Azure and Get set up with a subscription if you hadnt already( Free Or pay as you go ). Then when thats complete you should be at the home screen ready to go with our first step toward configuring  vm's In Microsoft Azure.
</p>
<br />

![image](https://github.com/EdwinLamarWalker/configure-VM/assets/147763790/dc64497c-bd11-408d-8bc0-362b1603af21)

</p>
<p>
Next Search " Resource Groups" In search bar up top, Or find the icon with the blue diamond labeled "resource groups." From there you'll need to name it and Pick your Region Closest to you. This is important that you keep your region the same throughout this lab. Then review and create And your ready to go for your next steps.
</p>
<br />

![image](https://github.com/EdwinLamarWalker/configure-VM/assets/147763790/ff42e65f-5e0f-4534-a47e-04d783349f42)
![image](https://github.com/EdwinLamarWalker/configure-VM/assets/147763790/02ee126e-44e4-4a27-83be-872208548bf2)

Now when you go to create your virtual machine it will take you toward the setup process. It is important that you keep the same previous settings (Region and Resource Group.)Then will Name your Vm and change your image ( Operating system) to windows 10 Pro 22H2 As well as Create a username and password (This is important to remember for your remote desktop process in later lab tutorials.)Then click the confirm box and proceed toward the "networking" section.

![image](https://github.com/EdwinLamarWalker/configure-VM/assets/147763790/88d74101-5f64-471f-80a4-6333691c0c27)


</p>
<p>
Once you enter the networking section it should autocreate your virtual machines NIC(Virtual Network Interface), Public and private Ip Addresses as well as your subnet and later on your firewall as well. We can observe that inside the resource group once you "review and create" your VM.
</p>
<br />

![image](https://github.com/EdwinLamarWalker/configure-VM/assets/147763790/1d1156c5-884d-4d81-826a-85f0d9889511)

Once you have created your Virtual Machine you can head toward your resource groups and watch as it installs the components neccesary for a virtual machine, just as a "real" computer would have. From here you can see any and everything that your vm has created.

![image](https://github.com/EdwinLamarWalker/configure-VM/assets/147763790/3724365c-de50-4fbd-b9bc-3d05a596cfbf)

Last But not least, You Search "Remote desktop" In your windows search Bar and copy and paste your VM1's Ip Address Inside; Once you've done that, you will enter in your username and password you created. Thats How you Create a Virtual Machine in Microsoft Azure! Be sure to Delete Your Resource Groups so you wont be charged for any extra components running. Rinse and Repeat for a deeper unnderstanding of Virtual Machines.
