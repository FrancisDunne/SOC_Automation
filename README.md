# SOC Automation

## Objective
In this project you will see how organizations manage their resources such as
users, computers and groups. This project will showcase how to install an active 
directory. It will show how to create a splunk instance where it will be 
ingesting events from a windows server, this windows server will hold the active 
directory. You will also see events ingested from the target windows machine that
uses sysmon, which is a windows system service and device driver that logs system 
activity to the Windows event log. The project will then move on to perform a
brute force attack using Kali Linux as our attacking machine. We will see what telemetry 
it generates. This project will also use atomic red team (ART) so we can see how to
generate some alerts for future activity. 



### Skills Learned

- Understanding of SIEM concepts and practical application.
- Proficiency in analyzing and interpreting network logs.
- Ability to generate and recognize attack signatures and patterns.
- Knowledge of network protocols and security vulnerabilities.
- Ability to build alerts with (ART) so we can detect on specific activity.


### Tools Used

- Splunk (SIEM) system for log ingestion and analysis.
- Windows 10 OS system for target machine.
- Windows server for Active Directory.
- Kali Linux for attacking machine.
- Splunk Universal Forwarder for sending data over to our Splunk server.
- Sysmon for logging system activity.
- Atomic Red Team (ART) for building alerts.
  
## Steps

### Preparation
