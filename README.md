# AzureProject
Online Food Ordering System In Azure
#Azure Online Food Ordering System Project
This repository contains the setup and configuration for an online food ordering system deployed on Azure. The project involves the creation of two virtual machines (Server1 and Server2) running Ubuntu Server, the installation of the Apache2 server, and the setup of a MySQL database on both servers. Additionally, Azure Traffic Manager, Azure Monitoring Service, and DNS Zones are used to manage and monitor the deployment.

##Project Components
Virtual Machines

#Server1:
Apache2 server installed.
PHP files uploaded to the HTML directory.
MySQL database for the online food ordering system.

#Server2:
Apache2 server installed.
PHP files uploaded to the HTML directory.
MySQL database for the online food ordering system.

##Azure Services:
1)Azure Traffic Manager:
Configured to manage traffic between Server1 and Server2.
Ensures high availability and load balancing for the online food ordering system.

2)Azure Monitoring Service:
Alert rule set up to send notifications (email and SMS) when the system's resource usage exceeds 80% threshold.

3)DNS Zones:
Used for mapping the deployment to a custom domain.
www.kyutorn.site is configured to point to the online food ordering system.

##Deployment Instructions
1)Deploy two virtual machines running Ubuntu Server.
2)Install Apache2 and MySQL on both Server1 and Server2.
3)Upload the PHP files to the HTML directory on both servers.
4)Configure the MySQL databases for the online food ordering system on both servers.
5)Set up Azure Traffic Manager to distribute traffic between Server1 and Server2.
6)Configure the Azure Monitoring Service alert rule for resource monitoring.
7)Create DNS Zones for the custom domain (e.g., www.kyutorn.site) and activate it.
8)Access the online food ordering system by visiting www.kyutorn.site in a web browser.
9)Monitoring and Alerts
10)The system is set to send email and SMS notifications when the resource usage exceeds 80%.
![image](https://github.com/jagdaleonkar/AzureProject/assets/95586197/365e38a0-9289-4ef2-857b-7ee5c2fb745f)
![image](https://github.com/jagdaleonkar/AzureProject/assets/95586197/fdee97a9-8137-42fb-ae94-21ecd742ca38)
![image](https://github.com/jagdaleonkar/AzureProject/assets/95586197/daf350bf-8cc8-4351-8c61-98e8df5d2196)
![image](https://github.com/jagdaleonkar/AzureProject/assets/95586197/40a137ab-d73f-4bd5-afef-ba043addde91)
![image](https://github.com/jagdaleonkar/AzureProject/assets/95586197/97d96f12-a84c-4b33-b6e7-d6d0f7703454)
![image](https://github.com/jagdaleonkar/AzureProject/assets/95586197/4cfc4b6e-2f45-4c9e-812d-99cae3d321d9)
![image](https://github.com/jagdaleonkar/AzureProject/assets/95586197/0677af23-114a-4a08-9db4-840411aa9b45)
![image](https://github.com/jagdaleonkar/AzureProject/assets/95586197/e79a0f66-af1d-40b6-8939-0865a8627d7b)
![image](https://github.com/jagdaleonkar/AzureProject/assets/95586197/04fda701-3d4f-4c50-9eed-947e67eec6d4)
![image](https://github.com/jagdaleonkar/AzureProject/assets/95586197/0c972eb7-65b1-4009-87ec-a858a76cfe8e)
![image](https://github.com/jagdaleonkar/AzureProject/assets/95586197/8f1bd19f-6e21-4dc1-b4c8-9f2ee07c5605)
![image](https://github.com/jagdaleonkar/AzureProject/assets/95586197/b50a9cba-bf71-409c-9aa5-357715731c64)
![image](https://github.com/jagdaleonkar/AzureProject/assets/95586197/eea6e125-53dc-4ca0-9443-a0d600f3701f)
![image](https://github.com/jagdaleonkar/AzureProject/assets/95586197/bf03c46e-547d-4c98-b514-421ab12ccca6)
![image](https://github.com/jagdaleonkar/AzureProject/assets/95586197/d9697124-29f3-4de3-ba19-65ebf55b2a94)
![image](https://github.com/jagdaleonkar/AzureProject/assets/95586197/54a3f828-246f-41ee-996f-2d6b63c94a0e)
![image](https://github.com/jagdaleonkar/AzureProject/assets/95586197/813987d7-482a-49c4-98ff-63bae56ed148)
![image](https://github.com/jagdaleonkar/AzureProject/assets/95586197/4fa1cfae-cada-405e-afa7-8f2df1732f35)
![image](https://github.com/jagdaleonkar/AzureProject/assets/95586197/89a09e6c-de3c-44fb-876f-a36fe28f6f2c)
![image](https://github.com/jagdaleonkar/AzureProject/assets/95586197/b9794b31-e355-4a3a-8268-9b668773337c)
![image](https://github.com/jagdaleonkar/AzureProject/assets/95586197/1ff82d48-f748-4365-b397-72282b18ce11)
![image](https://github.com/jagdaleonkar/AzureProject/assets/95586197/e6318174-46ba-43bd-9fbd-b9c6840b457c)
![image](https://github.com/jagdaleonkar/AzureProject/assets/95586197/88938a0e-88a3-41e8-b921-ae1c83690dff)
![image](https://github.com/jagdaleonkar/AzureProject/assets/95586197/57b0bf0d-14fc-43b6-af52-3c0c0e76185a)
![image](https://github.com/jagdaleonkar/AzureProject/assets/95586197/e2378b8f-c69f-4761-b95f-4481f667cd59)
![image](https://github.com/jagdaleonkar/AzureProject/assets/95586197/4bc08c68-c03e-408d-88a8-ab6f9438d96e)
![image](https://github.com/jagdaleonkar/AzureProject/assets/95586197/92e59fd3-f0a3-4eb4-a029-59d2d61a8e36)
![image](https://github.com/jagdaleonkar/AzureProject/assets/95586197/a6bcded2-ca6f-4cf9-85ac-fcb3d8647105)
![image](https://github.com/jagdaleonkar/AzureProject/assets/95586197/516a01db-ef88-4295-bfad-60d42c7e5f03)
![image](https://github.com/jagdaleonkar/AzureProject/assets/95586197/ba2ce911-dc2d-4930-afac-7bfb9980ff8f)
![image](https://github.com/jagdaleonkar/AzureProject/assets/95586197/8910964e-123a-4078-b5ac-fe34fdcfbf31)
![image](https://github.com/jagdaleonkar/AzureProject/assets/95586197/a29aa394-7aad-42eb-8014-2b3baf92bc2d)
![image](https://github.com/jagdaleonkar/AzureProject/assets/95586197/f55ee1d2-3517-4c14-9d09-4ef128d037c7)
![image](https://github.com/jagdaleonkar/AzureProject/assets/95586197/e86caac6-ae14-4184-ac4b-7b926f2ab267)
![image](https://github.com/jagdaleonkar/AzureProject/assets/95586197/2a90b74f-31bf-4184-8bff-4ae8d816ef8a)
![image](https://github.com/jagdaleonkar/AzureProject/assets/95586197/5c2fd2cd-e833-4423-8f1f-42dc4244f875)
![image](https://github.com/jagdaleonkar/AzureProject/assets/95586197/71ae6669-072b-4db9-a78c-5a66971adfdb)
![image](https://github.com/jagdaleonkar/AzureProject/assets/95586197/bca15608-48d9-4142-b0a9-af59ae99c2d6)
![image](https://github.com/jagdaleonkar/AzureProject/assets/95586197/26f405c5-0bff-47bf-99a7-4baee3805367)
![image](https://github.com/jagdaleonkar/AzureProject/assets/95586197/4f58e095-f421-4e33-8b97-807fcbb9b351)
![image](https://github.com/jagdaleonkar/AzureProject/assets/95586197/c3aa199d-9b90-4661-8387-b42d51208867)
![image](https://github.com/jagdaleonkar/AzureProject/assets/95586197/f0a4768e-7589-43d4-a9a3-98a40a875139)
![image](https://github.com/jagdaleonkar/AzureProject/assets/95586197/ad111103-733d-43f2-bcec-d000697c10c4)
![image](https://github.com/jagdaleonkar/AzureProject/assets/95586197/b56b5612-54f2-4efc-87f5-78384eb41734)
![image](https://github.com/jagdaleonkar/AzureProject/assets/95586197/516019ba-6780-42da-bc6d-32e4ed0abf4b)
![image](https://github.com/jagdaleonkar/AzureProject/assets/95586197/e7d7ecfd-b499-4a4f-ba7c-796bcc2575ed)
![image](https://github.com/jagdaleonkar/AzureProject/assets/95586197/97bb5a65-a427-496f-9050-0df14a3ebd91)
![image](https://github.com/jagdaleonkar/AzureProject/assets/95586197/c232f6c7-83c8-4c81-a342-c6296852f1ba)
![image](https://github.com/jagdaleonkar/AzureProject/assets/95586197/0cf08f24-462e-4bf3-9a65-dd1cb6e580bc)
![image](https://github.com/jagdaleonkar/AzureProject/assets/95586197/9b46ee44-1901-49b9-84f9-2bd5553453cc)
![image](https://github.com/jagdaleonkar/AzureProject/assets/95586197/47b42ab4-65ad-4467-a31a-bdc4adc64e36)
![image](https://github.com/jagdaleonkar/AzureProject/assets/95586197/82bacb4a-9c25-4c60-8e6b-dabc8420cec9)
![image](https://github.com/jagdaleonkar/AzureProject/assets/95586197/0359f540-aa38-4e8d-95c2-c4898fc94ab8)
![image](https://github.com/jagdaleonkar/AzureProject/assets/95586197/23790779-7310-47dc-a696-e526b710feeb)
![image](https://github.com/jagdaleonkar/AzureProject/assets/95586197/753794f5-2da0-490e-915e-247d71811066)
![image](https://github.com/jagdaleonkar/AzureProject/assets/95586197/c1f8d747-3c95-4707-9e27-f827837d8911)
![image](https://github.com/jagdaleonkar/AzureProject/assets/95586197/a6cf9c26-79b9-4476-8ff6-bbd0d1692a7a)
![image](https://github.com/jagdaleonkar/AzureProject/assets/95586197/49a19a8c-d56b-419e-ac05-d4e775e2b332)
![image](https://github.com/jagdaleonkar/AzureProject/assets/95586197/fbc5517e-a4a6-48b7-9bf1-8b59bbbe7966)
![image](https://github.com/jagdaleonkar/AzureProject/assets/95586197/2674008c-3d8b-40d1-b3ba-57c4b542999a)




