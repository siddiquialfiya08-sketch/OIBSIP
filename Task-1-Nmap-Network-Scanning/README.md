## Objective
To perform a basic network scan using Nmap and identify open ports and running services on the local system.

## Tool Used
- Nmap

## Command Executed
nmap localhost

## Open Ports Identified

| Port | Service | Description |
|----|--------|------------|
| 135 | MS RPC | Used for Windows system communication |
| 445 | SMB | File and printer sharing service |
| 902 | VMware | Virtual machine communication |
| 912 | VMware Auth | VMware authentication service |
| 1521 | Oracle DB | Oracle database listener |
| 3306 | MySQL | MySQL database service |
| 5500 | Oracle EM | Oracle Enterprise Manager |
| 7070 | HTTP Alt | Alternate web service port |

## Security Significance
Open ports indicate active services. If not properly secured, attackers may exploit them to gain unauthorized access.
