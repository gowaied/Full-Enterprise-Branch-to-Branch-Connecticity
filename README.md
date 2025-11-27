# Full-Enterprise-Branch-to-Branch-Connecticity-lab-on-EVENG

This lab demonstrates a full end-to-end enterprise network between **two branches**, connected over the Internet with **GRE over IPsec VPN**, VLANs, HSRP, OSPF, and Layer-2 security.

## 🔍 Lab Topology

![Topology](topology.png)

## 🎯 Objectives / Tasks
1. Configure IP addressing on all devices.
2. Implement VLANs, HSRP, EtherChannel, and inter-VLAN routing.
3. Configure OSPF for dynamic routing.
4. Create a GRE over IPsec tunnel between the branch routers.
5. Apply Layer-2 security: DHCP Snooping, DAI, Port Security.
6. Verify end-to-end connectivity and redundancy.


## 🚀 How to Use This Lab
1. Import the topology file into EVE-NG.
2. Deploy all devices according to the topology.
3. Apply the configuration files.
4. Test connectivity and VPN functionality.

## ✅ Validation / Verification
- Ping between VLANs inside each branch
- Ping between branch LANs over GRE/IPsec
- Show OSPF neighbors (`show ip ospf neighbor`)
- Show HSRP status (`show hsrp brief`)
- Show IPsec tunnel (`show crypto isakmp sa`, `show crypto ipsec sa`)

## 📚 References
- [Cisco Documentation](https://www.cisco.com/)
- [EVE-NG Documentation](https://www.eve-ng.net/)
