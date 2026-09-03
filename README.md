
# Agenda
0. Release information and Topology
1. ZTP Satellite provisioning procedure 
2. esat ports in VPRN as SAP.
3. Logging and Alarms of Satellite and esat ports
4. Qos – Buffer Allocation with various shaping rates.
5. Qos - Shaping of esat ports
6. Qos - ACL Egress FC Classification.
7. Qos - Scheduling Traffic correctly
   

# 0. Release information and Topology



# 1. ZTP Satellite provisioning procedure 
## Prerequisites
- Compact flash with the ZTP software kit for the 7250 IXR chassis
- The 7250 IXR MAC address printed on the chassis label or from the console during the ZTP autoboot
  (or can be found via console connection with “show chassis” CLI if IXR is loaded, or it can be found     in LOG 99 on 7750 SR host) 

## Procedure
- Insert the compact flash with the ZTP software kit in the 7250 IXR chassis.
- Connect the associated uplinks between the 7750 SR host and the 7250 IXR chassis 
- power on the 7250 IXR chassis.
- Obtain the MAC address from the 7250 IXR.
- Configure a software repository containing the IXR images (the example are on the following slides).
- Configure and enable the satellite on the host (the examples are on the following slides).
- Configure and enable the satellite uplinks (breakout, RS-FEC, and admin status enabled) and establish   the port-topology for the uplink-to-host port (the examples are on the following slides).




