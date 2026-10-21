# 🐧 Linux Labs

Hands-on labs covering Linux system administration, networking, and host security, built on local VirtualBox VMs (plus one AWS EC2 deployment). Each lab has a write-up with objectives, the steps I followed, screenshots, and key takeaways.

| # | Lab | Topics |
|---|---|---|
| 01 | [Deploy Linux Servers](lab-01-deploy-linux-servers/) | VirtualBox, Ubuntu Server, AWS EC2, Security Groups, SSH key pairs |
| 02 | [Deploy Services, Test, and Manage Workflow](lab-02-deploy-services-and-workflow/) | NAT/Host-only networking, OpenSSH, Apache2, systemctl, Git/GitHub deploy workflow |
| 03 | [Manage Access, Harden Services, Host Security Basics](lab-03-manage-access-harden-services/) | Users/groups, file permissions, sudo, SSH keys, sshd hardening, AllowGroups, ufw firewall |
| 04 | [Internetworking: One Router, Two Networks](lab-04-internetworking-one-router/) | Subnet planning, static IPs, VirtualBox internal networks, IP forwarding, default gateways |
| 05 | [Internetworking: Two Routers, Three Networks](lab-05-internetworking-two-routers/) | /29 subnetting, multi-router topology, static routes, next-hop routing, hop-by-hop troubleshooting |

## What I've Been Learning

Here's what I've picked up so far:

**Linux**
- Setting up Ubuntu Server VMs and getting comfortable on the command line
- Installing and running services like SSH and a web server (Apache)
- Managing users, groups, and who can access which files
- Getting a website from my laptop onto a server with Git and GitHub

**Networking**
- How a VM connects to the internet and to my own computer
- Planning subnets and giving machines static IPs
- How routers pass traffic between networks, and why every router needs to know the way there and the way back

**Security**
- Using SSH keys instead of passwords, and limiting who's allowed to log in
- Setting up a basic firewall that only lets in what's needed
- Always leaving myself a way back in before changing login settings (I learned that one by locking myself out)

## More Labs

- [☁️ Cloud Labs](https://github.com/willkhot/Cloud-Labs)
- [🔐 IAM Labs](https://github.com/willkhot/IAM-Labs)

## Author

**Will Khotsyphom**

[![GitHub](https://img.shields.io/badge/GitHub-willkhot-181717?logo=github)](https://github.com/willkhot)

## Security Note

Screenshots and commands in this repository are sanitized. Public IP addresses, hostnames, usernames and keys are redacted or replaced with placeholders. All cloud resources shown were terminated after each lab.
