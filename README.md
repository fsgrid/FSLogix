# FSLogix

Download latest version from Releases:       
https://github.com/cfgmin/FSLogix/releases/tag/25.09

## System requirements

* Requires .NET Framework version 4.6 or later
* Minimum supported operating systems include Windows 10 and Windows Server 2016

## Introduction

FSLogix is a Windows virtualization optimization and profile management solution designed for enterprise VDI and cloud desktops. It helps deliver a consistent user experience by separating user profiles and application data from the underlying operating system and storing them in virtual hard disk containers (VHD/VHDX). At sign-in, these containers are mounted and presented to the session as a native profile, which reduces logon time and minimizes profile corruption compared to traditional roaming profiles or folder redirection.

FSLogix is commonly used with Azure Virtual Desktop, Citrix Virtual Apps and Desktops, and VMware Horizon to improve performance and simplify administration in non-persistent or pooled environments. Profile Containers capture the full user profile, while Office Containers can isolate and optimize Microsoft 365 data such as Outlook OST, OneDrive cache, and Teams-related content, improving responsiveness and reducing network overhead.

Administration is typically handled through Group Policy or registry-based configuration, enabling IT teams to control container locations, permissions, exclusions, and advanced behaviors for troubleshooting and compatibility. With central storage (SMB shares, Azure Files, or other supported file services), FSLogix supports scaling user workloads while maintaining profile portability across hosts. Overall, FSLogix provides a practical, production-grade approach to profile and application data management for modern virtual desktop deployments, improving stability, user satisfaction, and operational efficiency.
