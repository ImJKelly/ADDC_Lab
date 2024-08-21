<h1>Active Directory-Domain Controller Lab</h1>

<h2>Description</h2>
Using Oracle Virtual Box, a home lab environment is used to create instatnces of MS Server 2022 and a client running Windows 10. 
The lab demonstrates how to configure the roles of Active Directory and Domanin Controller using MS Server 2022. The lab
also demonstrates how to allow and connect a Windows 10 client to the domain.

<h2>Tools Used</h2>
- Oracle VirtualBox</br>
- Windows 10</br>
- Server 2022

<h2>Lab walk-through</h2>
<b>In the Oracle VitualBox, adding an instance of Server 2022</b>
<img src="https://github.com/user-attachments/assets/3f36029b-f4aa-4e9c-b513-911f72609671" /> 

</br><b>Inserting guest additions image for ease-of-use when working with the virtual machine (VM)</b>
<img src="https://github.com/user-attachments/assets/21cee06c-a101-4948-93ef-c0b04b3b4907" /> </br>

<b>Configuring the NIC, for the internal network, with static addressing</b>
<img src="https://github.com/user-attachments/assets/f7e807b6-51e0-4db3-970b-052e4b87b6d3" /> </br>

<b>Adding Active Directory Domain Service (ADDS) as a role for the server</b>
<img src="https://github.com/user-attachments/assets/ee182b98-c00f-486d-a911-e7a99ce45ad4" /> </br>

<b>Promoting server to a Domain Controller</b>
<img src="https://github.com/user-attachments/assets/c0f376e9-6fbe-4a83-823f-e2cd6dcd6388" /> </br>

<b>Adding a created user as a member of the domain admins</b>
<img src="https://github.com/user-attachments/assets/79f63876-0700-4432-ac57-35c0ee50b50c" /> </br>

<b>Adding the role of Remote Access Server (RAS)</b>
<img src="https://github.com/user-attachments/assets/bed31676-a20a-42ba-b03a-f9536ee4c410" /> </br>

<b>Routing and Network Address Translation (NAT) configured for DC</b>
<img src="https://github.com/user-attachments/assets/6affddbf-55d3-4adf-9542-5c6cf6f7cfc8" /> </br>

<b>Adding role of DHCP Server</b>
<img src="https://github.com/user-attachments/assets/70b79405-a357-49f9-b87f-e936beb3bacb" /> </br>

<b>Configuring the scope of DHCP for the LAN (internal network)</b>
<img src="https://github.com/user-attachments/assets/bef8edd5-baf6-4b19-9434-6c27e7814d38" /> </br>

<b>Shows Windows 10 client VM connected to the domain</b>
<img src="https://github.com/user-attachments/assets/ecc7f394-99d3-4e73-afa5-6d94e12af933" /> 








