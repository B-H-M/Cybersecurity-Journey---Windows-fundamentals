# 🔐 Cybersecurity Learning Journey | LetsDefend.io

## 🖥️ Windows Fundamentals

**Platform:** [LetsDefend.io](https://letsdefend.io/)  
**Course:** Windows Fundamentals  
**Learning Focus:** Windows Administration | Endpoint Security | SOC Analysis | Blue Team  
**Achievement:** 🏅 Systsem sentinel Badge

---

## 📌 Overview

As part of my ongoing cybersecurity learning journey, I have completed the **Windows Fundamentals** course on LetsDefend.io, strengthening my understanding of Windows operating systems, system administration, and endpoint security.

This course covered essential Windows concepts, including file systems, directory structures, command-line operations, user and group management, permissions, processes, services, scheduled tasks, the Windows Registry, firewall configuration, event logs, and Windows Management Instrumentation (WMI).

The knowledge gained provides a strong foundation for understanding Windows system behavior, identifying suspicious activities, investigating security events, and developing practical Security Operations Center (SOC) analyst skills.

Earning the **Windows User Badge** represents another milestone in my cybersecurity learning journey.

---

## 📑 Table of Contents

1. [Introduction to Windows](#1-introduction-to-windows)
2. [Windows Filesystems](#2-windows-filesystems)
3. [Directory Structure](#3-directory-structure)
4. [Windows Command Line](#4-windows-command-line)
5. [Windows Users and Groups](#5-windows-users-and-groups)
6. [Permissions Management on Windows](#6-permissions-management-on-windows)
7. [Windows Process Management](#7-windows-process-management)
8. [Windows Services](#8-windows-services)
9. [Task Scheduler](#9-task-scheduler)
10. [Windows Registry](#10-windows-registry)
11. [Windows Firewall](#11-windows-firewall)
12. [Event Logs](#12-event-logs)
13. [Windows Management Instrumentation](#13-windows-management-instrumentation-wmi)
14. [Key Learning Outcomes](#-key-learning-outcomes)
15. [System Sentinel Badge Achievement](#-windows-user-badge-achievement)
16. [Application to SOC Operations](#-application-to-soc-operations)
17. [Next Learning Goals](#-next-learning-goals)
18. [Conclusion](#-conclusion)

---

## 📚 Course Summary

### 1. Introduction to Windows

Developed a stronger understanding of Windows operating system architecture, functionality, and its role in enterprise IT environments.

**SOC Relevance:** Understanding Windows system behavior helps identify abnormal activities, security misconfigurations, and potential endpoint threats.

### 2. Windows Filesystems

Explored Windows file systems, particularly NTFS, including file organization, access controls, and security-related features.

**SOC Relevance:** File system knowledge supports investigations involving unauthorized file access, suspicious file modifications, and malicious file activity.

### 3. Directory Structure

Studied the Windows directory hierarchy and important system locations, including:

- `C:\Windows`
- `C:\Windows\System32`
- `C:\Program Files`
- `C:\Program Files (x86)`
- `C:\Users`
- `C:\ProgramData`

**SOC Relevance:** Understanding system directories helps analysts identify suspicious files and unusual executable locations.

### 4. Windows Command Line

Strengthened my familiarity with Command Prompt and essential Windows commands.

| Command | Function |
|---|---|
| `whoami` | Displays the current user |
| `ipconfig /all` | Displays detailed network configuration |
| `systeminfo` | Displays system information |
| `tasklist` | Lists running processes |
| `net user` | Displays or manages user accounts |
| `netstat -ano` | Displays network connections and process IDs |
| `sc query` | Queries Windows services |

**SOC Relevance:** Command-line proficiency supports system investigation, troubleshooting, and basic incident response activities.

### 5. Windows Users and Groups

Explored local user accounts, administrative privileges, security groups, and account management.

**SOC Relevance:** Understanding user and group management supports the investigation of unauthorized accounts, privilege misuse, and suspicious account activity.

### 6. Permissions Management on Windows

Studied NTFS permissions, access control lists (ACLs), and permission inheritance.

**SOC Relevance:** Helps identify excessive privileges, unauthorized access, and potentially insecure file permissions.

### 7. Windows Process Management

Learned how Windows manages running applications and background processes, including process IDs and parent-child relationships.

**SOC Relevance:** Process monitoring supports the identification of suspicious executables, unusual process behavior, and potentially malicious activity.

### 8. Windows Services

Explored Windows services and their role in running background system operations.

Relevant tools include:

- `services.msc`
- `sc query`
- `Get-Service` in PowerShell

**SOC Relevance:** Monitoring services can help identify suspicious service installations and persistence mechanisms used by attackers.

### 9. Task Scheduler

Studied how Windows Task Scheduler automates system activities and executes tasks based on configured triggers.

Relevant tools include:

- `taskschd.msc`
- `schtasks`
- `Get-ScheduledTask` in PowerShell

**SOC Relevance:** Scheduled tasks are important during security investigations because attackers may abuse them to establish persistence or execute malicious commands.

### 10. Windows Registry

Developed an understanding of the Windows Registry and its role in storing operating system and application configuration settings.

Explored major registry hives such as:

- `HKEY_LOCAL_MACHINE`
- `HKEY_CURRENT_USER`
- `HKEY_CLASSES_ROOT`
- `HKEY_USERS`

**SOC Relevance:** Registry analysis supports the investigation of unauthorized configuration changes and common persistence techniques.

### 11. Windows Firewall

Studied how Windows Defender Firewall controls inbound and outbound network traffic using configurable rules.

Relevant tools include:

- `wf.msc`
- `netsh advfirewall`
- `Get-NetFirewallRule` in PowerShell

**SOC Relevance:** Firewall knowledge supports investigations involving unauthorized connections, suspicious traffic, and security policy violations.

### 12. Event Logs

Explored Windows Event Logs and their importance in recording operating system, application, and security-related activities.

Important log categories include:

| Log | Purpose |
|---|---|
| Security | Authentication and audited security events |
| System | Operating system and service events |
| Application | Application-generated events |
| PowerShell Operational | PowerShell-related operational activity |
| Task Scheduler Operational | Scheduled task activity |

**SOC Relevance:** Windows Event Logs are essential for investigating suspicious logins, privilege changes, service modifications, and other security events.

### 13. Windows Management Instrumentation (WMI)

Learned how WMI provides access to system management information, including operating system details, hardware configurations, processes, and user accounts.

Example commands:

```powershell
Get-CimInstance Win32_OperatingSystem
Get-CimInstance Win32_ComputerSystem
Get-CimInstance Win32_Process
```

**SOC Relevance:** WMI knowledge supports system investigation, endpoint visibility, and understanding how attackers may abuse legitimate Windows management capabilities.

---

## 🎯 Key Learning Outcomes

Through Windows Fundamentals, I have strengthened my understanding of:

- Windows operating system architecture and administration.
- NTFS file systems and directory structures.
- Windows command-line tools and system troubleshooting.
- User accounts, groups, and access permissions.
- Process, service, and scheduled task management.
- Windows Registry configuration.
- Firewall rules and network security controls.
- Event log analysis fundamentals.
- Windows Management Instrumentation (WMI).

These skills complement my existing IT support and systems analysis experience and contribute to my continued development in cybersecurity.

---

## 🏅 System Sentinel Badge Achievement

<img width="418" height="424" alt="System Sentinel" src="https://github.com/user-attachments/assets/e546336e-f1f2-4412-adb5-e8a14c54e0d3" />

---

## 🛡️ Application to SOC Operations

The Windows knowledge developed through this course is relevant to several important SOC responsibilities.

| Windows Skill | SOC Application |
|---|---|
| Filesystems | Investigating suspicious files and modifications |
| Users and Groups | Detecting unauthorized accounts and privilege misuse |
| Permissions | Identifying insecure access configurations |
| Process Management | Investigating suspicious processes |
| Windows Services | Identifying potential persistence mechanisms |
| Task Scheduler | Investigating malicious scheduled tasks |
| Windows Registry | Detecting suspicious configuration changes |
| Windows Firewall | Reviewing unauthorized network access |
| Event Logs | Investigating authentication and system security events |
| WMI | Collecting system information and identifying suspicious management activity |

Understanding these concepts provides a foundation for endpoint investigation, security event monitoring, and incident response.

---

## 🚀 Next Learning Goals

As I continue my cybersecurity development, my next learning priorities include:

- Linux Fundamentals for Blue Team Operations
- Windows Event Log Analysis
- SIEM Monitoring and Alert Investigation
- Endpoint Detection and Response (EDR)
- Threat Hunting Fundamentals
- Malware Behavior and Persistence Techniques
- Practical SOC Investigation Labs

I will continue documenting my progress, technical knowledge, and hands-on cybersecurity exercises through my GitHub portfolio.

---

## 📝 Conclusion

Completing **Windows Fundamentals** represents another important step in my cybersecurity learning journey.

The course has strengthened my understanding of Windows system administration, endpoint security, access management, and system monitoring.

Earning the **Windows User Badge** further motivates me to continue developing practical technical skills relevant to SOC analysis, threat detection, and incident response.

**My biggest takeaway:** Understanding normal Windows system behavior is essential for recognizing suspicious activities and investigating potential security threats.

---

## 🏷️

#Cybersecurity #LetsDefend #WindowsFundamentals #WindowsUserBadge #SOCAnalyst #BlueTeam #WindowsSecurity #EndpointSecurity #WindowsEventLogs #WindowsRegistry #WMI #ThreatDetection #IncidentResponse #CybersecurityJourney #ContinuousLearning

---

*Building cybersecurity knowledge, one operating system at a time.* 🔐
