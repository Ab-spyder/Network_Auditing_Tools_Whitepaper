# Network_Auditing_Tools_Whitepaper
## Capstone Project (FALL 2020)
### Project Sponser: Raytheon Technologies
Whitepaper to identify which network auditing solution is best and compare their capabilities

The goal of this project was to determine the best utility to use for monitoring of network devices to meet the security control requirements laid forth by Defense Information Systems Agency (DISA) to meet RMF compliance. By using GNS3, a network software emulator, our team has created a fully virtualized environment, including a Virtual Router, a lightweight syslog forwarder called Vector, five Virtual Machines on AWS, and individually installed network auditing tools to perform testing.

The tools were tested for the following generated events:
1. Failed login for operator account (3x)
2. Successful login for administrative account
3. New device added to network
4. Old device taken off network
5. Interface shutdown
6. Interface turned on
