![Test](https://github.com/matthewpriddy/azure-vm-resource/blob/main/header.PNG?raw=true)





<h2>Environments and Technologies Used</h2>

- Microsoft Azure Subscription
- Remote Desktop

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)
- Windows Server 2022
- Ubuntu Server 22.04 LTS



<h2>Installation Steps</h2>

Lets start with creating a **Resource Group**.

- - - -

![test](https://github.com/matthewpriddy/azure-vm-resource/blob/main/Create%20Resource.png?raw=true)
</p>
<p>
  
- - - -
  
</p>
<br />

![test](https://github.com/matthewpriddy/azure-vm-resource/blob/main/Create%20Resource%202nd.png?raw=true)
</p>
<p>
  
- - - -
  
</p>
<br />

![test](https://github.com/matthewpriddy/azure-vm-resource/blob/main/Create%20Resource%203rd.png?raw=true)
</p>
<p>
  
- - - -
  
</p>
<br />

![test](https://github.com/matthewpriddy/azure-vm-resource/blob/main/Create%20Resource%204th.png?raw=true)
</p>
<p>

- - - -

  
Now that we have our **Resource group** created, let's move on to deploying our first of three distinctive **Virtual Machines (VM)**. Before we do, it's important to note that for every **VM** created, we want them to:

► share the same _Location_

► share the same **Resource Group**

► Have a _Size_ customized to the User's speed need. We'll select Standard _Size_ for this tutorial


The first **VM** will be a Windows 10 computer we will call "VM1".
  
- - - -
  
![test](https://github.com/matthewpriddy/azure-vm-resource/blob/main/Create%20Virtual%20Machine%201st.png?raw=true)
</p>
<p>

- - - -

</p>
<br />

![test](https://github.com/matthewpriddy/azure-vm-resource/blob/main/Create%20Virtual%20Machine%202nd.png?raw=true)
</p>
<p>
  
- - - -
  
</p>
<br />

![test](https://github.com/matthewpriddy/azure-vm-resource/blob/main/Create%20Virtual%20Machine%203rd.png?raw=true)
</p>
<p>
  
- - - -
  
</p>
<br />

![test](https://github.com/matthewpriddy/azure-vm-resource/blob/main/Create%20Virtual%20Machine%204th.png?raw=true)
</p>
<p>
  
- - - -
  
</p>
<br />

![test](https://github.com/matthewpriddy/azure-vm-resource/blob/main/Create%20Virtual%20Machine%205th.png?raw=true)
</p>
<p>
  
- - - -
  
</p>
<br />

![test](https://github.com/matthewpriddy/azure-vm-resource/blob/main/Create%20Virtual%20Machine%206th.png?raw=true)
</p>
<p>
  
- - - -

Now that we have deployed the Windows 10 **virtual machine**, lets move on to deploy the Windows Server 2022 **virtual machine**. To do so, lets select Create another **VM**. Repeat the initial deployment steps as for the previously deployed **virtual machine** until you reach the screen under the Basics tab. We will name this **VM** "VM2".
  
- - - -

</p>
<br />

![test](https://github.com/matthewpriddy/azure-vm-resource/blob/main/Create%20Virtual%20Machine%208th.png?raw=true)

- - - -

</p>
<br />

![test](https://github.com/matthewpriddy/azure-vm-resource/blob/main/Create%20Virtual%20Machine%209th.png?raw=true)

- - - -

For the last **VM** which we will call "VM3", we are deploying a Linux **virtual machine**. Repeat the initial deployment steps as for the previously deployed **virtual machine** until you reach the screen under the Basics tab.

- - - -

</p>
<br />

![test](https://github.com/matthewpriddy/azure-vm-resource/blob/main/Create%20Virtual%20Machine%2010th.png?raw=true)

- - - -

</p>
<br />

![test](https://github.com/matthewpriddy/azure-vm-resource/blob/main/Create%20Virtual%20Machine%2011th.png?raw=true)

- - - -

</p>
<br />

![test](https://github.com/matthewpriddy/azure-vm-resource/blob/main/Create%20Virtual%20Machine%209th.png?raw=true)

- - - -

</p>
<br />

![test](https://github.com/matthewpriddy/azure-vm-resource/blob/main/Create%20Virtual%20Machine%205th.png?raw=true)

- - - -

From the search bar at the top of the Azure webpage, search virtual machine. We have deployed three **virtual machines**.

- - - -

</p>
<br />

![test](https://github.com/matthewpriddy/azure-vm-resource/blob/main/search%20bar.png?raw=true)

- - - -

So all that's left for us to do now to wrap up this tutorial, is to remote in to one of these machines from our local PC desktop. Click on "VM2" from the **Virtual machines** screen to copy the Public IP Address of "VM2". 

- - - -

</p>
<br />

![test](https://github.com/matthewpriddy/azure-vm-resource/blob/main/Create%20Virtual%20Machine%2012th.png?raw=true)

- - - -

From the desktop, utilize the search bar of the Start Menu and find "Remote Desktop Connection".

- - - -

</p>
<br />

![test](https://github.com/matthewpriddy/azure-vm-resource/blob/main/remote%20in.png?raw=true)

- - - -

Enter "VM2" as the Username and the password you created for this machine (disregard the VM1 reference in the example pic below). It will take a few moments to boot like a desktop.

- - - -

</p>
<br />

![test](https://github.com/matthewpriddy/azure-vm-resource/blob/main/sign%20in%20to%20vm1.PNG?raw=true)

- - - -

</p>
<br />

![test](https://github.com/matthewpriddy/azure-vm-resource/blob/main/sign%20in%20to%20vm1%20part%202.PNG?raw=true)

- - - -

Congratulations, you are now logged in. This concludes this tutorial.
