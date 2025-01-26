# Host and Port Discovery Tool

A tool inspired by the OSEP course, designed to identify hosts and open ports within an internal network from a Windows machine. 

> [!CAUTION]
> There may be false positives in hostname resolution for machines that do not exist within the domain you are currently scanning from.

##  Features

- **Host Discovery**: Identify live hosts in a subnet.
- **Port Scanning**: Scan for open ports on discovered hosts.
- **FQDN Resolution**: Resolve IP addresses to Fully Qualified Domain Names (FQDNs).
- **OS Detection**: Detect the operating system of each host using TTL analysis.
- **Customizable Port Sets**: Predefined port sets for common services (e.g., web, admin, top 20 ports).

## 🖧 Available Port Sets

    web: Ports 80, 443, 3000, 8080, 8081, 8443.

    admin: Ports 135, 139, 445, 1433, 3389, 5985, 5986.

    top20: Common ports (21, 22, 23, 25, 53, 80, 110, 111, 135, 139, 143, 443, 445, 993, 995, 1723, 3306, 3389, 5900, 8080).

    custom: Specify a custom list or range of ports (e.g., 80,443,8080 or 1000-2000).


## 🎥 Video Sample

https://github.com/user-attachments/assets/0c38f23f-e96f-4ccd-a805-129bbb733fdd



