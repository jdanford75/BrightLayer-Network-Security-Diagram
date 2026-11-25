# BrightLayer Analytics — Network Security Beyond Diagrams

**Jack Danford · Austin Community College · CSIS 3333, Lab 7**

[View the submitted network diagram (PDF)](brightlayer-network-security-diagram.pdf)

I mapped the trust boundaries and expected traffic for an academic network design. The diagram follows public HTTPS into a DMZ web server, then shows the intended application and database paths, remote access through a VPN with MFA, and the connection to a cloud storage provider.

## What I would verify

- Compare firewall rules with the flows drawn on the diagram, especially the boundaries between the DMZ and private subnets.
- Verify where VPN MFA is enforced and check what remote users and developers can reach.
- Confirm which system initiates the cloud storage connection and review the integration's permissions.
- Check that endpoint detection and response is reporting from the managed workstations shown.

The diagram records the proposed design and its assumptions. The lab did not test deployed configurations or control effectiveness.
