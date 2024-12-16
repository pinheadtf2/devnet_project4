# Overlay
- Router (1x)
- Switch | Layer 2 (1x)
- Computer (2x)

# Connections
## Router
- **G0/0/1:** Connect to _Switch F0/1_
  - IP: 192.168.1.1
  - Subinterfaced
  - DHCP activated, range 192.168.1.21-254

## Switch
- **F0/1:** Connect to _Router G0/0/1_
  - VLAN 10 IP: 192.168.1.10
  - Trunked switchport
- **F0/23:** Connect to Computer 1
- **F0/24:** Connect to Computer 2 

# Extras
- **Username:** admin
- **Password:** Admin123!
- **Domain:** lab.pinhead.dev
