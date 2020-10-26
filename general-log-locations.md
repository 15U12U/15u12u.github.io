---
layout: page
title: General Log Locations
description: A collection of common log locations in different systems and applications.
nav-menu: true
---

## System

### Windows
```
C:\
   |
   +-- Windows\
               |
               +-- System32\
                            |
                            +-- winevt\
                                       |
                                       +-- Logs\
                                                |
                                                +-- Security.evtx
                                                +-- Application.evtx
                                                +-- System.evtx
                                                +-- Windows Powershell.evtx
                                                +-- Microsoft-Windows-PowerShell%4Operational.evtx
                                                +-- Microsoft-Windows-Sysmon%4Operational.evtx
```


### Linux / Unix
```
/
 |
 +-- var/
         |
         +-- log/
         |       |
         |       +-- messages
         |       +-- syslog
         |       +-- kern.log
         |       +-- cron
         |       +-- dmesg
         |       +-- boot.log
         |       +-- maillog
         |       +-- mail.log
         |       +-- user.log
         |       +-- cups
         |       +-- daemon.log
         |       +-- anaconda.log
         |       +-- auth.log
         |       +-- secure
         |       +-- sulog
         |       +-- dpkg.log
         |       +-- yum.log
         |       +-- wtmp (binary file)
         |       +-- btmp (binary file)
         |       +-- faillog (binary file)
         |       +-- lastlog (binary file)
         |       +-- apt/
         |       |       |
         |       |       +-- history.log
         |       |       +-- term.log
         |       |
         |       +-- audit/
         |                 |
         |                 +--audit.log
         |
         +-- audit/ (binary files)
         |
         +-- adm/ 
         |       | 
         |       +-- messages
         |       +-- secure
         |       +-- wtmpx
         |       +-- sulog
         |
         +-- run/
                 |
                 +-- utmp (binary file)
```
<code>
sdfsdgsdgasdg
</code>