# 🌐 Lab 3: Router Configuration

## 🎯 Objective

To connect two different networks using a router and verify communication between them.

---

## 🛠️ Requirements

* 2 PCs
* 1 Router
* (Optional) 2 Switches
* Cisco Packet Tracer

---

## 🖼️ Topology

PC1 ---- Router ---- PC2

(Network 1)        (Network 2)

---

## ⚙️ IP Configuration

### 🖥️ PC1:

* IP Address: 192.168.1.2
* Subnet Mask: 255.255.255.0
* Default Gateway: 192.168.1.1

### 🖥️ PC2:

* IP Address: 192.168.2.2
* Subnet Mask: 255.255.255.0
* Default Gateway: 192.168.2.1

---

## ⚙️ Router Configuration (CLI)

```
enable
configure terminal

interface g0/0
ip address 192.168.1.1 255.255.255.0
no shutdown

interface g0/1
ip address 192.168.2.1 255.255.255.0
no shutdown
```

---

## 🔌 Steps to Configure

1. Open Cisco Packet Tracer
2. Add 2 PCs and 1 Router
3. Connect PC1 to Router (G0/0)
4. Connect PC2 to Router (G0/1)
5. Assign IP addresses to PCs
6. Configure router interfaces using CLI
7. Ensure interfaces are turned ON (`no shutdown`)

---

## 🔍 Testing Connectivity

From PC1, open Command Prompt and type:
ping 192.168.2.2

---

## ✅ Expected Output


Reply from 192.168.2.2: bytes=32 time<1ms TTL=127


---

## ❌ Troubleshooting

* Check if router interfaces are up (`no shutdown`)
* Verify correct IP addresses on PCs and router
* Ensure default gateway is configured correctly
* Check cable connections
* First ping may fail due to ARP (normal behavior)

---

## 🧠 Key Concepts

* Router operates at Layer 3 (Network Layer)
* It connects different networks
* Uses IP addresses to forward packets
* Default gateway is required for inter-network communication


---

## 📘 Conclusion

Successfully configured a router to connect two different networks and verified communication using ping.
