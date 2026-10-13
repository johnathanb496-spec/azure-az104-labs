# Azure AZ-104 Course Labs

Bicep lab files from my AZ-104 (Azure Administrator) exam preparation, built by following Alan Rodrigues' Udemy course and Microsoft Learn labs. I passed the exam.

These are course exercises, not original designs. I keep them as a reference.

## Contents

- `Labs/` has Bicep modules for a virtual network, NSG, storage account, Windows and Linux VMs, internal load balancer, public IP, and VNet peering.
- `main.bicep` and `dev.parameters.json` tie the modules together. The module paths in `main.bicep` reflect my original local layout, so it won't run as-is.
- Secrets and identifiers have been removed from the parameters file.

## Known limitation

The NSG sample allows RDP from any source. That was a lab shortcut and should never be used in production.