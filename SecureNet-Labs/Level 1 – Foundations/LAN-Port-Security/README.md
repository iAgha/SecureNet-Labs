# LAN-Port-Security

## Objective
Build a small LAN network, implement port security, and simulate unauthorized device connections to practice SOC monitoring concepts.

## Steps
1. Assign static IPs to all PCs
2. Connect PCs to the switch and verify connectivity
3. Configure Port Security on switch ports:
   - Maximum MAC addresses per port = 1
   - Violation mode = shutdown
4. Connect an unauthorized device to trigger a port violation
5. Observe violation logs in Packet Tracer

## Security / SOC Insight
- Port Security prevents unauthorized devices from accessing the network
- Violations simulate SOC alerts/log monitoring
- Provides hands-on experience with incident detection and traffic control

## Tools Used
- Cisco Packet Tracer
- Git & GitHub
- AI-assisted documentation & planning tools (for README & lab structure)

## Included Files
- `diagrams/LAN_topology.png` – network diagram
- `configs/Switch1.txt` – switch configuration commands
- `configs/PCs_IPs.txt` – IP assignment table
- `labs/LAN_Port_Security.pkt` – Packet Tracer lab file