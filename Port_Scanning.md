# Port Scanning

## Objective

The objective of this task is to identify open ports and services running on a target system using port scanning techniques.

## Tool Used

* Python Port Scanner
* Nmap
* Termux

## What is Port Scanning?

Port scanning is a technique used to discover open ports and services available on a network host. It helps security professionals understand which services are accessible and identify potential security risks.

## Procedure

1. Installed Python and Nmap in Termux.
2. Created a Python Port Scanner using the socket module.
3. Executed the scanner against the target host.
4. Scanned ports from 1 to 100.
5. Recorded all open ports discovered during the scan.

## Python Port Scanner Code

The scanner uses Python socket programming to connect to ports and determine whether they are open or closed.

## Scan Results

Target: scanme.nmap.org

Open Ports Found:

* Port 22 (SSH)
* Port 80 (HTTP)

## Analysis

### Port 22 - SSH

SSH (Secure Shell) is used for secure remote login and administration of systems.

### Port 80 - HTTP

HTTP is used for web communication and allows users to access websites hosted on the server.

## Findings

The scan successfully identified active network services running on the target host. Open ports indicate available services that should be monitored and secured.

## Conclusion

Port scanning is an important network security technique used to discover active services and assess the security posture of a system. This task provided practical experience with Python socket programming and basic network reconnaissance.
