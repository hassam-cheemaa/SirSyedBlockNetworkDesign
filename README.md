# Sir Syed Block Network Design Project

Welcome to the **Sir Syed Block Network Design Project** repository! This project demonstrates the design and implementation of a scalable and reliable network infrastructure for the Sir Syed Block at Bahria University. It includes detailed documentation, configuration files, and testing results to showcase the practical application of networking concepts.

## 📚 Project Overview

The goal of this project is to design a network infrastructure connecting multiple offices, labs, and departments, ensuring seamless communication, resource sharing, and centralized management. The network is designed to support future scalability and maintain high security and efficiency.

### Features
- **Hybrid Topology**: Combines star and partial mesh structures for optimized connectivity.
- **IP Addressing Scheme**: Structured subnetting to avoid IP conflicts and simplify traffic management.
- **Protocol Implementation**: 
  - STP (Spanning Tree Protocol) to prevent loops.
  - RIPv1 for dynamic routing.
  - TCP/IP, DNS, and FTP for resource sharing and connectivity.
- **Centralized Resource Management**: Servers for DNS, FTP, and web hosting located in the server room.
- **Testing and Validation**: Comprehensive testing using tools like `ping` and `traceroute`.

---

## 🛠 Software Used

The project was developed using **Cisco Packet Tracer**, a beginner-friendly network simulation tool that allows easy design, configuration, and testing of network topologies.

---

## 📜 Network Design

### Topologies
- **Star Topology** for department-level connections.
- **Partial Mesh Topology** for inter-departmental communication.
- Subnets allocated to specific departments for efficient traffic management.

### IP Addressing Scheme
| Subnet          | Description                  | IP Range          |
|-----------------|------------------------------|-------------------|
| 192.168.1.0/24  | First Floor                  | 192.168.1.2 - .7  |
| 192.168.2.0/24  | OC Labs                      | 192.168.2.2 - .7  |
| 192.168.3.0/24  | Advisor Office               | 192.168.3.2 - .8  |
| 128.168.0.0/24  | HOD Office                   | 128.168.0.2 - .6  |
| 1.0.0.0/24      | Server Room                  | 1.0.0.2 - .5      |
| 192.168.4.0/24  | Security Room                | 192.168.4.2 - .3  |

---

## ⚙ Protocols Used
- **STP (Spanning Tree Protocol)**: Prevents loops and ensures network stability.
- **RIPv1**: Simplifies routing between subnets.
- **TCP/IP**: Ensures reliable data transmission.
- **DNS**: Resolves domain names for easy access.
- **FTP**: Facilitates file sharing across departments.
- **ICMP**: Used for testing connectivity.

---

## 🔍 Testing and Validation
- Connectivity tests performed using `ping` commands within and across subnets.
- Verified routing between departments using dynamic routing protocols.
- Simulated packet sniffing for troubleshooting.

---

## 🚀 Future Improvements
- Implement VLANs for enhanced traffic segmentation and security.
- Introduce wireless access points for mobile connectivity.
- Upgrade routing protocols to RIPv2 or OSPF for scalability.
- Integrate performance monitoring tools to track and optimize network performance.

---

## 📁 Repository Structure
- **Documentation**: Includes the detailed project report.
- **Configuration Files**: Contains the network setup files.

---

## 📞 Contributors
If you have any questions or suggestions, feel free to reach out to the contributors:
- **Muhammad Aadil Masaud** - Email: aadil11masaud@gmail.com
- **Muhammad Hassam Cheema** - Email: hassam.cheemaa@gmail.com
