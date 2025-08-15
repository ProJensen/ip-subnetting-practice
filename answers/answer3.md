# ✅ Answer 3 – Subnetting /27 (8 subnets)

## Calculation
- Original: `192.168.1.0/24` → 256 addresses  
- Need 8 subnets → borrow 3 bits → **/27**  
- Subnet mask: **255.255.255.224**  
- Each subnet: **32 addresses → 30 usable**  

---

### Subnet 1
- **Network:** `192.168.1.0/27`
- **Usable:** `192.168.1.1 – 192.168.1.30`
- **Broadcast:** `192.168.1.31`
- **Usable hosts:** 30

### Subnet 2
- **Network:** `192.168.1.32/27`
- **Usable:** `192.168.1.33 – 192.168.1.62`
- **Broadcast:** `192.168.1.63`
- **Usable hosts:** 30

### Subnet 3
- **Network:** `192.168.1.64/27`
- **Usable:** `192.168.1.65 – 192.168.1.94`
- **Broadcast:** `192.168.1.95`
- **Usable hosts:** 30

### Subnet 4
- **Network:** `192.168.1.96/27`
- **Usable:** `192.168.1.97 – 192.168.1.126`
- **Broadcast:** `192.168.1.127`
- **Usable hosts:** 30

### Subnet 5
- **Network:** `192.168.1.128/27`
- **Usable:** `192.168.1.129 – 192.168.1.158`
- **Broadcast:** `192.168.1.159`
- **Usable hosts:** 30

### Subnet 6
- **Network:** `192.168.1.160/27`
- **Usable:** `192.168.1.161 – 192.168.1.190`
- **Broadcast:** `192.168.1.191`
- **Usable hosts:** 30

### Subnet 7
- **Network:** `192.168.1.192/27`
- **Usable:** `192.168.1.193 – 192.168.1.222`
- **Broadcast:** `192.168.1.223`
- **Usable hosts:** 30

### Subnet 8
- **Network:** `192.168.1.224/27`
- **Usable:** `192.168.1.225 – 192.168.1.254`
- **Broadcast:** `192.168.1.255`
- **Usable hosts:** 30

![/27](https://raw.githubusercontent.com/ProJensen/ip-subnetting-practice/refs/heads/main/Calculation/%3A27.png)
