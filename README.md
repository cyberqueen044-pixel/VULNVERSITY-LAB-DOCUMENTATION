# VULNVERSITY-LAB-DOCUMENTATION
# Vulnversity Lab Documentation

## Task 1: Enumeration
### Description
In this task, we performed enumeration to identify potential vulnerabilities on the target system.

### Screenshots
![Nmap Scan](screenshots-Nmap_scan.png)
![Service Version](screenshots/service_version.png)

### Notes
- Nmap revealed several open ports, including SSH and HTTP.
- The HTTP service was running an outdated version of Apache.

## Task 2: Exploitation
### Description
This task involved exploiting a known vulnerability to gain access to the system.

### Screenshots
![Exploit Command](screenshots/exploit_command.png)
![Success Message](screenshots/success_message.png)

### Notes
- We used an exploit for a known Apache vulnerability.
- Gained a shell on the target system.
