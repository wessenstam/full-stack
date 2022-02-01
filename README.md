# Labguide for ThycoticCentrify Full Stack lab guide

## Version control
Initial version:0.1
Author: WE


## High level tasks overview 

- The data center should be highly protected. Not just Windows, but also Linux machines
- Protect the machines of the users, without impacting them to much
- Allow the ACME contractors to connect to their data center servers in a secure manner, not using VPN as that is the current situation

1. Account vaulting and discover
2. Command elevation/least privilege
3. Just in Time Privilege
4. Privileged Session auditing
5. Zero Standing privileges
6. Bring DevOps in the mix

## Day 1 - Vaulting and discovery of a domain
Install and initial configure Secret Server with AD, including password rotation and launchers

## Day 2 - Implementing Elevated Rights for the data center
Configure Server/cloud Suite to protect the VMs from all having elevated rights

## Day 3 - Add MFA for access
Configure the Server/Cloud suite to use MFA when certain actions are to be run lie elevated rights or even login to the Domain Controller

## Day 4 - Configure Auditing and Reporting
Installation and configuration of Auditing and reporting for the data center

## Day 5 - Extend the scope to the user's devices like Desktops and Laptops
Install and configure Privilege Manager to remove asmin rights to users and allow elevated rights when needed

## Day 6 - Allow remote users to connect to the infrastructure
Configure the needed components to interact with each other so remote users (including contractors with no AD account) can connect to the infrastruture VPN-less but still on a secure manner

## Day 7 - DevOps
Configure a CI/CD environment to use a Vaulting solution for the secrets that are needed for the code to run successful, including password rotation
 
