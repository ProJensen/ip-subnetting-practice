# ✅ Answer 1 – Subnetting /25 (2 subnets)

## Calculation
- Original: `192.168.1.0/24` → 256 addresses
- Need 2 subnets → borrow 1 bit → /25
- Subnet mask `255.255.255.128`
- Each subnet: 128 address → 126 usable

---

### Subnet 1:
- Network: `192.168.1.0/25`
- Usable: `192.168.1.1 - 192.168.1.126`
- Broadcast: `192.168.1.127`
- Hosts: 126

### Subnet 2:
- Network: `192.168.1.128/25`
- Usable: `192.168.1.129 - 192.168.1.254`
- Broadcast: `192.168.1.255`
- Hosts: 126

![/25 Calculation](https://raw.githubusercontent.com/ProJensen/ip-subnetting-practice/refs/heads/main/Calculation/%3A25.png)
