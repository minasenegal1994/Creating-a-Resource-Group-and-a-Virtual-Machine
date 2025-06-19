# Creating-a-Resource-Group-and-a-Virtual-Machine
This is a demonstration on using Microsoft Azure to create Resource Groups and a Windows Virtual Machine! Below is a sped-up video of what we'll be creating!


https://github.com/user-attachments/assets/f736505d-435c-4746-81cc-cb8552bf0e78


Step 1:
To start off the tutorial of creating a resource group and a virtual machine, we're going to sign into Microsoft Azure. To do so, we're going to go to "www.portal.azure.com".
After typing in the URL, we should come across the sign in page. Once, we click on the user, we will be signed in.
![1](https://github.com/user-attachments/assets/f3d2473d-f0bd-46ed-87a8-6afafe9c19ef)

Step 2:
First, we are going to create a resource group to put the virtual machine in. After signing in, there will be a search bar at the top of the page. In the search bar, type in "resource group" and click on the first result that pops up. It should bring up a page that says "Resource Groups" at the top. At the bottom-middle of the page, there should be a blue, rectangle button that says, "+ Create".
![2](https://github.com/user-attachments/assets/0ff3c161-1a67-4da6-a22d-01c017c3fe15)

Step 3:
We now see a page that says, "Create a resource group". Below, we have the first 3 fields to fill out: Subscription, Resource group name, and Region. In the subscription field, choose the subscription that is connected to your account. The next field, resource group name, can be filled with any name you choose for the group, preferably with a name that is relevant for what you'll be using it for. The region field is the geographic location where the metadata for the resource group is stored. For this example, I chose "(US) East US". After filling out all the fields, go to the bottom left part of the page and click "Review + create".
![3](https://github.com/user-attachments/assets/8102dae1-4e92-4053-a642-661ec7b736ca)

Step 4:
After creating the resource group, refresh the page, and you should see it listed below by the name it was given.
![4](https://github.com/user-attachments/assets/a02ffcc2-573b-4dca-953a-fad3ad7c6eb5)

Step 5:
Now that the resource group is made, we can work on making the virtual machine. In the search bar, begin typing in "virtual machine" and it should pop up immediately.

![5](https://github.com/user-attachments/assets/2953d8bf-7528-4d85-92a5-4f3c19125041)

Step 6:
On the virtual machine page, we're going to click the blue "+ Create" button and click on "Azure virtual machine".
![6](https://github.com/user-attachments/assets/9cbe0b59-6ac8-4cba-90f8-6b9e10a62f66)

Step 7:

Once we get to the "Create a virtual machine page", we see the first 4 fields to fill out. The first field is subscription, which would be the same subscription chosen for the resource group. In the resource group field, we'll choose the resource group we created in the earlier steps. The third field is the "Virtual machine name" where we will name it something relevant to what the machine will be used for. For the region, we're going to choose the same region that we did for the resource group.
![7](https://github.com/user-attachments/assets/2cc4e8c6-dbda-4de9-90bd-f35993ee0f65)


Step 8:

We'll scroll down to the image field. Since this is a Windows virtual machine that we're making,  we're going to choose "Windows 10 Pro, version 22H2 - x64 Gen2". The image is a very important part of the machine and refers to the operating system that it will run and what software it'll come with.
![8](https://github.com/user-attachments/assets/7a7cb8f0-691a-4774-9b9b-241e2940f646)

Step 9:
Here is where we will create the username and password. This will be what we use to log in when we use the virtual machine on Remote Desktop.

![9](https://github.com/user-attachments/assets/cadff74e-5f56-4413-b745-bbc728fe4312)

Step 10:
Below, in the corner, there will be a section titled "Licensing". We'll check the box since the virtual machine is a Windows virtual machine. Then we'll hit "Next : Disks >".

![10](https://github.com/user-attachments/assets/e2930e18-b84d-4a8b-8a71-aaf4e552faea)


Step 11:
After getting to the next page, Which is "Networking", there's going to be a few more things to quickly look over. More often than not, there's nothing to change on these tabs, but it never hurts to look through them. At the bottom of the page, hit "Next : Networking >", then "Next : Management >", "Next : Monitoring >", "Next : Advanced >", and "Next : Tags >".

![11](https://github.com/user-attachments/assets/6d680519-f047-49fb-a7b1-d6ffca22807f)

Step 12:
Click on the button that says, "Next : Review + create >" and it will bring us to the final step, which is "Create" to finish the virtual machine.
![12](https://github.com/user-attachments/assets/64ce12e6-c054-4bfe-9946-c4494d05b794)


Step 13:

After hitting the button to create the machine, a message will pop up in the corner of the page that says, "Initializing deployment...". It can take a minute for the virtual machine to finish being made.
![13](https://github.com/user-attachments/assets/68133401-d494-428e-b985-d36891f7692f)


Step 14:

This shows what is happening inside of the virtual machine. All of this is included with the machine once it is finished.
![14](https://github.com/user-attachments/assets/7dc1ac58-14e7-4e8e-92e9-3ebfaa71eb2a)


Step 15:
Once the machine is finished, refresh the Virtual machines page and the Windows machine should show up. It will show the name of the resource group that it's in, the region that it was created in, whether the machine is running or not, the size of the machine, and the public IP address.
![15](https://github.com/user-attachments/assets/f03939f7-da59-47f5-860d-831ec74b75a4)

