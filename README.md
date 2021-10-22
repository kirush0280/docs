# docs
Инструкции

 enable
 conf t
 interface vlan 1
 ip address 192.168.1.20 255.255.0.0
 !
 exit
 write
 
 Для 10:
 copy tftp://192.168.1.111/4600-10.cfg startup.cfg
 copy tftp://192.168.1.111/3900_4600/S4600-XXP(-P)-dev2xx(R0241.0470)_nos.img nos.img
 

 Для 28:
 copy tftp://192.168.1.111/4600-28.cfg startup.cfg
 copy tftp://192.168.1.111/3900_4600/DCN-S4600-10_dev3xx(R0241.0470)_nos.img nos.img
 
 reload
 
