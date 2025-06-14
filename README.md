# Graylog-OPNsense-Extractors
Fork of IRQ10's Extractors for Graylog to parse OPNSense logs.

This fork adds extractors for the following on top of IRQ10's firewall extractors:

* DHCPD
* Lighttpd

## Versions

### This Fork
OPNSense 25.1.8_1
Graylog 6.2.3

### Upstream
OPNsense 24.7.12_2
Graylog 5.0.13+083613e, codename Noir

## Usage
1. Open Graylog as admin
2. Open 'System / Inputs', click on 'Inputs'
3. Select the input you forward OPNsense filterlog to. Click "More actions' > "Edit input", and ensure "Store full message?" is enabled.
4. For the input OPNsense is forwarding into, click on "Manage extractors"
5. Drop down "Actions" in the top right corner, then click "Import extractors"
6. Paste the contents of the desired JSON file into the box. Click "Add extractors to input"
