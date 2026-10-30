# Virtual Networking Notes

Record the network mode selected for the lab and why it was chosen.

## Common VirtualBox Modes

- **NAT:** The guest can generally access external networks through the host's network connection. Inbound access to the guest is not automatically exposed.
- **Bridged Adapter:** The guest appears as a separate device on the connected network. Use only where permitted and appropriate.
- **Host-only Adapter:** Provides communication between the host and guest on a private virtual network, typically without direct external connectivity.
- **Internal Network:** Allows communication between VMs attached to the same named internal network.

## Lab Record

- Selected mode:
- Adapter name:
- Addressing method:
- Reason for selection:
- Verification performed:

Choose a mode based on the lab objective and keep security boundaries in mind. Do not assume a mode is configured until it has been checked in VirtualBox.
