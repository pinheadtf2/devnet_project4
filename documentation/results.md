# Initial Setup
- DHCP may act strange and refuse to distribute IPs
  - Double check physical connections
  - Ensure interfaces are not shut down

# Past Issues
- Ansible password was incorrectly configured
  - Written as: Password123!
  - Actual: Admin123!
- Router-Switch link was misconfigured
  - No-shut command was not written in basic config file
  - Physical link was from G0/0/0 