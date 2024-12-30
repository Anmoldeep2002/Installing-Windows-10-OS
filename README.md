<h1>Installing Windows 10</h1>


<h2>Description</h2>
<p>In this section, I'll set up a new Virtual Machine for the Helpdesk employee. I will also establish another Virtual Machine for a client within the organisation. In this section, I will demonstrate my ability to install Windows 10 within both virtual machines.</p>


<br />

<h2>Step-by-Step Walk-Through:</h2>


<p align="center"> 
STEP 1: <br/>
<img src="https://i.imgur.com/YQlwKCX.png" height="70%" width="70%"/> </p>


<p align="center">I want to create a new Virtual Machine using the software "VirtualBox". I want to use this VM as a helpdesk account under the domain "OFFICE123". The operating system for this virtual machine will be Windows 10.</p>

<hr width="100%" size="2">

<br />

<p align="center"> 
STEP 2: <br/>
<img src="https://i.imgur.com/VuVYsUs.png" height="70%" width="70%"/> </p>


<p align="center">In this stage, I enter information about the virtual machine that I want to create and configure it with the necessary requirements. As you can see, I've filled out all of the needed information for this virtual machine. I've entered the name "Windows 10" and chosen the version "Windows 10 (64-bit)". After this, I clicked on the "Next" button. As you can see, I have not chosen an ISO image to run the Windows Operating System; I will do so once I launch the Virtual Machine.</p>

<hr width="100%" size="2">

<br />

<p align="center"> 
STEP 3: <br/>
<img src="https://i.imgur.com/2r1nv6O.png" height="70%" width="70%"/> </p>


<p align="center">In this phase, I allocated RAM memory and CPU for the virtual machine, as well as the amount of hard disk storage it will receive. I've allocated 2GB of RAM, which is the minimum required to run a Virtual Machine, and 1 CPU core, which will allow the Virtual Machine to do tasks efficiently. I then proceeded to allocate the actual storage for the Virtual Machine; I allocated 25 GB of storage, which is more than plenty for this project. After this, I hit the "Finish" button to add the Virtual Machine.</p>

<br />
<br />

<p align="center"> 
<img src="https://i.imgur.com/nYrXX2u.png" height="70%" width="70%"/> </p>


<p align="center">This section appeared automatically after signing into the Virtual Machine. As you can see, this is the "Server Manager" section, which is crucial because it will allow me to install "Active Directory", create a domain, and carry out a variety of other things required for this lab-based project.</p>


<hr width="100%" size="2">

<br />

<p align="center"> 
STEP 4: <br/>
<img src="https://i.imgur.com/ffTw5kJ.png" height="70%" width="70%"/> </p>


<p align="center">In this stage, I click the "START" button, which allows me to start the virtual machine. As you can see, I was greeted with an error message stating that there is no "Operating System" to boot the virtual machine. To overcome this particular issue, I must boot the Virtual Machine's with an actual ISO. To pick the ISO, I clicked the small arrow icon on the right side, followed by the small "Folder" icon at the bottom. After choosing the "Folder" icon, I'll be able to choose an ISO.</p>

<hr width="100%" size="2">

<br />

<p align="center"> 
STEP 5: <br/>
<img src="https://i.imgur.com/GRMn16p.png" height="80%" width="80%" alt="Disk Sanitization Steps"/> </p>


<p align="center">As you can see, I've successfully added a virtual machine into the lab-based project. The next thing to do will be to launch the Virtual Machine and load an ISO so that it can execute an operating system.</p>

<br />


<p align="center"> 
<img src="https://i.imgur.com/bpliGZ1.png" height="50%" width="50%" alt="Disk Sanitization Steps"/> </p>


<p align="center">I click the "START" button, which allows me to start the virtual machine. As you can see, I was greeted with an error message indicating that there is no "Operating System" to boot the virtual machine.</p>

<hr width="100%" size="2">

<br />

<p align="center"> 
STEP 6: <br/>
<img src="https://i.imgur.com/StLqrW0.png" height="50%" width="50%" alt="Disk Sanitization Steps"/> </p>


<p align="center">To overcome the previously mentioned issue, I must select an ISO to boot the system of the Virtual Machine. To select the ISO, I clicked the small arrow icon on the right side, followed by the small "Folder" icon at the bottom. After choosing the "Folder" icon, I'll be able to choose an ISO.</p>

<br />

<p align="center"> 
<img src="https://i.imgur.com/P3owG3c.png" height="80%" width="80%" alt="Disk Sanitization Steps"/> </p>

<p align="center">I got directed to my actual ISO file, and I selected it. I obtained the ISO file for free from Google and saved it in my "Downloads" folder. This ISO contains the operating system that will enable the Virtual Machine to run Windows Server 2016.</p>

<hr width="100%" size="2">

<br />

<p align="center"> 
STEP 7: <br/>
<img src="https://i.imgur.com/y3AXOJM.png" height="50%" width="50%" alt="Disk Sanitization Steps"/> </p>


<p align="center">As you can see, the ISO file has been selected and is ready to be mounted on the Virtual Machine. In this stage, I'll click the "Mount and Retry Boot" option, which will enable the Virtual Machine to boot with the new Operating System.</p>

<br />

<p align="center"> 
<img src="https://i.imgur.com/mXA8jNJ.png" height="70%" width="70%" alt="Disk Sanitization Steps"/> </p>


<p align="center">The new operating system has been successfully loaded on the virtual machine. As you can see, the Virtual Machine is booting up the Windows operating system.</p>

<hr width="100%" size="2">


<br />

<p align="center"> 
STEP 8: <br/>
<img src="https://i.imgur.com/BZ1ZMPT.png" height="70%" width="70%"/> </p>


<p align="center">The Virtual Machine has been successfully loaded with the Windows operating system. As you can see, I'm on the initial setup page, where I can configure the VM based on my requirements. In this instance, I click the "NEXT" button to proceed to the next step.</p>

<br />
<br />

<p align="center"> 
<img src="https://i.imgur.com/yV20weV.png" height="70%" width="70%"/> </p>


<p align="center">It's asking me which version of Windows to select. In this instance, I selected the second option. The reason for this is that the second option contains a GUI interface, which makes it easier for me to navigate the OS. I did not select the first choice because it lacks a GUI and will make it more difficult for me to manage the Virtual Machine. After selecting the version to install, I clicked "NEXT" to move on to the next stage.</p>

<br />
<br />

<p align="center"> 
<img src="https://i.imgur.com/Dyf6B6N.png" height="70%" width="70%"/> </p>


<p align="center">It's asking me to choose the type of installation to execute. There are just two options: "upgrade" or "custom install" the OS. In this case, I opt for the second option because I am interested in installing the OS rather than upgrade it.</p>

<br />
<br />

<p align="center"> 
<img src="https://i.imgur.com/mVOUcnw.png" height="70%" width="70%"/> </p>


<p align="center">In this phase, it asks where I would like to install Windows. As you can see, I just have one hard drive, "DRIVE 0", and it has 32GB of free space. In this instance, I click "DRIVE 0" and move on to the next stage.</p>


<br />
<br />

<p align="center"> 
<img src="https://i.imgur.com/GbG21Vk.png" height="70%" width="70%"/> </p>


<p align="center">Finally, the Operating System (OS) is being installed, as shown in the image above. The installation procedure will progress through several stages, and once completed, I will be given the choice to move to the next step.</p>


<br />
<br />

<p align="center"> 
<img src="https://i.imgur.com/E1IAkvI.png" height="70%" width="70%"/> </p>


<p align="center">The installation is complete, and it is now requiring me to set up a password for the local "Administrator" account, which will be used to access the Server VM I've typed the password and set it to "Office123". I then hit "Finish" to conclude the OS installation process for this VM.</p>

<br />
<br />

<p align="center"> 
<img src="https://i.imgur.com/W7V6nPb.png" height="70%" width="70%"/> </p>


<p align="center">The installation is complete, and it is now requiring me to set up a password for the local "Administrator" account, which will be used to access the Server VM I've typed the password and set it to "Office123". I then hit "Finish" to conclude the OS installation process for this VM.</p>


<br />
<br />

<p align="center"> 
<img src="https://i.imgur.com/n5P8cEl.png" height="70%" width="70%"/> </p>


<p align="center">This section appeared automatically after signing into the Virtual Machine. As you can see, this is the "Server Manager" section, which is crucial because it will allow me to install "Active Directory", create a domain, and carry out a variety of other things required for this lab-based project.</p>






