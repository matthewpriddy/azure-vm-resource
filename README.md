![the very first](https://github.com/matthewpriddy/azure-vm-resource/assets/132313534/9145f582-4d46-4d34-a2d0-243c0d8fc7ed)






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

![part 1](https://github.com/matthewpriddy/azure-vm-resource/assets/132313534/6935bab7-e82c-40f0-98d0-f61913d59721)

</p>
<p>
  
- - - -
  
</p>
<br />

![part 2 of 4](https://github.com/matthewpriddy/azure-vm-resource/assets/132313534/66e34ba7-2b09-43e8-b7da-1006c67b86dc)

</p>
<p>
  
- - - -
  
</p>
<br />

![part 3 of 4](https://github.com/matthewpriddy/azure-vm-resource/assets/132313534/fe5501c2-6826-4e4f-b94e-6df296d6b861)

</p>
<p>
  
- - - -
  
</p>
<br />

![part 4 of 4](https://github.com/matthewpriddy/azure-vm-resource/assets/132313534/b95c69a4-5056-46ce-89f6-f2e6fca5c7dd)

</p>
<p>

- - - -

  
Now that we have our **Resource group** created, let's move on to deploying our first of three distinctive **Virtual Machines (VM)**. Before we do, it's important to note that for every **VM** created, we want them to:

► share the same _Location_

► share the same **Resource Group**

► Have a _Size_ customized to the User's speed need. We'll select Standard _Size_ for this tutorial


The first **VM** will be a Windows 10 computer we will call "VM1".
  
- - - -
  
![5](https://github.com/matthewpriddy/azure-vm-resource/assets/132313534/6a0f94f5-10ed-49c7-9ef7-876abab54d3c)

</p>
<p>

- - - -

</p>
<br />

![6](https://github.com/matthewpriddy/azure-vm-resource/assets/132313534/c41af984-97bb-465a-ab9c-59dc7278a53d)

</p>
<p>
  
- - - -
  
</p>
<br />

![7](https://github.com/matthewpriddy/azure-vm-resource/assets/132313534/b337e202-745a-4a1e-83c4-1de067877a4e)

</p>
<p>
  
- - - -
  
</p>
<br />

![8](https://github.com/matthewpriddy/azure-vm-resource/assets/132313534/fa6304e6-1417-4f29-a62d-fcbb76a23e8b)

</p>
<p>
  
- - - -
  
</p>
<br />

![9](https://github.com/matthewpriddy/azure-vm-resource/assets/132313534/675c76c5-6c4c-44e8-89b3-b71af6420803)

</p>
<p>
  
- - - -
  
</p>
<br />

![10](https://github.com/matthewpriddy/azure-vm-resource/assets/132313534/19a58050-e2d8-4331-9daa-192771525741)

</p>
<p>
  
- - - -

Now that we have deployed the Windows 10 **virtual machine**, lets move on to deploy the Windows Server 2022 **virtual machine**. To do so, lets select Create another **VM**. Repeat the initial deployment steps as for the previously deployed **virtual machine** until you reach the "Create a Virtual Machine" screen under the Basics tab. We will name this **VM** "VM2".
  
- - - -

</p>
<br />

![11](https://github.com/matthewpriddy/azure-vm-resource/assets/132313534/6ea0afe7-30a3-4b7f-9849-0345a65685e5)


- - - -

</p>
<br />

![12](https://github.com/matthewpriddy/azure-vm-resource/assets/132313534/570238bd-3edb-426c-b093-35997fc983b3)


- - - -

For the last **VM** which we will call "VM3", we are deploying a Linux **virtual machine**. Repeat the initial deployment steps as for the previously deployed **virtual machine** until you reach the screen under the Basics tab.

- - - -

</p>
<br />

![13](https://github.com/matthewpriddy/azure-vm-resource/assets/132313534/77b006da-84f3-4a3d-a4f7-c05320745de4)


- - - -

</p>
<br />

![14](https://github.com/matthewpriddy/azure-vm-resource/assets/132313534/fdc1c056-b2d3-4b5a-9d13-8e3db9393bed)


- - - -

</p>
<br />

![15](https://github.com/matthewpriddy/azure-vm-resource/assets/132313534/02e38f50-3649-45ee-b72f-99bfb108d71c)


- - - -

</p>
<br />

![16](https://github.com/matthewpriddy/azure-vm-resource/assets/132313534/b08480f2-08a8-4070-8363-61e57cafc140)


- - - -

From the search bar at the top of the Azure webpage, search virtual machine. We have deployed three **virtual machines**.

- - - -

</p>
<br />

![17](https://github.com/matthewpriddy/azure-vm-resource/assets/132313534/0e01c0fa-d152-4b90-b127-bcb2d137b4a0)


- - - -

So all that's left for us to do now to wrap up this tutorial, is to remote in to one of these machines from our local PC desktop. Click on "VM2" from the **Virtual machines** screen to copy the Public IP Address of "VM2". 

- - - -

</p>
<br />

![18](https://github.com/matthewpriddy/azure-vm-resource/assets/132313534/b47f014b-26a8-43fc-9282-22280202cf0c)


- - - -

From the desktop, utilize the search bar of the Start Menu and find "Remote Desktop Connection".

- - - -

</p>
<br />

![19](https://github.com/matthewpriddy/azure-vm-resource/assets/132313534/61772c20-2c78-47da-8537-1d2b10f4bef3)


- - - -

Enter "VM2" as the Username and the password you created for this machine (disregard the VM1 reference in the example pic below). As a desktop might, it will take a few moments to boot.

- - - -

</p>
<br />

![20](https://github.com/matthewpriddy/azure-vm-resource/assets/132313534/39c71479-2ca0-4f8a-96f2-48bf07f0f20a)


- - - -

</p>
<br />

![21](https://github.com/matthewpriddy/azure-vm-resource/assets/132313534/867a02f1-c201-4698-b0e2-0a9e8583c8fa)


- - - -

Congratulations, you are now logged in. This concludes this tutorial.
