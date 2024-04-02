**Steps to Create an Active Directory Lab in Azure:**

1. **Sign Up for Azure:**
   - Create a Microsoft Azure account if you don't have one and sign in to the Azure Portal.

2. **Create a Resource Group:**
   - Navigate to the Azure Portal and create a new resource group to contain the resources for your lab.
![Opera Snapshot_2024-04-02_110357_portal azure com](https://github.com/Malik-444/Azure-Active-Directory-Lab/assets/151242422/55bf5a12-b2d6-4836-aaf0-f8edbc4fa5e0)

3. **Deploy Virtual Machines:**
   - Deploy virtual machines in Azure for domain controllers, member servers, and client workstations within your resource group.![Opera Snapshot_2024-04-02_111415_portal azure com](https://github.com/Malik-444/Azure-Active-Directory-Lab/assets/151242422/5ff17d68-dcd3-4bc8-875f-2014d7729ad0)

4. **Set Up Domain Controllers:**
   - Install and configure Active Directory Domain Services on the designated virtual machines to act as domain controllers.![Opera Snapshot_2024-04-02_112719_portal azure com](https://github.com/Malik-444/Azure-Active-Directory-Lab/assets/151242422/4a19bb0f-740f-4896-89b0-fe298823ff45)
   - You can make your User and Password whatever u want and going to use rdp to connect to VM![Opera Snapshot_2024-04-02_112854_portal azure com](https://github.com/Malik-444/Azure-Active-Directory-Lab/assets/151242422/3dc86e6d-c2cb-4412-a26d-6e0dd4a63039)
   - After the contoller is setup this how it should look after with your virtual network
    ![Opera Snapshot_2024-04-02_113236_portal azure com](https://github.com/Malik-444/Azure-Active-Directory-Lab/assets/151242422/f466b8ac-5e81-418a-ab04-d9747c6b7791)
   -Now we are going to connect and setup the contoller, U can download the RDP file to make it eaiser to connect and orginze VM connections ![Opera Snapshot_2024-04-02_113312_portal azure com](https://github.com/Malik-444/Azure-Active-Directory-Lab/assets/151242422/a3a7d2c0-c743-4d2c-a728-1c5ae1fd4a95)![tempsnip](https://github.com/Malik-444/Azure-Active-Directory-Lab/assets/151242422/85f046b8-650d-4a8a-b535-e417c24786be)
    -After opening your domain controller you should be greeted with this screen![Server Roles And Features](https://github.com/Malik-444/Azure-Active-Directory-Lab/assets/151242422/8bfcc1dc-3577-4e58-9567-2a4c054aed3c)
    -Navigate to Dashboard then Server Roles and enable Active Directory Domain Services 
    - Click Add Features and continue to the installation stage![ad roles 4](https://github.com/Malik-444/Azure-Active-Directory-Lab/assets/151242422/1aeab546-d7dd-4c73-9623-7f800a879ea5)

    - After the install in your server




5. **Configure Virtual Networks:**
   - Create virtual networks and subnets to connect the virtual machines in your Azure environment.
![Opera Snapshot_2024-04-02_110640_portal azure com](https://github.com/Malik-444/Azure-Active-Directory-Lab/assets/151242422/fc9ce639-0fc9-4d44-b84e-d4fda435e8b2)
![Opera Snapshot_2024-04-02_110811_portal azure com](https://github.com/Malik-444/Azure-Active-Directory-Lab/assets/151242422/53b28148-307f-400a-a83f-c56820726141)
**We Are Going to use all defualt setting for the virtual networks**
![Opera Snapshot_2024-04-02_110959_portal azure com](https://github.com/Malik-444/Azure-Active-Directory-Lab/assets/151242422/1cd87340-7b29-4cb5-8490-9c813e030d64)

6. **Join Member Servers to the Domain:**
   - Join the member servers to the Active Directory domain created by the domain controllers.

7. **Configure Azure Active Directory:**
   - Set up Azure Active Directory and configure user identities, groups, and access controls in the Azure Portal.


8. **Testing and Optimization:**
    - Test user authentication, access controls, and policies to ensure they function correctly. Optimize the Azure AD configuration for performance and security.

By following these steps, you can create an Active Directory lab environment in Azure to practice and learn about cloud-based directory services, user management, and identity and access management solutions.
