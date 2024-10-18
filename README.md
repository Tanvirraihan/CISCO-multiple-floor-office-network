# CISCO-multiple-floor-office-network



Project Name: Multiple Floor Office Network Design and Implementation
As part of your end-of-year networking project, you are required to design and implement the network for a multiple-floor office. The office has three floors. On the first floor, there are three departments (Reception, Store, and Logistics), on the second floor, there are three departments (Finance, HR, and Sales/Marketing), while the third floor hosts the IT and Admin departments. The following considerations should be taken into account during the design and implementation:
There should be three routers connecting each floor (all placed in the server room in the IT department).
All routers should be connected to each other.
The network between the routers should be 10.0.0.0, 11.0.0.0 ,12.0.0.0
Each floor is expected to have one switch (placed on the respective floor)
Each department should have a printer.
Each department should be in a different VLAN with the following details:
1st Floor:
Reception - VLAN 80, Network of 192.168.80.0/24
Store - VLAN 70, Network of 192.168.70.0/24
Logistics - VLAN 60, Network of 192.168.60.0/24
2nd Floor:
Finance - VLAN 50, Network of 192.168.50.0/24
HR - VLAN 40, Network of 192.168.40.0/24
Sales - VLAN 30, Network of 192.168.30.0/24
3rd Floor:
Admin - VLAN 20, Network of 192.168.20.0/24
IT - VLAN 10, Network of 192.168.10.0/24
Use OSPF as the routing protocol to advertise routes.
All devices in the network should obtain IP addresses dynamically, with their respective router configured as the DHCP server.
All devices in the network should be able to communicate with each other.
Configure SSH on all routers for remote login.
In the IT department, add a PC called  to port fa0/4 and use it to test remote login.
Configure port security on the IT department switch to allow only IT PC to access port fa0/1 (use the sticky method to obtain the MAC address, with a violation mode of shutdown). 
