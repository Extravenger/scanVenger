# Host and Port Discovery Tool

A powerful and flexible C# tool for discovering live hosts and scanning open ports in a network. Designed with penetration testers and network administrators in mind, this tool provides detailed insights into the network environment, including hostnames, operating systems, and open ports.

![Tool Demo](https://via.placeholder.com/800x400.png?text=Tool+Demo+Placeholder) <!-- Replace with an actual screenshot or GIF -->

---

## Features

- **Host Discovery**: Identify live hosts in a subnet using ICMP (ping).
- **Port Scanning**: Scan for open ports on discovered hosts.
- **FQDN Resolution**: Resolve IP addresses to Fully Qualified Domain Names (FQDNs).
- **OS Detection**: Detect the operating system of each host using TTL analysis.
- **Customizable Port Sets**: Predefined port sets for common services (e.g., web, admin, top 20 ports).
- **Concurrency Control**: Efficiently scan multiple hosts and ports concurrently.
- **Export Results**: Save scan results to a text file in a clean, tabular format.

---

## Prerequisites

Before using the tool, ensure you have the following:

- **.NET SDK**: The tool is written in C# and requires the .NET SDK to build and run. Download it from [here](https://dotnet.microsoft.com/download).
- **Permissions**: Administrative privileges may be required for certain operations (e.g., ICMP ping).

---

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/host-port-discovery-tool.git
   cd host-port-discovery-tool
