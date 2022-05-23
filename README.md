# iptables Malicious Countries
### Block Malicious Countries with ipset Blocklists


Blocks *all* IPv4 and IPv6 traffic from the following countries:
- China
- Russia
- Ukraine
- India
- Iran
- Vietnam
- Brazil
- Thailand
- Indonesia
- Pakistan
- Algeria

Then blocks all incoming SSH connections unless they are from Great Britain.


Also included is a debugging script to test SSH server security. Example run: `python ssh-audit.py -p <port> <hostname>`
