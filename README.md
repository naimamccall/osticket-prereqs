<p 
 align="center"><img width="512" height="512" alt="image" src="https://github.com/user-attachments/assets/ef0bef94-1338-42c3-ad37-1b38df5f6e81" />
</p>

<h1>Virtual Machine Setup and Utilization</h1>
This tutorial outlines the setup and ultilization of Remote Desktop<br />




<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Powershell

<h2>Operating Systems Used </h2>

- Mac OS
- Windows OS

<h2>List of Prerequisites</h2>

- Step 1: Create a virtual machine by entering appropriate configuration.

- Step 2: Locate IP address in newly created Virtual Machine.
  
- Step 3: Open remote desktop and add a new PC.
  
- Step 4: Enter the IP address from the created Virtual Machine.
  
- Step 5: Inside the Virtual Machine ipconfig /all to show ip address of virtual machine instead of personal computer.

  

<h2>Installation Steps</h2>

<p>
<img width="3004" height="1944" alt="image" src="https://github.com/user-attachments/assets/d8d69fde-f327-49d1-aae2-99576e76d53d" />
<p>
 Azure allows users to utilize it's environments in versitile ways. One of them being virtual machine. Creating a virtual machine will require proper configuration to insure the system runs accuratly. Creating a recource group with a unique name within the account being used is the first step. A virtual machine name must be established as well as a region and zone.
</p>
<br />

<p>
<img width="2024" height="964" alt="image" src="https://github.com/user-attachments/assets/2f3fe04f-f8d9-4eb1-9bce-a5ad21011f4a" />
</p>
<p>
Once a unique IP address has been established it is time to copy that IP address so that it can be used for remote desktop.
</p>
<br />

<p>
<img width="1538" height="1070" alt="image" src="https://github.com/user-attachments/assets/72e7c431-def1-4533-8a8e-c553c9d51c1c" />
</p>
<p>
For those who are Windows computer users already, these tasks can be done on Windows Remote Desktop. Mac users can complete these tasks via the Windows App. Once the application is opened, by clicking the + sign in the top right corner, the option to create a new PC will pop up. Clicking on that will prompt information to be entered, allowing the virtual machine to mirrored on the PC being created.
</p>
<br />


<p>
<img width="868" height="668" alt="image" src="https://github.com/user-attachments/assets/ef5bff4f-8bd9-4e99-b0fe-bde50f3ad1d6" />
</p> 
<p>
<img width="984" height="692" alt="image" src="https://github.com/user-attachments/assets/48be315d-3cad-4a2c-a81b-5961f5fe4fa2" />
</p>  
<p> 
The PC name will be the IP address of the computer that is going to be mirrored. A Friendly Name will need to be entered as well in order to easily detect which pc is which withing the Windows App. Once that is established a username and password is required in order to gain full access to the computer that will be remoted into.
</p>
<br />

<p>  
<img width="3024" height="1964" alt="image" src="https://github.com/user-attachments/assets/6e9fa65c-cd83-4287-99e5-ed9fcb983ce0" />
</p>
<p>
After the proper login information is entered access into the computer will be granted. As a Mac user I now have Windows OS features at my disposal without having to switch physical PCs.
</p>
<br />

<p>  
<img width="3024" height="1964" alt="image" src="https://github.com/user-attachments/assets/83ba0fff-3ce5-48eb-98c7-3b5aa7f1bf3e" />
</p>
<p>  
<img width="3024" height="1964" alt="image" src="https://github.com/user-attachments/assets/1aec517c-65a5-437c-bf16-26cf16a3e0df" />
</p>
<p> 
Once remoted into this virtual machine powershell can be accessed. If ipconfig /all is typed in it can be noticed that the information of the computer that is being mirrored shows up instead of the information of the physical PC the user is on.
</p>
<br />

