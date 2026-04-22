
# Lab 01 – Basic Network Connectivity (Cisco Packet Tracer)

## Objective
The goal of this lab was to understand basic network communication by configuring two PCs with IP addresses and verifying connectivity using ICMP (ping).

---

## Tools Used
- Cisco Packet Tracer
- Command Prompt (within Packet Tracer)

---

## Topology
Two PCs connected directly using a copper cross-over cable.

![Topology](screenshots/lab01-step1-topology.png)

---

## Configuration

### PC0
- IP Address: 192.168.1.1
- Subnet Mask: 255.255.255.0

![PC0 Config](screenshots/lab01-step3-ipconfig-pc0.png)

### PC1
- IP Address: 192.168.1.2
- Subnet Mask: 255.255.255.0

![PC1 Config](screenshots/lab01-step4-ipconfig-pc1.png)

---

## Connectivity Test (Successful)

Ping from PC0 to PC1 was successful, confirming both devices are on the same network and can communicate.

![Successful Ping](screenshots/lab01-step5-successful-ping.png)

---

## Connectivity Test (Failure Scenario)

After changing PC1’s IP address to 192.168.2.2, the ping failed. This demonstrates how devices on different networks cannot communicate without a router.

![Failed Ping](screenshots/lab01-step6-failed-ping-test.png)

---

## Key Takeaways
- Devices must be on the same subnet to communicate directly
- IP addressing is critical for network communication
- Ping (ICMP) is a basic but powerful troubleshooting tool
- Misconfiguration leads to immediate connectivity failure

---

## Skills Practiced
- IP Configuration
- Subnet Awareness
- Network Troubleshooting
- Packet Tracer Simulation
