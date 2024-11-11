## Introduction
In this lab, I will simulate the installation of a Windows Server 2019 machine and configure ADDS on it to become a Domain Controller.
# AD Lab Requirements:
VMware Workstation Pro

Windows Server 2019 ISO

Windows 10 ISO
## Setting Up the Domain Controller
1. Open VMware Workstation Pro > File > New VM > Enter a name for the VM > Select Microsoft Windows as the Type > Select Windows 2019 (64-bit) as the Version > Next

![Capture 0](https://github.com/user-attachments/assets/4bdaf3e0-6890-4042-b0a0-75515fc0c8c6)
![Capture 1](https://github.com/user-attachments/assets/b4179d75-46e8-4124-8c56-94f2f344f389)

2. Specify a destination path for the VM > Create a Hard Disk & set the size to 50 GB

![Capture 2](https://github.com/user-attachments/assets/da8f47d0-1af3-42ab-b55a-4b9c4135606d)
![Capture 3](https://github.com/user-attachments/assets/7e6da549-ffe7-48c2-8f47-ee6d9c8a0db5)

3. Mount the ISO file
![Capture 4](https://github.com/user-attachments/assets/2384d198-6eb1-441f-9336-c9d22cd8f62d)

4. Now our VM is ready!!!
![Capture 5](https://github.com/user-attachments/assets/66bfef65-8f19-47bb-80ee-6b570b0debdd)

## Windows Server 2019 configuration steps:
1. Start up the VM, choose your preferred settings and click Next > Install now.
![Capture 7](https://github.com/user-attachments/assets/b2e47a5a-85ef-4af9-a30c-bc9cd38e57e0)
![Capture8](https://github.com/user-attachments/assets/2e7781ba-742b-4105-a02c-77f500be336c)


2. Select Windows Server 2019 Datacenter Evaluation (Desktop Experience) > Next > Tick the license terms > Next


3. Select, Custom: Install Windows only (advanced) > New > Apply > Next


4. After successful installation, enter a password > Finish. Then enter the password to login after finalization.


5. 
