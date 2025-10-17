# AD PROJECT: Initializing and utilizing AD

## Overview 
This repository is a project designed to help me transition from theory to practical application. We'll use solutions such as Oracle VirtualBox, Windows Server 2022, and Active Directory. The goal of this project is to further my education in enterprise technology.

## Requirements
### Downloads 
- **Virtualization:** [Oracle VirtualBox](https://www.virtualbox.org/wiki/Downloads)
- **Server OS:** [Windows Server 2022](https://www.microsoft.com/en-us/evalcenter/download-windows-server-2022)
- **Client OS:** [Windows 11 Enterprise](https://www.microsoft.com/en-us/evalcenter/download-windows-11-enterprise)

## Initial setup

### VirtualBox
- [x] Create machines using the [Windows Server 2022](https://www.microsoft.com/en-us/evalcenter/download-windows-server-2022) & [Windows 11 Enterprise](https://www.microsoft.com/en-us/evalcenter/download-windows-11-enterprise) ISO files with virtual box.
- [x] Configure machine names, hardware, and network adapter settings.
- [x] Started the machines, ensured the machines used a secure password, and the network is isolated.
- [x] Create AD forest, domain, and activated AD Domain Services & DNS.

### VirtualBox setup photos
> The screenshot below displays a fully operational and well-configured **VirtualBox** running **Windows Server 2022** & **Windows 11 Enterprise**.

![Configured VirtualBox machines](https://i.imgur.com/W6HHmLe.png)

> The image below shows a running **Active Directory Domain Service** and **DNS**.

![AD Services configured](https://i.imgur.com/0paIYE5.png)

> The photo below shows the configured **Organizational Units**.

![OUs configured](https://i.imgur.com/xqg5QGX.png)

> The screenshot, as shown below, displays properly configured **User Accounts** and **Security Groups** to replicate the standard onboarding process.
 
![OUs configured](https://i.imgur.com/u2D6RfI.png)

> The image shown below shows the client properly connected with the server. It now authenticates against the **Domain Controller**, allowing for centralized user logins and future management via **Group Policy**.

![OUs configured](https://i.imgur.com/Wh4SFFI.png)

