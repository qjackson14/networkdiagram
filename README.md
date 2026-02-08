<p align="center">

</p>

<h1></h1>
<br />


<h2>Video Demonstration</h2>

- ### [YouTube: Day 1 Lab Network Diagram](https://www.youtube.com/watch?v=ud9KieJKSJc)

<h2>Environments and Technologies Used</h2>

- Jeremy's IT Lab Youtube Channel
- Cisco Packet Tracer
  

  
<h2>Operating Systems Used </h2>

- Cisco IOS


<h2>Step-by-Step</h2>

<b>🟢 Part 1 — Understand the Network Diagram</b>

- Review the target topology from the lecture video.

- Identify the components in the design: Internet router, New York branch (PCs, switch, router, firewall), Tokyo branch (servers, switch, router, firewall), and the attacker device.

- Understand that your goal is to recreate this layout in Packet Tracer.

<b>🟢 Part 2 — Place Network Devices</b>

- Click Network Devices → Routers.

- Place two Cisco 2911 routers.

- Click Switches and place two 2960 switches.

- Click Firewalls and place two ASA 5505 firewalls.

- Click End Devices and place two PCs, two Servers, and one Laptop (attacker).

<b>🟢 Part 3 — Rename Devices</b>

- Click each device name to rename it.

- Rename the PCs to PC1 and PC2.

- Rename the switches to SW1 and SW2.

- Rename the routers to R1 and R2.

- Rename the firewalls to FW1 and FW2.

- Rename the servers to SRV1 and SRV2.

- Rename the laptop to Attacker.

 <b>🟢 Part 4 — Connect Devices</b>

- Click the Connections (lightning bolt) icon.

- Select Automatically Choose Connection Type.

- Connect PC1 → SW1.

- Connect PC2 → SW1.

- Connect SW1 → R1.

- Connect R1 → FW1.

- Connect FW1 → Internet.

- Connect Internet → R2.

- Connect R2 → FW2.

- Connect FW2 → SW2.

- Connect SW2 → SRV1.

- Connect SW2 → SRV2.

- Connect Attacker → Internet.

- Hold Ctrl while selecting the lightning bolt to keep the tool active.

- Click Cancel when finished.

<b>🟢 Part 5 — Access the CLI</b>

- Click a router or switch.

- Select the CLI tab.

- Use the CLI for device configuration.
