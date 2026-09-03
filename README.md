# Windows 11 Client – Active Directory Domain Join Lab

## Lab Overview

A hands-on lab demonstrating the full lifecycle of bringing a Windows 11 client into a Windows Server 2022 Active Directory domain: installing the client OS, configuring networking and DNS, joining it to the domain, and validating authentication and shared resource access through Organizational Units.

## Environment

- **Client:** Windows 11 Pro (`Client01`), running in Oracle VirtualBox
- **Domain Controller:** Windows Server 2022, domain `sudeep.local`
- **Organizational Units:** `Finance`, `HR`, `IT`, `Staff`, `Finance Team`, `HR Team`, `IT support`
- **Sample domain users:** David Lee, Mike Brown, John Smith, Sarah Wilson
- **Shared resources:** `\\localhost\CompanyData`, `\\localhost\Finance`, `\\localhost\HR`, plus the default `NETLOGON` and `SYSVOL` shares

## Topics Covered

- Windows 11 client installation
- Client IPv4 and DNS configuration
- Network connectivity testing
- Domain join (`sudeep.local`)
- Active Directory integration
- Organizational Unit (OU) management and moving users between OUs
- Shared folder access and permissions

## Conclusion

Successfully deployed and configured a Windows 11 client in an Active Directory environment and validated domain connectivity, authentication, and shared resource access — including confirming the client joined the `sudeep.local` domain and could browse departmental shares such as `CompanyData`.

## Repository Contents

- [`Joining a Windows 11 Client to an Active Directory Domain.pdf`](<./Joining a Windows 11 Client to an Active Directory Domain.pdf>) — full step-by-step write-up
- [`client windows 11 SS/`](<./client windows 11 SS>) — implementation evidence (client installation, domain join, and shared resource access)

## Author

**Sudeep Kumar Chaurasiya**

Bachelor of Information Technology (Networking / Cyber Security)
Melbourne Institute of Technology, Sydney

GitHub: [github.com/sudeep0449](https://github.com/sudeep0449)
