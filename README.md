
# PITS IT Management System

Created by me, for me. But will eventually expand to be more useful.

The device management side is working as needed for me at the minute, I can see up to date information about devices such as CPU Load, Disk Information, RAM Usage and installed applications (Windows Only).

I can also manage devices via the use of scripts. Managed and executed via the Web UI, useful scripts can be ran on remote machines with the app running. I use this mainly for rebooting services, however, anything can be done that can be done via CMD or Bash.

The ticketing system needs work. Tickets can be created via the Windows app, or via the Web UI by an engineer. Replying to the tickets and setting a status can be done via the UI. 


## Tech Stack



**Web Client:** Blazor Server Side with Mudblazor Framework

**Web API:** ASP.NET Core 6.0, Entity Framework

**Windows Desktop App:** Wpf 

**Linux Server App:** .netcore 7.0

**DB:** MySQL

**Hosting:** Docker via Github actions


## Features

- Light/dark mode toggle
- Full Device Information, including CPU Load, RAM Usage, Installed Applications etc
- Run scripts on remote machine, protected by TOTP 2FA
- Auth0 User Management
- Ticket Management

## Roadmap

- Email system to send ticket updates and device alerts

- Get more device information

- Add front end support for ticket updates

## Long way down the Road-map

- Mobile app for admin approval of tickets, i.e. for application installs

- Remote Desktop for Windows machines

- SSH Console for Linux machines


## Screenshots

**Home Page**

![Home Page for PITS](https://raw.githubusercontent.com/obiwanconobi/PITS/main/MainMenu1.png)

**Device Information Dialog**
![Dialog for Device Management](https://raw.githubusercontent.com/obiwanconobi/PITS/main/DeviceInfo1.png)

**CPU Load**
![Dialog for CPU Load](https://raw.githubusercontent.com/obiwanconobi/PITS/main/CPULoad.png)

**Disk Information**
![Dialog for Disk Information](https://raw.githubusercontent.com/obiwanconobi/PITS/main/DiskInfo1.png)

**Installed Apps**
![Dialog for Installed Apps](https://raw.githubusercontent.com/obiwanconobi/PITS/main/installedAppsSearch.png)

**Ticket Dialog**
![Dialog for replying to and updating Tickets](https://raw.githubusercontent.com/obiwanconobi/PITS/main/TicketDialog1.png)
