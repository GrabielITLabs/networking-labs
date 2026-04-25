# Lab 05 – Routing Between Two Networks

## Objective
Build two separate networks and use a router to allow communication between them.

---

## Step 1: Build the Topology
Created a network with two PCs on one side of a switch and one PC on a separate router interface.

![Topology](screenshots/lab05-step1-topology.png)

---

## Step 2: Connect PCs to the Switch
Connected PC0 and PC1 to the switch using copper straight-through cables.

![PCs to Switch](screenshots/lab05-step2-pcs-to-switch.png)

---

## Step 3: Connect Switch to Router
Connected the switch to the router to create the path out of Network A.

![Switch to Router](screenshots/lab05-step3-switch-to-router.png)

---

## Step 4: Connect PC2 to Router
Connected PC2 to a separate router interface to create Network B.

![PC2 to Router](screenshots/lab05-step4-pc2-to-router.png)

---

## Step 5: Configure Network A
Configured PC0 and PC1 with IP addresses in the 192.168.10.x network.

![PC0 Config](screenshots/lab05-step5-ipconfig-pc0.png)

![PC1 Config](screenshots/lab05-step5-ipconfig-pc1.png)

---

## Step 6: Configure Network B
Configured PC2 with an IP address in the 192.168.20.x network.

![PC2 Config](screenshots/lab05-step6-ipconfig-pc2.png)

---

## Step 7: Configure Router Interfaces
Configured router interfaces for both networks and enabled them using `no shutdown`.

![Router Config](screenshots/lab05-step7-router-config.png)

---

## Step 8: Verify Cross-Network Connectivity
Tested communication from Network A to Network B using ping.

![Cross-Network Ping](screenshots/lab05-step8-successful-cross-network-ping.png)

---

## What I Learned
- Switches connect devices within the same local network.
- Routers connect different networks together.
- Default gateways allow devices to send traffic outside their local network.
- A single incorrect cable, port, or interface configuration can break communication.
- The first ping may fail while the device learns the path using ARP.

---

## Cybersecurity Standards & Findings Connection
This lab connects directly to network segmentation and control validation.

In a cybersecurity standards and findings role, this matters because:
- Different networks often represent different trust zones.
- Routers and gateways control communication between those zones.
- Misconfigured interfaces, wrong gateways, or incorrect physical connections can create findings.
- Evidence such as IP configurations, router interface status, and ping results helps support technical conclusions.

---

## Skills Demonstrated
- Switch and router connectivity
- Static IP addressing
- Default gateway configuration
- Router interface configuration
- Cross-network communication testing
- Basic network troubleshooting

---

## Tools & Technologies
- Cisco Packet Tracer
