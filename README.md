# NSX-SDN-LAB
NSX Software-defined Networking Lab - Architected and Developed by Hany Michael 

# About
NSX SDN-LAB is a fully virtualized and nested lab running on VMware’s internal cloud. This lab is architected and developed by Hany Michael – Senior Staff Architect in the Networking & Security Business Unit. If you are a VMware employee, you have an instant access to this lab as a virtual pod which could be deployed as an independent and dedicated instance from the OneCloud portal. If you are a VMware customer or a partner and would like to have an access to the lab, you can contact your account team for further guidance. This lab is vendor neutral and any of its third-party vendors listed could be replaced if required. This architecture could be used also to illustrate some of VMware’s networking and security solutions and capabilities. All the information included in this architecture reflects the exact design and configuration of the NSX SDN-LAB including but not limited to: designs, product releases, hostnames, IP addresses and so forth. The lab is also designed to be modular and could be scaled to include more sites, network, servers and/or storage resources. The future development of this lab will be based on “add-ons” to introduce other networking technologies (like MPLS), topologies (like Service-Provider models) or external clouds (like Amazon AWS, Microsoft Azure, Google CPE just to name a few).

# NSX Design & Features
NSX System:
- 2 x NSX Managers in Cross-vCenter
- 3 x Universal Controllers
- CAI: 1 x Edge Cluster + 1 x Compute
- HBE: 1 x Collapsed Edge + Compute
