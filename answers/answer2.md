# ✅ Answer 2 – Subnetting /26 (4 subnets)

## Calculation
- Original: `192.168.1.0/24` → 256 addresses  
- Need 4 subnets → borrow 2 bits → **/26**  
- Subnet mask: **255.255.255.192**  
- Each subnet: **64 addresses → 62 usable**

---

### Subnet 1
- Network: `192.168.1.0/26`
- Usable: `192.168.1.1 – 192.168.1.62`
- *Broadcast: `192.168.1.63`
- Usable hosts: 62

### Subnet 2
- Network: `192.168.1.64/26`
- Usable: `192.168.1.65 – 192.168.1.126`
- Broadcast: `192.168.1.127`
- Usable hosts: 62

### Subnet 3
- Network: `192.168.1.128/26`
- Usable: `192.168.1.129 – 192.168.1.190`
- Broadcast: `192.168.1.191`
- Usable hosts: 62

### Subnet 4
- Network: `192.168.1.192/26`
- Usable: `192.168.1.193 – 192.168.1.254`
- Broadcast: `192.168.1.255`
- Usable hosts: 62
