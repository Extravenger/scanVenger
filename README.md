# Host and Port Discovery Tool

A tool built along the OSEP course, the idea came from when attempting to find hosts and open ports inside an internal network, but from windows machine.

## Features

- **Host Discovery**: Identify live hosts in a subnet.
- **Port Scanning**: Scan for open ports on discovered hosts.
- **FQDN Resolution**: Resolve IP addresses to Fully Qualified Domain Names (FQDNs).
- **OS Detection**: Detect the operating system of each host using TTL analysis.
- **Customizable Port Sets**: Predefined port sets for common services (e.g., web, admin, top 20 ports).

## Available Port Sets

    web: Ports 80, 443, 3000, 8080, 8081, 8443.

    admin: Ports 135, 139, 445, 1433, 3389, 5985, 5986.

    top20: Common ports (21, 22, 23, 25, 53, 80, 110, 111, 135, 139, 143, 443, 445, 993, 995, 1723, 3306, 3389, 5900, 8080).

    custom: Specify a custom list or range of ports (e.g., 80,443,8080 or 1000-2000).


## Video Sample

https://github.com/user-attachments/assets/d593f359-db7e-48e1-a4a3-a54d4fef3fad


