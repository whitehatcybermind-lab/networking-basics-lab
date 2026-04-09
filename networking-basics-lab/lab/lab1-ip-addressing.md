# 🌐 Lab 1: IP Addressing

## 🎯 Objective

To assign IP addresses to devices and test network connectivity using the ping command.

---

## 🛠️ Requirements

* 2 PCs
* 1 Switch (optional but recommended)
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
3. Connect PCs to switch using copper straight-through cable
4. Click on PC → Desktop → IP Configuration
5. Assign IP addresses as mentioned above

---

## 🔍 Testing Connectivity

Open Command Prompt on PC1 and type:
ping 192.168.1.2


---

## ✅ Expected Output

Reply from 192.168.1.2: bytes=32 time<1ms TTL=128


---

## ❌ Troubleshooting

* Check if IP addresses are in same network
* Check if cables are properly connected
* Ensure devices are powered on
* Wait for link lights to turn green

---

## 🧠 Key Concepts

* Devices in same network can communicate directly
* Switch helps in connecting devices in a LAN
* Ping command is used to test connectivity


---

## 📘 Conclusion

Successfully configured IP addresses and verified communication between two devices in the same network.
