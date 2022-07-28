# Hotel-_Management_Network_System
Download the project and unzip and open it using cisco packet tracer

##############
address space given 192.168.10.0/24


Five departments:  all departments use 255.255.255.224 as a subnet mask 
 
        range of IP address      BRoadcast Ip
ADMINISTRATION  192.168.10.0  192.168.10.1- 192.168.10.30                      192.168.10.31 

SALES 192.168.10.32 
           Range of IP addresses          192.168.10.33 to 192.168.10.62      192.168.10.63  

FINANCE
192.168.10.64
                     192.168.10.65 -192.168.10.94                              192.168.10.95          

SECURITY
192.168.10.96
                 192.168.10.97 -192.168.10.126                                  192.168.10.127 

TRANSPORT AND PACKING
192.168.10.128
                     192.168.10.129 -192.168.10.158                              192.168.10.159   

SERIAL LINKS(SERIAL ROUTERS)
192.168.10.160
   192.168.10.161 -  192.168.10.190                                              192.168.10.191     
         

#################################################################


SWITCH:
vlan are created : admin/IT vlan 10             fa0/1-4
                   finance/HR  vlan 20           fa0/5-8
                   customer service/reception vlan 30  fa0/9-12


interface gig0/2 is a trunckport to transfer traffic from switch to router to 
DHCP pools are configured on the switch according to the vlan

########################################################
ROUTER
Inter-vlan routing is configure on the router(ROSA- Router On the Stick)
##############################################
WLAN
Every wireless has its own SSID rhyming the department it belongs and the Service Set Identifier on its Access points
Administration 
smartphone/tablet  ................SSID is administration
finance   
smartphone/tablet      ................SSID is financedepartment
Security
smartphone/tablet      ................SSID is security
Transport/Packing

Sales
smartphone/tablet      ................SSID is salesdepartment
#######################################################################

Each department has its own DHCP SERVER from its subnet and designed in its own VLAN.
The subnets are linked together via two routers with serial links




Main router/switch: 
enable password: cisco
console password:class
line vty 0 15 : class
line aux 0: class
Developed by Nandokha Collins
nandokhacollins0@gmial.com
0758974868
