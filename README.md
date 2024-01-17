# Network Configuration and Security Steps

1. Establish the network topology and initial settings in GNS3, including the WAN cloud and switches.
2. Configure the FortiGate firewall with initial system settings, including formatting and system reboot procedures.
3. Set up network interfaces on the firewall, configuring access permissions for HTTP, HTTPS, and SSH, and defining IP addresses for the interfaces.
4. Configure the DHCP server settings on the firewall, specifying the default gateway, netmask, and the IP address range for DHCP clients.
5. Test connectivity from a Windows machine, verifying that DHCP settings are applied and that the system can ping the default gateway.
6. Attempt to access the firewall’s web interface from the Windows machine, indicating the setup of administrative web access.
7. Adjust system settings within the firewall's web interface, such as hostname, NTP settings, and administrative access ports.
8. Edit network interfaces through the web interface, setting up IP addresses and enabling DHCP server functionality for different VLANs or interfaces.
9. Adjust feature visibility within the firewall's web interface to enable or disable various security features and system settings.
10. Configure service groups and policy routes within the firewall's interface to control traffic flow and access to services.
11. Access the DNS settings in the FortiGate firewall's web interface, showing a section for DNS Service on Interface and DNS Database without entries.
12. View the IPv4 policy settings within the FortiGate firewall, detailing the policies for traffic between different network zones and interfaces.
13. Configure network settings on a Windows Server, specifically setting static IP details including IP address, subnet mask, default gateway, and DNS servers.
14. Perform network connectivity tests via PowerShell on a Windows machine, including pinging the local gateway and external servers like Google.
15. Configure Internet Time settings on a Windows Server, showing successful synchronization with an NTP server.
16. Review properties and event logs within the Server Manager on a Windows Server, providing system information and recent event logs.
17. Open the Add Roles and Features Wizard in Windows Server Manager, specifically prompting for features required for Active Directory Domain Services.
18. Display the Windows Server 2012 R2 login screen, prompting for the Administrator's password.
19. Open Active Directory Users and Computers management console, showing various organizational units and user accounts.
20. Configure Internet Time Settings to synchronize with an Active Directory domain, confirming successful time synchronization.
21. Open the System Properties dialog box on a Windows machine, showing the Computer Name/Domain Changes section with the computer name entered as "win10" and joining to the "widgets.localdomain" domain.
22. Confirm in the System Properties window that the Windows 10 computer has successfully joined the "widgets.localdomain" domain.
23. Open the Local Group Policy Editor, showing the Desktop Wallpaper policy configuration set to Enabled with a specified path for the wallpaper image.
24. Run the gpupdate /force command in Windows PowerShell to immediately update group policies.
25. Show the Windows 10 user login screen displaying the new desktop background as a result of the updated group policy.
26. Open Server Manager on Windows Server showing the Add Roles and Features Wizard with IIS (Internet Information Services) selected for installation.
27. Display System Properties of a Windows Server joined to "widgets.localdomain," showing the Computer Name/Domain Changes section with the domain set to "widgets.localdomain."
28. Show the login screen for a Windows Server machine, indicating it is ready for the administrator to log in.
29. Show the installation progress window of the Add Roles and Features Wizard in Server Manager, indicating that IIS is being installed.
30. Open Internet Information Services (IIS) Manager, displaying the default IIS Welcome page, indicating that IIS is installed and running.
31. Open Windows Server Manager, displaying the "Manage" menu with various management options.
32. Open Group Policy Management Console (GPMC), showing the "Forest" and "Domains" sections for managing group policies.
33. Run the gpupdate /force command in Windows PowerShell in the background to update group policies.
34. Display the Group Policy Update Results window in Windows PowerShell, showing the results of the group policy update process.
35. Open Local Group Policy Editor, showing the setting for "Disable changing lock screen and logon image."
36. Open Windows Server Manager displaying the "Add Roles and Features Wizard" with the option to add roles and features to the server.
37. Show Server Manager open, displaying the "All Servers" section with details about the server's roles and status.
38. Run the gpupdate /force command in Windows PowerShell to force an immediate group policy update.
39. Open Windows Server Manager displaying the "Add Roles and Features Wizard" with the option to add roles and features to the server.
40. Show Server Manager open, displaying the "All Servers" section with details about the server's roles and status.
41. Install DokuWiki using the installer accessed through a web browser and fill out the required fields such as Wiki Name and superuser information.
42. Document the network configuration in DokuWiki, detailing the firewall settings, Windows Domain, and other network resources.
43. Create DNS records, including A records and PTR records, for domain resolution within the Windows DNS Manager.
44. Set up firewall rules and policies in the FortiGate VM to define the traffic flow between different network segments.
45. Configure network interfaces on the firewall, assigning IP addresses, roles, and aliases appropriately for WAN, LAN, DMZ, and other segments.
46. Create a network diagram in GNS3 to visualize and plan the network topology, including all devices and their connections.
47. Rename the Windows server to align with the network documentation and domain structure.
48. Add roles and features to the Windows server, such as Web Server (IIS), including role services like FTP Server and FTP Extensibility.
49. Access the FTP server settings in the IIS Manager to configure and secure the FTP site.
50. Verify the FTP site in a web browser to ensure it's accessible and correctly displays the files hosted on the server.
51. Log into the Widgets Network Documentation Wiki and review the VULNERABILITY REPORT section.
52. Analyze the report for weak cipher suites used by SSL/TLS, noting the severity as medium and summarizing the impact.
53. Understand the impact of deprecated SSLv2 and SSLv3 protocols detected on the system, considering the solution to migrate to TLSv1.2+ protocols.
54. Note the server certificate vulnerabilities with RSA keys less than 2048 bits and plan appropriate mitigation steps.
55. Sign into the Greenbone Security Assistant using the provided admin credentials.
56. Examine the Greenbone Security Assistant dashboard for an overview of tasks by severity, CVEs by creation time, and NVTs by severity class. Document hardening notes for the FortiGate firewall, including access control policies, firmware updates, authentication and authorization, logging and monitoring, intrusion prevention systems, and VPN security.

