# osdr

Off-Site Data Recovery (OSDR) tools are a collection of programs targeted to Small Office/Home Office (SOHO) environments to assist with protecting data in the event of complete loss of systems and on-premises storage.

The environment in which these tools were developed includes multiple systems backing up to a single Synology network attached storage (NAS) unit, and then the data on this NAS being protected by the use of NAS included tools extended by OSDR and portable USB disks.
These programs are written in Python 2.7 and are designed to run on Linux. The testing platform has been a Synology NAS running DSM 6.1, as a result these tools have in-built the ability to send messages to the Synology web console notification system. 

The fundamental design philosophy of an OSDR supported backup and disaster recovery strategy is a multi-layered hybrid of: on-site storage redundancy; off-site, off-line storage and cloud storage.

Caution: Some of these tools require “root” privilege to operate. As with any program with this privilege, bugs or misuse could cause significant damage. This software is provided to you in readable Python source code for your inspection prior to execution so use of this code is entirely at your own risk. The terms of use are spelled out formally in the MIT License included in this repository and by using the --license option in each program. If you are not willing to accept these terms of use, do not run this code.
