This is a challenge to modify configuration in a network with Cisco devices that include multilayer switches. I resolved it in Packet Tracer to simulate the real situation. 
All devices are preconfigured. SW2 has been replaced with a multilayer switch
Hosts are in the correct VLANs.
SW1-SW2 are connected via trunk.
R1-SW2 are connected via ROAS.

What we want to do is:

Replace the ROAS configuration on R1-SW2 with a point-to-point Layer 3 connection.
    Use the IP addresses given in the network diagram.
    Configure a default route on SW2, with R1's G0/0 interface as the next hop.

Configure SVIs on SW2, one for each VLAN.
     Assign the last usable IP address of each subnet to the appropriate SVI.

Test inter-VLAN connectivity by pinging between VLANs.

Test connectivity to the Internet by pinging 1.1.1.1
    (Routes have already been configured on R1 and the Internet router)
