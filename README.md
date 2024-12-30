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


<br />
<br />

<p align="center">
<img src="https://i.imgur.com/GSaan0n.png" height="70%" width="70%"/> </p>


<p align="center">Here I was led to my actual ISO file, and I picked it. I obtained the ISO file for free from Google and saved it in my "Downloads" folder. This ISO contains the Operating System, which will enable the Virtual Machine to run Windows 10.</p>

<br />
<br />


<p align="center"> 
<img src="https://i.imgur.com/fEEASpY.png" height="50%" width="50%"/> </p>


<p align="center">As you can see, the ISO file has been selected and is ready to be mounted on the Virtual Machine. In this stage, I'll click the "Mount and Retry Boot" option, which will allow the Virtual Machine to boot with the new Operating System.</p>

<br />
<br />


<p align="center"> 
<img src="https://i.imgur.com/7KnIUFw.png" height="70%" width="70%"/> </p>


<p align="center">The new operating system has been successfully installed on the virtual machine. As you can see, the Virtual Machine is booting up the Windows 10 operating system.</p>

<hr width="100%" size="2">

<br />

<p align="center"> 
STEP 5: <br/>
<img src="https://i.imgur.com/kQpQdgJ.png" height="70%" width="70%"/> </p>


<p align="center">The Virtual Machine has been successfully loaded with Windows 10. As you can see, I'm on the basic installation page, where I can configure the VM based on my requirements. In this situation, I clicked the "NEXT" button to go to the next stage.</p>

<br />
<br />

<p align="center"> 
<img src="https://i.imgur.com/QF3zKRi.png" height="70%" width="70%"/> </p>

<p align="center">In this phase, Windows prompts me for a product key before installing Windows 10. I do not have a product key for lab reasons, therefore I click "I DON'T HAVE A PRODUCT KEY".</p>

<br />
<br />

<p align="center"> 
<img src="https://i.imgur.com/HlKmtpr.png" height="70%" width="70%"/> </p>

<p align="center">Here, it asks me the version of Windows 10 I want to install. In this instance, I chose "Windows 10 Pro" because it is the most suited version for the lab's needs. This version of Windows 10 allows the virtual machine to be added to a domain, but the others do not.</p>

<br />
<br />

<p align="center"> 
<img src="https://i.imgur.com/k7MdNDf.png" height="70%" width="70%"/> </p>

<p align="center">Here it's asking me to choose the type of installation to execute. There are just two options: "upgrade" or "custom install" the OS. In this case, I opt for the second option because I want to install the OS rather than upgrade it.</p>

<br />
<br />

<p align="center"> 
<img src="https://i.imgur.com/aHPxirs.png" height="70%" width="70%"/> </p>

<p align="center">In this phase, it asks where I want to install Windows 10. As you can see, I only have one hard drive, "DRIVE 0", and it has 25GB of empty space. In this instance, I click "DRIVE 0" and move on to the next stage.</p>

<br />
<br />

<p align="center"> 
<img src="https://i.imgur.com/qPfM3Mu.png" height="70%" width="70%"/> </p>

<p align="center">Finally, the Windows 10 operating system is being installed on the virtual machine, as shown in the image above. The installation procedure will progress through several stages, and once completed, I will be given the choice to move to the next step.</p>

<br />
<br />

<p align="center"> 
<img src="https://i.imgur.com/MD81AAD.png" height="70%" width="70%"/> </p>

<p align="center">As you can see, Windows 10 has been installed, and it is now time to configure the operating system's basic settings. In this situation, it's asking about the region and keyboard layout. I leave everything at its default settings and move on to the next phase.</p>

<br />
<br />

<p align="center"> 
<img src="https://i.imgur.com/Oj1oiay.png" height="70%" width="70%"/> </p>

<p align="center">Here, I select "SET UP FOR PERSONAL USE" because this is a lab-based project and not intended for a real organisation environment.</p>


<br />
<br />

<p align="center"> 
<img src="https://i.imgur.com/TvfaAm6.png" height="70%" width="70%"/> </p>

<p align="center">Here I've created a temporary local user account since I'll later enable the "Administrator" account to grant extra privileges to this device. I added the user name as "User" and continued without adding a password. I'll add the password later as I work on this project. </p>

<br />
<br />

<p align="center"> 
<img src="https://i.imgur.com/My8lV6C.png" height="70%" width="70%"/> </p>

<p align="center">It is now finalising all of the configurations I have set. This will take a few minutes, but once completed, Windows 10 will be successfully installed on the virtual machine.</p>

<br />
<br />

<p align="center"> 
<img src="https://i.imgur.com/lyUFEwc.png" height="70%" width="70%"/> </p>

<p align="center">As you can see, Windows 10 was successfully installed on the VM. Later, I will link this device to a domain and utilise it as a Helpdesk account.</p>

<hr width="100%" size="2">

<br />

<p align="center"> 
STEP 6 (Creating a 3rd VM and Installing Windows 10 for Employee Client Device): <br/>
<img src="https://i.imgur.com/xqgtys0.png" height="70%" width="70%"/> </p>


<p align="center">I need to add an additional VM for this project. I'd like to add this virtual machine so that I can manage it from Active Directory using the "Helpdesk" account, allowing me to practise with "Active Directory Users and Computers". I'll also add the device to the domain.
As you can see, I have added the new device to the VirtualBox software. The device is called "Desktop2" and will function as a standard employee client within the domain. I upgraded the device with 2GB of RAM, one CPU core, and 30GB of hard disk capacity. I've also loaded "Windows 10" Pro on the device, and this version of Windows 10 allows me to add the device to the domain.</p>


<br />
<br />

<p align="center"> 
<img src="https://i.imgur.com/mNaWdu4.png" height="70%" width="70%"/> </p>

<br />

<p align="center"> 
<img src="https://i.imgur.com/sY3Fzoy.png" height="70%" width="70%"/> </p>


<p align="center">As you can see, Windows 10 has been installed on the third VM. The device was in the process of being installed in the first image above, and it successfully started up with Windows 10 in the second image below.</p>



