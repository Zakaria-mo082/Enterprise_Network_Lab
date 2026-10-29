# Enterprise_Network_Lab
# Multi-Site Enterprise Network Lab (Cisco Packet Tracer)

A simulated enterprise network featuring a Headquarters (Toronto) and a Branch site connected via a serial WAN, utilizing dynamic OSPF routing and VLAN segmentation.

## 🛠️ Key Configurations
- **Router-on-a-Stick:** Configured subinterfaces on R1 and R2 for VLAN 10 (Finance), VLAN 20 (Engineering), and VLAN 30 (Guest).
- **Routing Protocol:** OSPF enabled across all routers and WAN serial links (`10.1.1.0/30`).
- **Trunking:** Verified 802.1Q trunking between Cisco switches and routers.
- **Addressing:** Dual-stack support configuration notes for IPv4 and IPv6 (`2001:DB8::/32`).
