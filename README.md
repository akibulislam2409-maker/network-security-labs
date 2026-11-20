# 🔐 Network Security Labs

Security design and Cisco configuration for a three-campus institute network, from **COMP516 Fundamentals of Network Security** (Grade: A-).

## What's inside
### Part 1: Securing a three-campus WAN (Cisco Packet Tracer)
- Three-router WAN with `/30` serial links and **RIPv2** routing
- **SSH** remote access (domain name, RSA keys, local users) instead of Telnet
- `enable secret`, console and VTY password security
- **AAA authentication**
- Security domains and policy design

### Part 2: Practical security configurations
- Access control lists (**ACLs**) and network access control policies
- **VLAN** segmentation and traffic control
- **Firewall vs VLAN** comparison, and **DMZ** design
- Attack mitigation, covering ARP spoofing, DDoS and more

### Report topics
Threat actors, how attackers exploit switches and routers, edge routers, firewalls and DMZs, **VPN and IPsec**, and the CIA triad.

## 📁 Files
```
part1-wan-security/
  aaa_ssh_security.pkt
  ip_addressing_table.xlsx
  static_routing_commands.xlsx
  three_campus_wan.pkt
  configs/
    aaa_ssh_config.txt
    three_campus_wan_config.txt
part2-security-policies/
  q1_part_d.pkt
  q2_part_a.pkt
  q2_part_b.pkt
  q2_part_c.pkt
  q2_part_d.pkt
```

## ▶️ How to open
Open the `.pkt` files in **Cisco Packet Tracer**. Device configs are in `configs/`.

> The passwords in these configs are lab examples only.

**Skills:** SSH · AAA · ACL · RIPv2 · VLAN · DMZ · VPN/IPsec concepts · Cisco IOS hardening
