# vmware-windows-server2022-adds-domain-lab
🔧 A hands-on lab project simulating an enterprise network using VMware Workstation Pro, Windows Server 2022, and ADDS. Includes setup of a Primary Domain Controller (PDC), Additional Domain Controller (ADC), and a client PC in a Virtual LAN with manual IP configuration and domain management.

# 🛠️ ADDS Domain Network Setup using VMware Workstation Pro

Welcome to my project on **Active Directory Domain Services (ADDS)** in a **Virtual LAN environment** using **VMware Workstation Pro**! This project demonstrates how to configure and manage a domain network from scratch in a virtual lab setup.

---

## 📌 Project Overview

This project simulates a corporate-style network environment within VMware using:
- A **Primary Domain Controller (PDC)** 🧠
- An **Additional Domain Controller (ADC)** for redundancy 🔁
- A **Client/User PC** connected to the domain 💻

All devices are connected via a **Virtual Switch** in a **Virtual LAN (VLAN)** and use **manually configured IP addresses** for static communication.

---

## 🧰 Technologies & Tools Used

- 💻 **VMware Workstation Pro**
- 🖥️ **Windows Server 2022** (for both PDC and ADC)
- 🧑‍💻 **Windows 10/11** (Client Machine)
- 🌐 **Virtual LAN with Manual IP Configuration**
- 🛡️ **Active Directory Domain Services (ADDS)**
- 🔥 **Windows Defender Firewall Rules**

---

## ⚙️ Project Components

### 1️⃣ Server 1: Primary Domain Controller (PDC)
- Installed and configured **Active Directory Domain Services**
- Created a **new domain**: `tcs.com`
- Created and managed **users, groups, and OUs**
- Set up **Group Policy Management**
- Controlled **user permissions and password policies**

### 2️⃣ Server 2: Additional Domain Controller (ADC)
- Joined the existing domain `tcs.com`
- Promoted as **Additional Domain Controller**
- Acts as a **failover** controller when PDC is unavailable

### 3️⃣ Client PC
- Joined to domain `tcs.com`
- Verified domain login using credentials from Server 1
- Communicated via **ping tests** and **data sharing**

---

## 🔑 Key Highlights

✅ **Manual IP Configuration** for all machines  
✅ **Domain Creation & Client Join**  
✅ **Firewall configuration** to allow VLAN communication  
✅ **User & Group Management via ADDS**  
✅ **Redundancy using ADC setup**  
✅ **Ping tests & File sharing** between devices  
✅ **All setup done in isolated Virtual Network**

---

## 📂 Repository Structure

```bash
📁 ADDS-Domain-Network-Setup/
│
├── 📁 Screenshots/            # Setup screenshots
├── 📁 NetworkDiagrams/        # Topology diagrams and IP mapping
├── 📁 ConfigFiles/            # Text configs, commands, notes
├── 📄 README.md               # Project documentation
└── 📄 Project_Summary.pdf     # Short summary (optional)

