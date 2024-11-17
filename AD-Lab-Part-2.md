## Introduction

- I will install DHCP Server, 

- Windows 10 Client Machine and join it to the domain.

## DHCP

# Installation

First click on Manage > Add Roles and Features > Next > Choose Role-based > Next > Choose Your destination server (local in our case) > Next > Choose DHCP (Option ticked in image below) > Install

![Capture0](https://github.com/user-attachments/assets/8ff49b30-f27f-4355-8751-ca0c0ecfa623)

![Capture1](https://github.com/user-attachments/assets/c513a821-6c6f-47d9-aae3-9de80e49212e)

![Capture2](https://github.com/user-attachments/assets/c159aaed-c776-4c8a-a2f2-09e91de4c317)

# Configuration

_Go to Tools > DHCP_

First I will authorize this server to distribute addresses in the domain.

![Capture3](https://github.com/user-attachments/assets/e0699055-43df-4659-bdaa-86f37a8f915c)
![Capture4](https://github.com/user-attachments/assets/d2ab76f7-8c55-41ea-b43c-523d15cc100a)

To create a scope Right click on IPv4 > Choose New Scope > Give a name to the scope > Enter the scope range > You can add exclusion addresses or ranges > Finally configure some options (Gateway, DNS Servers, NTP Server, etc...)

![Capture5](https://github.com/user-attachments/assets/702649fa-0472-45da-9305-5d311da72198)

![Capture6](https://github.com/user-attachments/assets/0b50de2d-8b48-4fd2-b729-8a5a189691cd)

![Capture7](https://github.com/user-attachments/assets/a6e439d9-29e0-4040-9d30-856b4b03059f)

![Capture8](https://github.com/user-attachments/assets/f577151e-0f7f-437a-9911-792f1fd89bcc)

![Capture9](https://github.com/user-attachments/assets/859111d4-b128-4cf1-8e42-111c0e7e111c)

![Capture10](https://github.com/user-attachments/assets/e5834566-f0f1-49ba-9cf0-9258d247ec55)

![Capture11](https://github.com/user-attachments/assets/2dda8057-2559-4bc4-b2bd-16c4ebcb0876)








