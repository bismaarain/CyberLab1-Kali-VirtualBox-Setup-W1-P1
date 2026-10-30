# Troubleshooting Notes

Record symptoms and verified fixes rather than assuming a cause.

## Network Interface Not Visible

1. Check the VM's adapter settings in VirtualBox.
2. Confirm that the virtual network adapter is enabled.
3. Boot Kali Linux and inspect interfaces with `ip address`.
4. Record the observed result.

## No Expected Network Connectivity

1. Confirm the selected VirtualBox network mode.
2. Inspect the guest IP configuration using `ip address`.
3. Inspect routes using `ip route`.
4. Review DNS resolver settings using `cat /etc/resolv.conf`.
5. Test IP reachability and DNS resolution separately where appropriate.
6. Record results before changing settings.

## Package Manager Appears Busy

Check whether another package operation is running and allow it to finish. Do not delete package lock files manually or terminate package-management processes blindly.
