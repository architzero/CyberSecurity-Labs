# Linux Operating System Fundamentals, Access Control and Security

Hands-on cybersecurity laboratory work focused on Linux operating-system fundamentals, access control, privilege management, file permissions, Linux capabilities, shells, system administration, and security-relevant commands.

This lab was performed as part of the **Cyber Security Skill Development Lab (2026–28)** during my **M.Tech in Cyber Security, Semester I** at **Defence Institute of Advanced Technology (DIAT), Pune**.

---

## 1. Objective

The objective of this laboratory was to develop a practical understanding of Linux operating-system security mechanisms using a controlled Kali Linux virtual-machine environment.

The lab focused on:

- Understanding the Linux boot process
- Understanding Linux users, groups, UIDs and GIDs
- Understanding Linux file ownership and permissions
- Working with read, write and execute permissions
- Studying SUID, SGID and Sticky Bit
- Understanding Linux capabilities and fine-grained privilege assignment
- Working with Bash and Zsh
- Using security-relevant Linux commands
- Performing system, user, process, file and network analysis
- Identifying security weaknesses caused by excessive permissions and privileges
- Comparing Linux access-control mechanisms with Windows security mechanisms
- Applying the Principle of Least Privilege

---

# 2. Lab Environment

| Component | Configuration |
|---|---|
| Virtualization | Oracle VM VirtualBox |
| Operating System | Kali GNU/Linux Rolling |
| Installed Version | Kali 2026.2 |
| Kernel | 6.19.14+kali-amd64 |
| Architecture | x86_64 (64-bit) |
| Virtual CPUs | 2 |
| RAM | 4 GB |
| Virtual Disk | 40 GB VDI, dynamically allocated |
| Network | NAT |
| Hostname | `kali` |
| Primary User | `kali` |
| Default Shell | Zsh |
| Init/System Manager | systemd |
| Default Target | `graphical.target` |
