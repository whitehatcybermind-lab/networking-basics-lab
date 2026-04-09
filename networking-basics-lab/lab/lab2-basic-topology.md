# 🌐 Lab 2: Basic Network Topology

## 🎯 Objective

To create a basic Local Area Network (LAN) using a switch and verify connectivity between devices.

---

## 🛠️ Requirements

* 2 PCs
* 1 Switch
* Cisco Packet Tracer

---

## 🖼️ Topology

PC1 -------- Switch -------- PC2

---

## ⚙️ IP Configuration

### 🖥️ PC1:

* IP Address: 192.168.1.1
* Subnet Mask: 255.255.255.0

### 🖥️ PC2:

* IP Address: 192.168.1.2
* Subnet Mask: 255.255.255.0

---

## 🔌 Steps to Configure

1. Open Cisco Packet Tracer
2. Add 2 PCs and 1 Switch
3. Connect both PCs to the switch using copper straight-through cable
4. Assign IP addresses to both PCs
5. Wait for link lights to turn green

---

## 🔍 Testing Connectivity

Open Command Prompt on PC1 and type:
ping 192.168.1.2


---

## ✅ Expected Output

Reply from 192.168.1.2: bytes=32 time<1ms TTL=128

---

## ❌ Troubleshooting

* Check if both PCs are connected to the switch
* Ensure correct IP configuration
* Verify that both devices are in the same subnet
* Wait for switch ports to become active (green light)

---

## 🧠 Key Concepts

* Switch operates at Layer 2 (Data Link Layer)
* It uses MAC addresses to forward data
* Devices in the same network can communicate without a router


---

## 📘 Conclusion

Successfully created a LAN using a switch and verified communication between devices using ping.
