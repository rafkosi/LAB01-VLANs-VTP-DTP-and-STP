Task 1
Enable and configure VTP on the switches illustrated in the topology as
follows:
All switches should reside in VTP domain ‘SWITCH’
All switches should run VTP version 2
All switches should allow VLAN creation, deletion and modification
All switches should use a VTP password of ‘CCNP’

Task 2
Configure trunking on the switches as follows:
Configure ALS1 so that its interfaces will only trunk if the upstream
switch is trunking
Configure ALS2 so that its interfaces will only trunk if the upstream
switch is trunking
Configure DLS1 so that its interfaces will actively attempt to become
trunk links
Configure DLS2 so that its interfaces will actively attempt to become
trunk links

Task 3
Configure the following VLANs only on switch DLS1:
VLAN 100 name USER-VLAN
VLAN 200 name FILE-VLAN
Configure switch DLS1 so that Cisco IOS software automatically elects it as
the root bridge for both VLANs without explicitly specifying a priority value.
Ensure that switch DLS2 is also automatically elected backup root bridge for
both VLANs.

Task 4
Configure Spanning Tree on switches ALS1 and ALS2 as follows:
Port Fa0/7 on ALS1 and port Fa0/9 on ALS2 should be forwarding for
VLAN 100
Port Fa0/9 on ALS1 and port Fa0/7 on ALS2 should be forwarding for
VLAN 200

Task 5
Configure your 802.1D network to improve convergence as follows:
Backup ports on Access layer switches should transition to forwarding
in 1 to 5 seconds following the failure of the primary link to the root
bridge
In the event of an indirect link failure, the network should converge
within 30 seconds instead of the typical 50 seconds
